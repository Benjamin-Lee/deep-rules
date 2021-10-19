> ## Reviewer 2
>
> The article titled “Ten Quick Tips for Deep Learning in Biology” provides a review of potential challenges to employing deep learning in biomedical research.
> This well written article is of importance at a time when deep learning is broadly viewed as a magic solution to many prediction and modelling problems.
> It cautions the inexperienced and reminds the experienced researcher that while DL has led to remarkable advances in certain applications, it is far from guaranteed to succeed in a broad range of biomedical applications for a gamut of reasons, can lead the researcher astray, be time consuming to develop, and result in unexpected ethical risks.
> While the article is well written, easy to follow and of interest to the readership, a few points for improvement are worth considering prior to publication:
>
> ### Major comments
> - In point 10, Distributed learning should be mentioned. An example reference: https://www.sciencedirect.com/science/article/pii/S0010482521005102

Thank you for this suggestion. We have added this sentence to point 10:

"Other methods, such a distributed learning, in which small subsets of the data are processed independently in silos (possibly by different agents), are also promsing but requrie careful investigation before applying to protected information [@doi:10.1016/j.compbiomed.2021.104716]."

> - I think it might be worth to further emphasis how results should be evaluated in the presence of class imbalance and risk/benefits of incorrect/correct predictions in the context of the specific application. 



> On a similar note, it is mentioned that AUCROC may not be reliable, but consider recommending alternatives such as precision-recall curves.

We appreciate the suggestion to include an alternative and have added the follwing sentence: "One alternative approach is to use the precision-recall curve rather than the receiver operating characteristic since the former is more resistant to imbalanced data [@doi:10.1145/1143844.1143874]."

>
> ### Minor comments:
> - Lines 153: those though

We have corrected this typo.
>
> - Line 183 is missing a period

We have added the missing period.

> - Paragraph starting at line 271: This paragraph is cumbersome and contains jargon that is not introduced (CUDA/CuDNN). Is it implied that implementation (hardware and software) variations between platforms can hinder reproducibility? Or perhaps the implementation is reproducible, so long that random seeding is not used?
>

The paragraph now reads:

A specific reproducibility pitfall that is often missed in applying deep learning is the use (often by default) of non-deterministic algorithms.
For example, the GPU acceleration libraries, such as CUDA/CuDNN, that facilitate the parallelized computing powering state-of-the-art deep learning often use algorithms by default that produce different outcomes from iteration to iteration even with the same hardware and sofrware.
Therefore, achieving reproducibility in this context requires explicitly specifying the use of deterministic algorithms (which are typically available within deep learning libraries).
This step is distinct from and in addition to the setting of random seeds that typically achieve reproducibility by controlling pseudorandom deterministic procedures such as shuffling and initialization [@url:https://docs.nvidia.com/deeplearning/sdk/cudnn-developer-guide/index.html#reproducibility].
---
author-meta:
- Benjamin D. Lee
- Alexander J. Titus
- Kun-Hsing Yu
- Marc G. Chevrette
- Paul Allen Stewart
- Evan M. Cofer
- Sebastian Raschka
- Finlay Maguire
- Benjamin J. Lengerich
- Alexandr A. Kalinin
- Anthony Gitter
- Casey S. Greene
date-meta: '2019-02-28'
keywords:
- quick tips
- machine learning
- deep learning
- artificial intelligence
lang: en-US
title: Ten Quick Tips for Deep Learning in Biology
...






<small><em>
This manuscript
([permalink](https://Benjamin-Lee.github.io/deep-rules/v/8e74d282ca30d10d2ee86645d6cd7f2d5147a579/))
was automatically generated
from [Benjamin-Lee/deep-rules@8e74d28](https://github.com/Benjamin-Lee/deep-rules/tree/8e74d282ca30d10d2ee86645d6cd7f2d5147a579)
on February 28, 2019.
</em></small>

## Authors
Please note the current author order is chronological and does not reflect the final order.



+ **Benjamin D. Lee**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0002-7133-8397](https://orcid.org/0000-0002-7133-8397)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [Benjamin-Lee](https://github.com/Benjamin-Lee)<br>
  <small>
     Lab41, In-Q-Tel; School of Engineering and Applied Sciences, Harvard University; Department of Genetics, Harvard Medical School
  </small>

+ **Alexander J. Titus**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0002-0145-9564](https://orcid.org/0000-0002-0145-9564)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [AlexanderTitus](https://github.com/AlexanderTitus)<br>
  <small>
     Titus Analytics
  </small>

+ **Kun-Hsing Yu**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0001-9892-8218](https://orcid.org/0000-0001-9892-8218)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [khyu](https://github.com/khyu)<br>
  <small>
     Department of Biomedical Informatics, Harvard Medical School
  </small>

+ **Marc G. Chevrette**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0002-7209-0717](https://orcid.org/0000-0002-7209-0717)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [chevrm](https://github.com/chevrm)<br>
  <small>
     Department of Genetics, University of Wisconsin-Madison; Department of Bacteriology, University of Wisconsin-Madison
  </small>

+ **Paul Allen Stewart**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0003-0882-308X](https://orcid.org/0000-0003-0882-308X)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [pstew](https://github.com/pstew)<br>
  <small>
     Biostatistics and Bioinformatics Shared Resource, Moffitt Cancer Center
  </small>

+ **Evan M. Cofer**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0003-3877-0433](https://orcid.org/0000-0003-3877-0433)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [evancofer](https://github.com/evancofer)<br>
  <small>
     Lewis-Sigler Institute for Integrative Genomics, Princeton University; Graduate Program in Quantitative and Computational Biology, Princeton University
  </small>

+ **Sebastian Raschka**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0001-6989-4493](https://orcid.org/0000-0001-6989-4493)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [rasbt](https://github.com/rasbt)<br>
  <small>
     Department of Statistics, University of Wisconsin-Madison
  </small>

+ **Finlay Maguire**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0002-1203-9514](https://orcid.org/0000-0002-1203-9514)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [fmaguire](https://github.com/fmaguire)<br>
  <small>
     Faculty of Computer Science, Dalhousie University
  </small>

+ **Benjamin J. Lengerich**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0001-8690-9554](https://orcid.org/0000-0001-8690-9554)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [blengerich](https://github.com/blengerich)<br>
  <small>
     Computer Science Department, Carnegie Mellon University
  </small>

+ **Alexandr A. Kalinin**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0003-4563-3226](https://orcid.org/0000-0003-4563-3226)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [alxndrkalinin](https://github.com/alxndrkalinin)<br>
  <small>
     Department of Computational Medicine and Bioinformatics, University of Michigan
  </small>

+ **Anthony Gitter**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0002-5324-9833](https://orcid.org/0000-0002-5324-9833)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [agitter](https://github.com/agitter)
    · ![Twitter icon](images/twitter.svg){height="13px" width="13px"}
    [anthonygitter](https://twitter.com/anthonygitter)<br>
  <small>
     Department of Biostatistics and Medical Informatics, University of Wisconsin-Madison; Morgridge Institute for Research
  </small>

+ **Casey S. Greene**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0001-8713-9213](https://orcid.org/0000-0001-8713-9213)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [cgreene](https://github.com/cgreene)<br>
  <small>
     Department of Systems Pharmacology and Translational Therapeutics, Perelman School of Medicine, University of Pennsylvania
  </small>



## Introduction {#intro}

Deep learning (DL), a subfield of machine learning (ML) implementing artificial neural networks with many layers, is increasingly used for the analysis of biological data [@PZMP42Ak].
In many cases, novel biological insights have been revealed through careful evaluation of DL methods ranging from predicting protein-drug binding kinetics [@lwg6sPLT] to identifying the lab-of-origin of synthetic DNA [@WGfstNkj].
However, a lack of concise recommendations for biological applications of DL hamper newcomers wishing to apply state-of-the-art DL in their research.
As DL is an active and specialized research area, detailed resources are rapidly rendered obsolete and few resources articulate general DL best practices to the scientific community broadly and the biological community specifically.
To address this issue, we solicited input from a community of researchers with varied biological and deep learning interests, who wrote this manuscript collaboratively using the GitHub version control platform [@ysdRl4lj] and Manubot [@1GGGHdsew].

In the course of our discussions, several themes became clear: the importance of understanding and applying ML fundamentals  [@p4Nl5If0] as a baseline for utilizing DL, the necessity for extensive model comparisons with careful evaluation, and the need for critical thought in interpreting results generated by means of DL, among others.
Ultimately, the tips we collate range from high-level guidance to the implementation of best practices, and it is our hope that they will provide actionable, DL-specific advice for both new and experienced DL practitioners alike who would like to employ DL in biological research.
By increasing the accessibility of DL techniques to biology, we aim to improve the overall quality and reporting of DL in the literature, enabling more researchers to apply these powerful methods to generate biological insights.


## Tip 1: Concepts that apply to machine learning also apply to deep learning {#concepts}
Deep learning is a distinct subfield of machine learning, but it is still a subfield.
DL has proven to be an extremely powerful paradigm capable of outperforming “traditional” machine learning approaches in certain contexts, but it is not immune to the many limitations inherent to machine learning.
Many best practices for machine learning also apply to deep learning.
Like all computational methods, deep learning should be applied in a systematic manner that is reproducible and rigorously tested.

Those developing deep learning models should select data that are relevant to the problem at hand; non-salient data can hamper performance or lead to spurious conclusions.
Biases in testing data can also unduly influence measures of model performance, and it may be difficult to directly identify confounders from the model.
Investigators should consider the extent to which the outcome of interest is likely to be predictable from the input data and begin by throughly inspecting the input data.
Suppose that there are robust heritability estimates for a phenotype that suggest that the genetic contribution is modest but a deep learning model predicts the phenotype with very high accuracy.
The model may be capturing signal unrelated to genetic mechanisms underlying the phenotype.
In this case, a possible explanation is that people with similar genetic markers may have shared exposures.
This is something that researchers should probe before reporting unrealistic accuracy measures.
A similar situation can arise with tasks for which inter-rater reliability is modest but deep learning models produce very high accuracies.
When coupled with imprudence, data that is confounded, biased, skewed, or of low quality will produce models of dubious performance and limited generalizability.

Using a test set more than once will lead to biased estimates of the generalization performance  [@1CDx6NYSj; @hJQdIoO3].
Deep supervised learning models should be trained, tuned, and tested on non-overlapping datasets.
The data used for testing should be locked and only used one-time for evaluating the final model after all tuning steps are completed.
Also, many conventional metrics for classification (e.g. area under the receiver operating characteristic curve or AUROC) have limited utility in cases of extreme class imbalance [@u86hHJ9b].
Model performance should be evaluated with a carefully-picked panel of relevant metrics that make minimal assumptions about the composition of the testing data [@rKXyJKNt], with particular consideration given to metrics that are most directly applicable to the task at hand.

Extreme cases warrant testing the robustness of the model and metrics on simulated data for which the ground truth is known.
Said simulations can be used to verify the correctness of the model’s implementation as well.


## Tip 2: Use traditional methods to establish performance baselines {#baselines}

Before diving into a fancy thousand-layer neural network, always implement at least a simple model to establish an adequate performance baseline.
For example, researchers can build multinomial logistic regression or random forest models using the same software framework that is being used for DL and evaluate its classification performance.
This approach will help researchers with assessing the complexity of the task at hand and debugging more complex DL architectures.
The utility of these methods is evidenced by the recent development of hybrid models which combine DL and simpler models to improve robustness, interpretability, and confidence estimation [@uBcf6TJ2; @2bsGpiQt].
Depending on the amount of available data and the type of tasks, DL models may not necessarily be the best performing one.
As an illustration, the simple baseline models by Rajkomar et al. [@1DssZebFm] achieved performance comparable with that of DL in a number of clinical prediction tasks using electronic health records, which may be a surprise to many.

It is worth noting that conventional machine learning methods (e.g., support vector machines, random forests) are also likely to benefit from parameter tuning.
It can be tempting to train baseline models with these conventional methods using default parameters, which may provide acceptable but not stellar performance, but then tune the parameters for DL models to optimize performance.
Hu and Greene [@5CsWRjfp] discuss a Continental Breakfast Included effect by which unequal hyperparameter tuning skews the evaluation of methods, especially those with performance that varies substantially with modest changes to hyperparameters.
Those wishing to compare methods should tune the parameters of traditional and DL to optimize performance before making claims about relative performance differences.
The performance comparison among DL models and many other ML approaches is informative only when the models are similarly tuned.


## Tip 3: Understand the complexities of training deep neural networks {#complexities}

Correctly training deep neural networks is a non-trivial process.
There are many different options and potential pitfalls at every stage.
To get good results you have to expect to train many networks with a range of different parameter and hyperparameter settings.
Despite improved framework ease-of-use and on-demand cloud computing resources this means DL can be very demanding, often requiring significant infrastructure and patience to achieve state-of-the-art performance [@L7EocHX2].
The experimentation inherent to DL is often noisy (requiring repetition) and represents a significant organizational challenge.
All code, random seeds, parameters, and results must be carefully corralled using good coding practices (for example, version control, continuous integration etc.) in order to be effective and interpretable.
This organization is also key to being able to efficiently share your work and to update your model as new data becomes available. 

One specific reproducibility pitfall that is often missed is the default use of non-deterministic algorithms by CUDA/CuDNN backends when training on GPUs.
Making this process reproducible is distinct from setting random seeds, which will primarily affect pseudorandom deterministic procedures such as shuffling and initialization, and requires explicitly specifying the use of deterministic algorithms in your DL library [@1GSwNJdl7]. 

Similar to [Tip 4](#baselines), try to start with a relatively smaller network and increase the size and complexity as needed to prevent wasting time and resources. 
Beware of the seemingly trivial choices that are being made implicitly by default settings in your framework of choice e.g. choice of optimization algorithm (adaptive methods often lead to faster convergence during training but may lead to worse generalization performance on independent datasets [@mIx19cpn]).
These need to be carefully considered and their impacts evaluated (see [Tip 6](#hyperparameters)).


## Tip 4: Know your data and your question {#know-your-problem}

Having a well-defined scientific question and a clear analysis plan is crucial for carrying out a successful deep learning project.
Just like it would be inadvisable to step foot in a laboratory and begin experiments without having a defined endpoint, a deep learning project should not be undertaken without preparation.
Foremost, it is important to assess if a dataset exists that can answer the biological question of interest; obtaining said data and associated metadata and reviewing the study protocol should be pursued as early on in the project as possible.
A publication or resource might purportedly offer data that seems to be a good fit to test your hypothesis, but the act of obtaining the data can reveal numerous problems such as the data is unstructured when it is supposed to be structured, crucial metadata such as sample stratification is missing, or the usable sample size is different than what is reported.
Data collection should be documented or a data collection protocol should be created and specified in the project documentation.
Information such as the resource used, the date downloaded, and the version of the dataset, if any, will help minimize operational confusion and will allow for transparency during the publication process.

Once the data is obtained, it is easy to begin analyzing data without a good understanding of the study design, namely why the data was collected and how.
Metadata has been standardized in many fields and can help with this (for example, see [@YuxbleXb]), but if at all possible, seek out a subject matter expert who has experience with this type of data.
Receiving first-hand knowledge of the “gotchas" of a dataset will minimize the amount of guesswork and increase the success rate of a deep learning project.
For example, if the main reason why the data was collected was to test the impact of an intervention, then it may be the case that a randomized controlled trial was performed.
However, it is not always possible to perform a randomized trial for ethical or practical reasons.
Therefore, an observational study design is often considered, with the data either prospectively or retrospectively collected. 
In order to ensure similar distributions of important characteristics across study groups in the absence of randomization, individuals may be matched based on age, gender, or weight.
Study designs will often have different assumptions and caveats, and these cannot be ignored during a data analysis.
Many datasets are now passively collected or do not have a specific design, but even in this case it is important to know how individuals or samples were treated.
Samples originating from the same study site, oversampling of ethnic groups or zip codes, and sample processing differences are all sources of variation that need to be accounted for.

Systematic biases, which can be induced by confounding variables, for example, can lead to artifacts or so-called "batch effects." 
As a consequence, models may learn to rely on correlations that are irrelevant in the scientific context of the study and may result in misguided predictions and misleading conclusions [@mPnIAH38].
Other study design considerations that should not be overlooked include knowing whether a study involves biological or technical replicates or both.
For example, are some samples collected from the same individuals at different time points? 
Are those time points before and after some treatment? 
If one assumes that all the samples are independent but that is in fact not the case, a variety of issues may arise, including having a lower effective sample size than expected.

In general, deep learning has an increased tendency for overfitting, compared to classical methods, due to the large number of parameters being estimated, making issues of adequate sample size even more important (see [Tip 7](#overfitting)).
For a large dataset, overfitting may not be a concern, but the modeling power of deep learning may lead to more spurious correlations and thus incorrect interpretation of results (see [Tip 9](#interpretation)).
Finally, it is important to note that with the exception of very specific cases of unsupervised data analysis, it is generally the case that a molecular or imaging dataset does not have much value without appropriate clinical or demographic data; this must always be balanced with the need to protect patient privacy (see [Tip 10](#privacy)).
Looking at these data can also clarify the study design (for example, by seeing if all the individuals are adolescents or women) or at least help the analyst employing deep learning to know what questions to ask.


## Tip 5: Choose an appropriate data representation and neural network architecture {#architecture}
Unfortunately, choosing how to represent your data and design your architecture is closer to an art than a science.
While certain best practices have been established by the research community [@JT3rHKc7], architecture design choices remain largely problem-specific and are vastly empirical efforts requiring extensive experimentation.
Furthermore, as deep learning is a quickly evolving field, many recommendations are often short-lived and frequently replaced by newer insights supported by recent empirical results.
This is further complicated by the fact that many recommendations do not generalize well across different problems and datasets.
With that being said, there are some general principles that are useful to follow when experimenting.

First and foremost, use your knowledge of the available data and your question (see [Tip 4](#know-your-problem)) to inform your data representation and architectural design choices.
For example, if your data is an array of measurements with no natural ordering of inputs (such as gene expression data), multilayer perceptrons (MLPs), which are the most basic type of neural network, may be effective.
Similarly, if your data is comprised of images, convolutional neural networks (CNNs) are a good choice because they emphasize local structures and adjacency within the data.
CNNs may also be a good choice for learning on sequences, as recent empirical evidence suggests they can outperform canonical sequence learning techniques such as recurrent neural networks (RNNs) and the closely related long short-term memory (LSTM) networks [arxiv:1803.01271]. 

DL models can typically benefit from large amounts of labeled data to avoid overfitting (see [Tip 7](#overfitting)) and to achieve top performance on a task in hand.
In the event that there is not enough data available to train your model, consider using transfer learning.
In transfer learning, a model whose weights were generated by training on another dataset is used as the starting point for training [@enhj7VT6].
Transfer learning is most useful when pre-training and target datasets are of similar nature [@enhj7VT6].
For this reason, it is important to search for similar data that is already available and may potentially be used to increase the size of the training set or for pre-training and subsequent fine-tuning on the target data.
However, even when this assumption does not hold, transferring features still can improve performance of the model compared to just random feature initialization.
For example Rojkomar et al. showed advantages of ImageNet-pretraining [@cBVeXnZx] for the model that is applied to grayscale medical image classification [@x6HXFAS4].
In addition or as an alternative to pre-training models on larger datasets for transfer learning yourself, you may also be able to obtain pre-trained models from public repositories, such as Kipoi [@14cVrrqP1] for genomics models.
Moreover, learned features can be helpful even when pre-training task was different from the target one [@x7a5SM90].
Related to this property of transfer learning is multi-task learning, in which a network is trained jointly for multiple tasks simultaneously, sharing the same set of features across them.
Multi-task learning can be used separately or in combination with transfer learning [@ZwUaSNWa].


## Tip 6: Expect to tune hyperparameters extensively and systematically {#hyperparameters}

Deep neural networks have the ability to approximate arbitrary continuous functions, as long as the neural network contains enough hidden nodes [@1BnILgle7].
However, this flexibility makes the training process somewhat challenging.
Users should expect to systematically evaluate the impact of numerous hyperparameters when they aim to apply deep neural networks to new data or challenges.

Neural network architectures also have their own odd nuances that affect hyperparameter portability.
For example, in variational autoencoders (VAEs) there are two elements that are being optimized, reconstruction and distribution loss [@NLVTJ9Lj].
In common implementations, the relative weights of each are a function of the number of input features (more increase the importance of reconstruction loss) and the number of features in the latent space (more increase the importance of the distribution loss).
Users who apply a VAE architecture to a new dataset with more input features, even without changing any hyperparameters, alter the relative weights of the components of the loss function.

This flexibility also makes it difficult to evaluate the extent to which neural network methods are well-suited to solving a task.
We discussed how the Continental Breakfast Included effect could affect methods developers seeking to compare techniques in [Tip 2](#baselines).
This effect also has implications for those seeking to use existing deep learning methods because performance estimates from deep neural networks are often provided after tuning.
The implication of this effect on users of deep neural networks is that attaining performance numbers that match those reported in publications is likely to require an input of human and compute time for hyperparameter optimization.


## Tip 7: Address deep neural networks' increased tendency to overfit the dataset {#overfitting}

Overfitting is one of the most significant dangers faced by a deep learning practitioner.
Put simply, overfitting occurs when a model fits patterns in the training data too closely, includes noise or non-scientifically relevant perturbations, or in the most extreme case, simply memorizes patterns in the training set.
This subtle distinction is made clearer by seeing what happens when a model is tested on data to which it was not exposed during training: just as a student who memorizes exam materials struggles to correctly answer questions for which they have not studied, a machine learning model that has overfit to its training data will perform poorly on unseen test data.
Deep learning models are particularly susceptible to overfitting due to their relatively large number of parameters and associated representational capacity.
To continue the student analogy, a smarter student has greater potential for memorization than average one and thus may be more inclined to memorize.

![A visual example of overfitting. While a high-degree polynomial gets high accuracy on its training data, it performs poorly on data that is has not seen before, whereas a simple linear regression works well. The greater representational capacity of the polynomial is analogous to using a larger or deeper neural network.](images/overfitting.png){#fig:overfitting-fig}

The simplest way to combat overfitting is to detect it.
This can be done by splitting the dataset into three parts: a training set, a tuning set (also commonly called a validation set in the machine learning literature), and a test set.
By exposing the model solely to the training data during fitting, a researcher can use the model's performance on the unseen test data to measure the amount of overfitting.
While a slight drop in performance from the training set to the test set is normal, a significant drop is a clear sign of overfitting (see Figure @fig:overfitting-fig for a visual demonstration of an overfit model that performs poorly on test data).
Additionally, there are a variety of techniques to reduce overfitting during training including data augmentation and regularization techniques such as dropout [@R1RpVu06] and weight decay [@eR3C2hhK].
Another way, as described by Chuang and Keiser, is to identify the baseline level of memorization of the network by training on the data with the labels randomly shuffled and to see if the model performs better on the actual data [@yqAEYaMg].
If the model performs no better on real data than randomly scrambled data, then the performance of the model can be attributed to overfitting.

Additionally, one must be sure that their data are not skewed or biased, such as by having confounding and scientifically irrelevant variables that the model can pick up on [@FEPLn1Uo].
In this case, simply holding out test data is insufficient.
The best remedy for confounding variables is to [know your data](#know-your-problem) and to test your model on truly independent data.


## Tip 8: Do not necessarily consider a DL model as a black box {#blackbox}


## Tip 9: Don't over-interpret predictions {#interpretation}

Once we have trained an accurate deep model, we often want to use it to deduce scientific findings.
In doing so, we need to take care to correctly interpret the model's predictions.
We know that the basic tenets of machine learning also apply to deep learning ([Tip 1](#concepts)), but because deep models can be difficult to interpret intuitively, there is a temptation to anthropomorphize the models.
We must resist this temptation.

A common saying in statistics classes is "correlation doesn't imply causality".
While we know that accurately predicting an outcome doesn't imply learning the causal mechanism, it can be easy to forget this lesson when the predictions are extremely accurate.
A poignant example of this lesson is [@980FAm5x; @gSmt16Rh].
In this study, the authors evaluated the capacities of several models to predict the probability of death for patients admitted to an intensive care unit with pneumonia.
Unsurprisingly, the neural network model achieved the best predictive accuracy.
However, after fitting a rule-based model, the authors discovered that the hospital data implied the rule "HasAsthma(x) => LowerRisk(x)".
This rule contradicts medical understanding - having asthma doesn't make pneumonia better!
This rule was supported by the data (pneumonia patients with a history of pneumonia tended to receive more aggressive care), so the neural network also learned to make predictions according to this rule.
Guiding treatment decisions according to the predictions of the neural network would have been disastrous, even though the neural network had high predictive accuracy.

To trust deep learning models, we must combine knowledge of the training data ([Tip 4](#know-your-problem)) with inspection of the model ([Tip 8](#blackbox)).
By probing data domains where the model succeeds and contrasting with domains where the model fails, we can identify the internal logic and deduce scientific conclusions.
In this way, we can move beyond fitting predictive models toward building understanding.


## Tip 10: Don't share models trained on sensitive data {#privacy}

One of the greatest opportunities for deep learning in biology is the ability for deep learning techniques to incorporate representation learning to extract information that can not readily be captured by traditional methods [@UeE0s74F].
The abundance of features for each training example means that the representation learning of the deep learning models can capture information-rich abstractions of data during the training process.
Therefore with both deep learning and traditional machine learning models (_e.g._ _k_-nearest neighbors models, which learn by memorizing the full training data), it is imperative not to share models trained on sensitive data.
Applying deep learning to images of cats from the internet does not pose significant ethical, legal, or privacy problems; this is not the case when dealing with classified, confidential, trade secret, or other types of biological data that cannot be shared.

Techniques to train deep neural networks without sharing unencrypted access to data are being advanced through implementations of homomorphic encryption [@me326jb9; @3326vtLW].
However, adversarial training techniques such as model inversion attacks can be used to exploit model predictions to recover recognizable images of people's faces used for training [@zCqhgXvY].
These risks are more significant in deep learning than traditional machine learning because models have more representational capacity.
The large number of model weights, even in a relatively small network, allow deep learning to model high-dimensional non-linear relationships among features.
Such models can learn more nuanced features of specific data, but these features may be so specific that they may reveal the underlying sensitive data.
When training deep learning models on sensitive data, using privacy preserving techniques [@1HuQe3Z8X], such as differential privacy [@LiCxcgZp; @fbIH12yd; @eJgWbXRz], can help to mitigate risks as long as the assumptions underlying these techniques are met.


## Conclusion {#conclusion}


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

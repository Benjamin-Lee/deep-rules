# Proposed Rules

1. Concepts that apply to machine learning also apply to deep learning ([#37](https://github.com/Benjamin-Lee/deep-rules/issues/37))
  - Garbage In/Garbage Out ([#26](https://github.com/Benjamin-Lee/deep-rules/issues/26))
  - Normalize your data ([#7](https://github.com/Benjamin-Lee/deep-rules/issues/7))
  - Make sure data is not biased/skewed ([#43](https://github.com/Benjamin-Lee/deep-rules/issues/43))
  - How to deal with class imbalance
  - Make it reproducible ([#21](https://github.com/Benjamin-Lee/deep-rules/issues/21))
  - Validate it ([#27](https://github.com/Benjamin-Lee/deep-rules/issues/27))
  - Test/train/validate splitting ([#20](https://github.com/Benjamin-Lee/deep-rules/issues/20), [#19](https://github.com/Benjamin-Lee/deep-rules/issues/19))
  - Test the robustness of your DL model in a simulation framework in which the ground truth is known ([#49](https://github.com/Benjamin-Lee/deep-rules/issues/49))
  - Sanity checks, good coding practices, design and run experiments systematically ([#52](https://github.com/Benjamin-Lee/deep-rules/issues/52), [#35](https://github.com/Benjamin-Lee/deep-rules/issues/35))

2. Use traditional methods to establish performance baselines ([#41](https://github.com/Benjamin-Lee/deep-rules/issues/41), [#11](https://github.com/Benjamin-Lee/deep-rules/issues/11), [#10](https://github.com/Benjamin-Lee/deep-rules/issues/10))

3. Understand the complexities of training deep neural networks
  - Rerun multiple times different initial weight settings (e.g., avg. top 3 out of 5 performance) for fair comparison ([#42](https://github.com/Benjamin-Lee/deep-rules/issues/42))
  - More extensive model selection: architecture as well as hyperparameter search required ([#42](https://github.com/Benjamin-Lee/deep-rules/issues/42))
  - Deep learning really shines on unstructured, not structured data ([#22](https://github.com/Benjamin-Lee/deep-rules/issues/22))

4. Know your data and your question
  - ([#31](https://github.com/Benjamin-Lee/deep-rules/issues/31), [#12](https://github.com/Benjamin-Lee/deep-rules/issues/12), [#13](https://github.com/Benjamin-Lee/deep-rules/issues/13),  [#18](https://github.com/Benjamin-Lee/deep-rules/issues/18))

5. Choose an appropriate neural network architecture and data representation ([#29](https://github.com/Benjamin-Lee/deep-rules/issues/29))
  - A bit of discussion on DL architectures and how they apply to different problems here would be helpful

6. Tune your hyperparameters extensively and systematically ([#42](https://github.com/Benjamin-Lee/deep-rules/issues/42), [#11](https://github.com/Benjamin-Lee/deep-rules/issues/11))
  - Again, discussion on DL specific tuning would be helpful. i.e. layers, dropout, activation functions etc.

7. Address deep neural networks' increased tendency to overfit the dataset ([#28](https://github.com/Benjamin-Lee/deep-rules/issues/28))
  - Emphasize the added dangers of deep models with greater representational capacity with respect to overfitting
  - Some discussion on how not to overfit particularly in the context of DL methods.
  - Overfitting as a symptom of fitting to confounding effects ([#55](https://github.com/Benjamin-Lee/deep-rules/issues/55))

8. Do not necessarily consider a DL model as a black box
  - How to interpret DL models ([#36](https://github.com/Benjamin-Lee/deep-rules/issues/36))
  - Similar to [#6](https://github.com/Benjamin-Lee/deep-rules/issues/6). Check if DL is actually a significant improvement in performance over a more 'interpretable' model ([#25](https://github.com/Benjamin-Lee/deep-rules/issues/25))

9. Interpret predictions in the correct manner
  - How to apply a model ([#30](https://github.com/Benjamin-Lee/deep-rules/issues/30))
  - Correlation != Causation ([#9](https://github.com/Benjamin-Lee/deep-rules/issues/9))
  - Don't overinterpret ([#33](https://github.com/Benjamin-Lee/deep-rules/issues/33))

10. Don't share models trained on sensitive data.
  - Talk about machine learning security and privacy concerns, especially with respect to PII and PHI. ([#4](https://github.com/Benjamin-Lee/deep-rules/issues/4))
  - Emphasize the added dangers of deep models with greater representational capacity with respect to recovering sensitive data

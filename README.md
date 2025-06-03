# New RQ: 


**Idea:** Take automatic evaluation metric pipeline, test it with 2-3 different models for backtranslation, and observe how the evaluation metric score varies as we incorporate translation models ranging from worse to better quality. The goal is to see how the evaluation metric score shifts as model quality improves. This exercise can help us understand how sensitive/robust the eval metric is to the quality of the backtranslation model.

**Intuition:** Hypothesis is that if the metric is sensitive and reliable, we should see a upward trend in eval metric scores as we switch to better backtranslation models. If the scores remain relatively flat or inconsistent or noisy across **models of noticeably different quality** (i.e. poor correlation), it may indicate that the metric lacks sensitivity, raising questions about its reliability!

**Possible RQ:** 
1. How sensitive and robust are automatic evaluation metrics to the quality of backtranslation models used to generate synthetic hypothesis?

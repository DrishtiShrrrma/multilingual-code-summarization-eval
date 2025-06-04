# New RQ: 


**Idea:** Take automatic evaluation metric pipeline, test it with 2-3 different models for backtranslation, and observe how the evaluation metric score varies as we incorporate (back)translation models ranging from worse to better quality. The goal is to see how the evaluation metric score shifts as model quality improves. This exercise can help us understand how sensitive/robust the eval metric is to the quality of the backtranslation model.

**Intuition:** Hypothesis is that if the metric is sensitive and reliable, we should see a upward trend in eval metric scores as we switch to better backtranslation models. If the scores remain relatively flat or inconsistent or noisy across **models of noticeably different quality** (i.e. poor correlation), it may indicate that the metric lacks sensitivity, raising questions about their reliability!

**Possible RQ:** How sensitive and robust are automatic evaluation metrics to the quality of backtranslation models used to generate synthetic hypothesis?



----

# LLM Selection Criteria:

To ensure a fair, relevant, and practically grounded evaluation, we adopted the following criteria when selecting models for this study:
- Model Size Constraint: All models were selected with a size constraint of ≤10B parameters. This keeps the comparison grounded in models that are more accessible and practical for real-world use cases, especially for individual developers, academic researchers, and organizations with modest compute resources, rather than requiring large-scale infrastructure.
- We referred to the BigCode Models Leaderboard (https://huggingface.co/spaces/bigcode/bigcode-models-leaderboard) to guide our selection. This leaderboard evaluates multilingual code models on standardized benchmarks, including HumanEval-Python and a subset of MultiPL-E covering Java, JavaScript, and C++. Code models were prioritized based on their performance and ranking on the aforementioned benchmark tasks, with particular emphasis on their Win Rate, ensuring that we are evaluating strong, latest, state-of-the-art, community-recognized models that support the programming languages of interest to our study. Additionally, we favored models built on inherently multilingual LLM backbones.
- Diversity of Model Families: To ensure the study remains representative and generalizable, we intentionally chose models from distinct architectural families i.e., Qwen, Gemma, and DeepSeek — each of which has shown strong performance. This diversity helps prevent any skewed results that might arise from sticking to a single model lineage. This mix also allows us to explore both inter-family variation and dynamics. However, we did include two models from the Gemma family intentionally i.e. CodeGemma-7B-it (fine-tuned for code tasks) and Gemma-2-9B-it (instruction-tuned for general tasks). While the latter two share the same architectural lineage, we selected Gemma-2-9B-it for its multilingual capabilities and its demonstrated effectiveness across a variety of tasks and languages. This choice was motivated in part by curiosity, as well as the practical opportunity to investigate how a strong multilingual, general-purpose model performs on code-related tasks, i.e. specifically understanding code written in multiple programming languages and generating code summaries in multiple natural languages without any explicit code-specific or natural language-specific fine-tuning.





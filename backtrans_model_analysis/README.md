1. Eval scripts: https://github.com/DrishtiShrrrma/nueva/tree/main/src/eval
2. Eval scores: https://huggingface.co/datasets/DrishtiSharma/all_scores_backtrans
3. Back-translated Summaries: https://github.com/DrishtiShrrrma/nueva/tree/main/backtrans_model_analysis/backtrans_jsons





Note to self: Completed score computations for llamax3-alpaca-8b, aya-expanse-8b, and towerinstruct-13b-v0.1, as well as for m2m and gemmax2. 

computed scores for m2m specifically to establish a lower-bound baseline.  Goal was to figure out if our top-performing models are achieving certain scores, how much weaker models like m2m deviate or say are far off from that range. This variance could help us understand the signal-to-noise ratio of the evaluation metric: does a meaningful gap exist between weak and strong models? If yes, how much?  I wanted to know how much “lift” in scores we’re getting from the better models. And which metrics are more representative and sensitive to these differences and which ones aren’t? 

I was particularly interested in identifying score bands i.e. what scores are typical for a weak model + bad translation , what are typical for a strong one, and how stable these bands are across samples. 

Maybe we can have both coarse- and fine-grained evaluations:
- Coarse-grained: Comparing strong vs. weak models to understand general variance aka score band and the degree of sensitivity.
- Fine-grained: Comparing score differences from top-performing models, particularly through their backtranslations, to see how subtle differences are captured.

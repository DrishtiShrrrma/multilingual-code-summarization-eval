# Gemma-2-9b-it Prompt Evaluation

## Prompt 0:

- **Followed instructions much better than CodeGemma**; behavior is similar to DeepseekCoder. No major formatting issues observed.  
  ➤ Consistently used the same format style across all target language outputs.

- **Japanese** — Contains an incoherent mix (e.g., unexpected Japanese phrase "引数の"):  
  [L33](https://github.com/DrishtiShrrrma/nueva/blob/cd4994b7556e94d67c71d84f55911e5aa6895f34/prompt_analysis/gemma-2-9b-it/prompt0/all_languages_prompt0_combined_gemma-2-9b-it.json#L33)

- **Hindi** — Outputs are valid, but slightly verbose

---

## Prompt 1

- **Followed instructions much better than CodeGemma**; behavior is similar to DeepseekCoder.  
  ➤ No major formatting issues. Format style is consistent across all outputs.

- **Hindi, Arabic** — Slight verbosity observed at times, but not problematic

---

## Prompt 2: 

- **Format Inconsistency** — Some formatting issues across outputs:  
  [L2](https://github.com/DrishtiShrrrma/nueva/blob/cd4994b7556e94d67c71d84f55911e5aa6895f34/prompt_analysis/gemma-2-9b-it/prompt2/all_languages_prompt2_combined_gemma-2-9b-it.json#L2), [L37](https://github.com/DrishtiShrrrma/nueva/blob/cd4994b7556e94d67c71d84f55911e5aa6895f34/prompt_analysis/gemma-2-9b-it/prompt2/all_languages_prompt2_combined_gemma-2-9b-it.json#L37)

- **Hindi, Arabic** — Slight verbosity observed at times, but otherwise sound

---

## Prompt 3: Observations

- **Format Inconsistency** — Uneven structure across some outputs:  
  [L122](https://github.com/DrishtiShrrrma/nueva/blob/cd4994b7556e94d67c71d84f55911e5aa6895f34/prompt_analysis/gemma-2-9b-it/prompt3/all_languages_prompt3_combined_gemma-2-9b-it.json#L122), [L139](https://github.com/DrishtiShrrrma/nueva/blob/cd4994b7556e94d67c71d84f55911e5aa6895f34/prompt_analysis/gemma-2-9b-it/prompt3/all_languages_prompt3_combined_gemma-2-9b-it.json#L139)

- **Hindi, Arabic** — Slight verbosity observed at times, but no major issues

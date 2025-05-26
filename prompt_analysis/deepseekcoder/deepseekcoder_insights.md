# DeepseekCoder Prompt Evaluation

## Prompt 0: Observations

- **Chinese** — Summary generated in English (instead of Chinese) in some/most cases:  
  [L29](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L29), [L46](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L46), [L63](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L63)  
  ✅ Correctly generated in Chinese in some cases: [L148](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L148), [L284](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L284)

- **Hindi** — Summary generated in Indonesian instead of Hindi:  
  [L153](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L153), [L170](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L170), [L187](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L187)

- **Arabic** — Truncated or inconsistent summaries:  
  [L50](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L50), [L33](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L33)

---

## Prompt 1

- **Hindi** — Summary generated in English or Indonesian instead of Hindi (in some/most cases):  
  [L17](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L17), [L34](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L34), [L85](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L85)  
  ✳ Also: [L102 (prompt0)](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L102)  
  ✅ Correctly generated in Hindi: [L102 (prompt1)](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L102)

- **Arabic** — Summary generated in English in some/most cases:  
  [L67](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L67), [L84](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L84)  
  ✅ Correct Arabic summary example: [L101](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L101)

---

## Prompt 2: Consistent Issue

- **All code summaries were generated in English**  
  [L3](https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt2/all_languages_prompt2_combined_deepseek-coder-6.7b-instruct.json#L3)  
  ➤ No multilingual generation observed (at all!)

---

## Prompt 3: Positive Observation

- ✅ **Prompt 3 performed very well**  
  Code summaries were correctly generated in **each target language**

---

## Summary Notes

- DeepseekCoder shows **stronger format consistency** (i.e. using all prompts) and **better adherence to instructions** than CodeGemma
- Main issues observed:
  - **Wrong language substitutions** (e.g., Hindi replaced by Indonesian or English) — seen in prompt 0, 1, and 2
  - **Incomplete or English-only output** in some Arabic and Chinese summaries
- Prompt 3 suggests that multilingual capabilities are fully functional under ideal conditions

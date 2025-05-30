# Qwen2.5Coder Prompt Evaluation

## Prompt 0: 

- **General Format** — Slightly inconsistent formatting across different languages:  
  [L105](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt0/all_languages_prompt0_combined_Qwen2.5-Coder-7B-Instruct.json#L105), [L121](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt0/all_languages_prompt0_combined_Qwen2.5-Coder-7B-Instruct.json#L121)

- **Garbled Text** — Fragments of Chinese leaked into Spanish (e.g., Chinese characters in Spanish or Arabic summaries):  
  [L101](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt0/all_languages_prompt0_combined_Qwen2.5-Coder-7B-Instruct.json#L101), [L116](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt0/all_languages_prompt0_combined_Qwen2.5-Coder-7B-Instruct.json#L116)

---

## Prompt 1:

- ✅ **Format mostly consistent**

- **Hindi** — English summary in place of Hindi (in some/many instances):  
  [L17](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt1/all_languages_prompt1_combined_Qwen2.5-Coder-7B-Instruct.json#L17), [L34](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt1/all_languages_prompt1_combined_Qwen2.5-Coder-7B-Instruct.json#L34), [L102](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt1/all_languages_prompt1_combined_Qwen2.5-Coder-7B-Instruct.json#L102), [L918](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt1/all_languages_prompt1_combined_Qwen2.5-Coder-7B-Instruct.json#L918)  
  ✅ Hindi summaries correctly generated in some cases: [L68](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt1/all_languages_prompt1_combined_Qwen2.5-Coder-7B-Instruct.json#L68), [L85](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt1/all_languages_prompt1_combined_Qwen2.5-Coder-7B-Instruct.json#L85)

- **Garbled Text** — Some summaries contain unintelligible or broken text:  
  [L170](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt1/all_languages_prompt1_combined_Qwen2.5-Coder-7B-Instruct.json#L170)

- **Hindi** — Mediocre Hindi code summary (awkward or incomplete phrasing):  
  [L119](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt1/all_languages_prompt1_combined_Qwen2.5-Coder-7B-Instruct.json#L119)

---

## Prompt 2: 

- **Format mostly consistent**

- **Arabic** — Garbled or mixed-language output in Arabic code summaries:  
  [L67](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt2/all_languages_prompt2_combined_Qwen2.5-Coder-7B-Instruct.json#L67),  
  [L84](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt2/all_languages_prompt2_combined_Qwen2.5-Coder-7B-Instruct.json#L84),  
  [L152](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt2/all_languages_prompt2_combined_Qwen2.5-Coder-7B-Instruct.json#L152),  
  [L169](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt2/all_languages_prompt2_combined_Qwen2.5-Coder-7B-Instruct.json#L169),  
  [L237](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt2/all_languages_prompt2_combined_Qwen2.5-Coder-7B-Instruct.json#L237),  
  [L254](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt2/all_languages_prompt2_combined_Qwen2.5-Coder-7B-Instruct.json#L254),  
  [L271](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt2/all_languages_prompt2_combined_Qwen2.5-Coder-7B-Instruct.json#L271)

---

## Prompt 3: 

- **Format mostly consistent**

- **Garbled Text** — Some unintelligible output:  
  [L67](https://github.com/DrishtiShrrrma/nueva/blob/6e7495c2ba1e66e91c6b867f8526cda93a18a5ca/prompt_analysis/qwen2.5coder/prompt3/all_languages_prompt3_combined_Qwen2.5-Coder-7B-Instruct.json#L67)



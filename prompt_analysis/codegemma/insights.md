# CodeGemma Multilingual Prompt Evaluation

## Prompt 0: Problematic Cases

### Hindi

- Garbled or unclear summary:
  - [Sample 1](https://github.com/DrishtiShrrrma/nueva/blob/e99ddd875d761e187e590fd2779e6cc1ae0c3695/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L16)
  - [Sample 2](https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L64)
  - [Sample 3 (Chinese fragments)](https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L160)

### Arabic

- Mixed script/garbled:
  - [Sample](https://github.com/DrishtiShrrrma/nueva/blob/e99ddd875d761e187e590fd2779e6cc1ae0c3695/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L15)

### Inconsistent Format (Hindi & Arabic)
- [Sample 1](https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L271)
- [Sample 2](https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L272)

---

## Prompt 1

### Arabic
- Summary not generated:
  - [Example 1](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L15)
  - [Example 2](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L191)
- Inconsistent (some correct, e.g. [this](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L207))

### Hindi
- English-only output:
  - [Sample](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L32)

---

## Prompt 2

- Garbled text / awkward phrasing:
  - [Example](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L15)

- Repetition and clarity issues:
  - [Sample 1](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L128)
  - [Sample 2](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L160)

- English summary in place of local language:
  - [Multiple](#) ← you can list or hyperlink here as you've already identified

---

## Prompt 3

### Hindi
- Garbled or mixed-language fragments:
  - [Sample](https://github.com/DrishtiShrrrma/nueva/blob/998304accf83c012a6cd8f0e41aa1465e383080a/prompt_analysis/codegemma/prompt3/all_languages_prompt3_combined_codegemma-7b-it.json#L112)

### Arabic
- Missing summary (English used instead):
  - [Sample](https://github.com/DrishtiShrrrma/nueva/blob/998304accf83c012a6cd8f0e41aa1465e383080a/prompt_analysis/codegemma/prompt3/all_languages_prompt3_combined_codegemma-7b-it.json#L95)

---

## Notes

- Consistency across languages and prompts varies.
- Arabic and Hindi often have formatting or generation issues.
- Some summaries are entirely skipped or replaced by English.

---


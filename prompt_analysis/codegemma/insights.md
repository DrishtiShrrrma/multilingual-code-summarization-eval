# CodeGemma Prompt Evaluation

## Prompt 0: Problematic Cases

### Hindi

- **Broken or malformed structure**  
  [L16](https://github.com/DrishtiShrrrma/nueva/blob/e99ddd875d761e187e590fd2779e6cc1ae0c3695/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L16), [L32](https://github.com/DrishtiShrrrma/nueva/blob/e99ddd875d761e187e590fd2779e6cc1ae0c3695/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L32) — header structure broken (e.g., `## फ़ंक्शन का सारांश:\n\n* **फ़ंक्शन का नाम:`)

- **Slightly garbled or jumbled output**  
  [L64](https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L64) — (ref: TypeError word in the summary)

- **Text corruption with non-Hindi fragments**  
  [L160](https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L160) — includes Chinese/Japanese characters

### Arabic

- **Mixed script / garbled generation**  
  [L15](https://github.com/DrishtiShrrrma/nueva/blob/e99ddd875d761e187e590fd2779e6cc1ae0c3695/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L15) — blends Latin, English, and Arabic characters

### Hindi & Arabic

- **Formatting inconsistency across languages**  
  [L271](https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L271), [L272](https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L272)

---

## Prompt 1: Problematic Cases

### Arabic

- **No Arabic summary generated**  
  [L15](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L15), [L31](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L31), [L191](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L191)

- **Correct Arabic summary in isolated cases**  
  [L207](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L207)

### Hindi

- **English output instead of Hindi**  
  [L32](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L32)

- **Inconsistent format across target languages**  
  [L35](https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L35)

---

## Prompt 2: Problematic Cases

- **Awkward phrasing and garbled words**  
  [L15](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L15) — contains “ibrary” and “mux”

- **Repetitive content**  
  [L48](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L48)

- **Summary mostly in English**  
  [L63](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L63), [L47](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L47), [L79](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L79), [L111](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L111)

- **Verbose, redundant, and unclear summaries**  
  [L128](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L128), [L160](https://github.com/DrishtiShrrrma/nueva/blob/02253119d6dc0ce5b5e22cff76a1088701ebcb04/prompt_analysis/codegemma/prompt2/all_languages_prompt2_combined_codegemma-7b-it.json#L160)

---

## Prompt 3: Generation Failures

### Hindi

- **Multilingual fragments and corruption**  
  [L112](https://github.com/DrishtiShrrrma/nueva/blob/998304accf83c012a6cd8f0e41aa1465e383080a/prompt_analysis/codegemma/prompt3/all_languages_prompt3_combined_codegemma-7b-it.json#L112)

- **Abrupt truncation**  
  [L176](https://github.com/DrishtiShrrrma/nueva/blob/998304accf83c012a6cd8f0e41aa1465e383080a/prompt_analysis/codegemma/prompt3/all_languages_prompt3_combined_codegemma-7b-it.json#L176)

### Arabic

- **Fallback to English instead of Arabic**  
  [L95](https://github.com/DrishtiShrrrma/nueva/blob/998304accf83c012a6cd8f0e41aa1465e383080a/prompt_analysis/codegemma/prompt3/all_languages_prompt3_combined_codegemma-7b-it.json#L95), [L111](https://github.com/DrishtiShrrrma/nueva/blob/998304accf83c012a6cd8f0e41aa1465e383080a/prompt_analysis/codegemma/prompt3/all_languages_prompt3_combined_codegemma-7b-it.json#L111), [L159](https://github.com/DrishtiShrrrma/nueva/blob/998304accf83c012a6cd8f0e41aa1465e383080a/prompt_analysis/codegemma/prompt3/all_languages_prompt3_combined_codegemma-7b-it.json#L159)

- **Correct Arabic summary in some instances**  
  [L128](https://github.com/DrishtiShrrrma/nueva/blob/998304accf83c012a6cd8f0e41aa1465e383080a/prompt_analysis/codegemma/prompt3/all_languages_prompt3_combined_codegemma-7b-it.json#L128)

---

## General Notes

- **Language Quality and Formatting Issues**
  - Arabic and Hindi outputs frequently show garbled syntax, broken/inconsistent formatting, or fallback to English.
  - Output verbosity and repetition vary wildly --- noticed this in Hindi specifically!
  - Some prompts do result in correct summaries for both Hindi and Arabic (but inconsistently) -- Indicates that language support is possible, but unstable/unreliable for the prompts under test.

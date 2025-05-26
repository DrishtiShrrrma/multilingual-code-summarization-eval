
Deepseekcoder: prompt 0: problematic cases:

1. Chinese Summary in English in many instances ---- i ) https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L29 , ii ) https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L46 , iii) https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L63 ---- but it did produce in Chinese itself in a few instances, see: https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L148, iv) https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L284
2. Hindi Summary generated in Indonesian: https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L153, ii) https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L170, iii) https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L187
3. Arabic summaries show truncation or lack fluency/consistency --- https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L50, https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L33
4. Format-wise: mostly consistent output across all langs, followed instructions comparatively well than Codegemma


Deepseekcoder: prompt 1: problematic cases:

1. Hindi Summary generated in English and Indonesian inn some instances: https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L17, https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L34, https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L85 ; indonesian: https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt0/all_languages_prompt0_combined_deepseek-coder-6.7b-instruct.json#L102 ---- but it did produce summary in Hindi in a few cases: https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L102

2. Arabic Summary in English (in some/many instances): https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L67, https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L84, but it did produce Summary in Arabic in a few cases: https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt1/all_languages_prompt1_combined_deepseek-coder-6.7b-instruct.json#L101
3. Format-wise: mostly consistent output across all langs, followed instructions comparatively well than Codegemma


Deepseekcoder: prompt 2: problematic cases:
1. prompt 2 didn't fare well for this particular model: https://github.com/DrishtiShrrrma/nueva/blob/261ab9ace763a10fe107b214e4784e3941fb9e89/prompt_analysis/deepseekcoder/prompt2/all_languages_prompt2_combined_deepseek-coder-6.7b-instruct.json#L3 ---- for all the samples under test ---- code summaries generated were in English!


Deepseekcoder: prompt 3: observations:
1. this one worked really well! generated code summaries in each target lang

5. 

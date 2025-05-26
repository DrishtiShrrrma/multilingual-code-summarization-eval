
codegemma:

1. prompt1 go problematic output: " ## Hindi Code Summary" : sample_68262  ------ prompt 0 did produce output in Arabic, prompt1 just didn't!!

"summary_hindi": "## Hindi Code Summary\n\n**फंक्शन का नाम:** Use\n\n**कुल मिला:** यह फंक्शन एक नया रोटर हेंडलर को हस्तक्षेप में जोड़ता है।\n\n**आरेग़ुमेंट:**\n\n* `h`: यह एक `RouterHandler` प्रकार का मान लेता है।\n\n**मुख्य लॉजिक:**\n\n1. यह फंक्शन `hs.Handlers` नामक एक मैमेंडल स्टैक् में एक नया मान जोड़ता है।\n2. यह मान `h` नामक आरेग़ुमेंट से लेता है।\n3. यह मान `hs.Handlers` में जोड़ा जाता है।\n\n**उदाहरण:**\n\n```go\n// एक नया रोटर हेंडलर बनाना\nmyHandler := MyCustomHandler{}\n\n// हस्तक्षेप में हेंडलर जोड़ना\nhandlers.Use(myHandler)\n```\n\nइसके बाद, जब कोई HTTP अनुरोध मिलता है, तो हस्तक्षेप में जोड़े गए सभी हेंडलर एक-एक करके इसका xửली करते हैं।<eos>"
  },
"summary_arabic": "This function, named `Use`, is part of a stack of handlers, which are responsible for routing requests. It takes a handler of type `RouterHandler` as an argument and adds it to the stack. The handlers are executed in the order they are added, so adding a handler at the beginning of the stack will execute it before any other handlers. The main logic involves appending the new handler to the existing list of handlers.<eos>",

2. 





Codegemma:

prompt 0 --- problematic cases:
hindi: 
1. https://github.com/DrishtiShrrrma/nueva/blob/e99ddd875d761e187e590fd2779e6cc1ae0c3695/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L16, https://github.com/DrishtiShrrrma/nueva/blob/e99ddd875d761e187e590fd2779e6cc1ae0c3695/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L32  --- ## फ़ंक्शन का सारांश:\n\n* **फ़ंक्शन का नाम:**
2. https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L64 --- issues: slightly garbled text ; unclear/jumbled summary (ref:TypeError)
3.  https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L160 --- garbled text --- has fragments of text in Chinese/Japanese) 

arabic: 
1. https://github.com/DrishtiShrrrma/nueva/blob/e99ddd875d761e187e590fd2779e6cc1ae0c3695/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L15 ---- garbled text --- mixed Latin/English/Arabic script

arabic & hindi:
inconsistent format: example https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L271 Vs https://github.com/DrishtiShrrrma/nueva/blob/b6632ef8b04580d9867022e96459e38e534d643b/prompt_analysis/codegemma/prompt0/all_languages_prompt0_combined_codegemma-7b-it.json#L272



Codegemma : prompt 1: problematoc cases:

1. Didn't produce summary in Arabic in many instances: example: 1. https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L15 2. https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L31 3. https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L191   (but did produce summary in Arabic in a few instances! example: https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L207)
2. Even Hindi Summary is compromised at times: https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L32 --- text is generated in English only
3. inconsistent format: see code summary generrated in all the target languages for this partcular sample: https://github.com/DrishtiShrrrma/nueva/blob/bf8a5821ebae6b6f9f15a0ce704ee0b1068cee90/prompt_analysis/codegemma/prompt1/all_languages_prompt1_combined_codegemma-7b-it.json#L35


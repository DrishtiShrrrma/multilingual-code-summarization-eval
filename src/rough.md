def bt_function(text, src_lang_name):
    if bt_model_name == "m2m100":
        return backtranslate_m2m100(text, src_lang_name)
    elif bt_model_name == "llamax":
        return backtranslate_llamax(text, src_lang_name)
    elif bt_model_name == "ayax":
        return backtranslate_ayax(text, src_lang_name)
    elif bt_model_name == "tower":
        return backtranslate_tower(text, src_lang_name)
    elif bt_model_name == "gemmax":
        return backtranslate_gemmax(text, src_lang_name)
    else:
        raise ValueError(f"Unsupported backtranslation model: {bt_model_name}")

# openai 0.4.0

* Add endpoints `create_chat_completion()`, `create_transcription()`, and `create_translation()`
* Downgrade R dependence to 3.5 (see [https://github.com/irudnyts/openai/issues/27](this issue))
* Remove redundant options of `upload_file()`'s argument `purpose`, namely `"search"`, `"answers"`, and `"classifications"`
* Update links in documentation

# openai 0.3.0

* Remove outdated endpoints `create_answer()`, `create_classification()`, and `create_search()`
* Deprecate `retrieve_engine()` and `list_engines()`
* Deprecate `engine_id` argument in `create_completion()`, `create_edit()`, and `create_embedding()`

# openai 0.2.0

* Add new DALL-E functions, namely `create_image()`, `create_image_edit()`, and `create_image_variation()`

* Add the new function `create_moderation()` that checks whether the input violates OpenAI's Content Policy

* Add new model-related functions, namely `list_models()` and `retrieve_model()`

# openai 0.1.0

* Initial version 
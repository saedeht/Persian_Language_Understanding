# Persian_Language_Understanding
![GitHub Repo](https://img.shields.io/badge/Research-Paper-blue)
## 📝 Overview:
<p align="justify">
Dialogue understanding for low-resource languages like Persian remains challenging due to limited annotated data, which constrains supervised training at scale. We propose a simple yet effective training-free method that combines machine translation, retrieval-based example selection, and prompting with a large language model (ChatGPT) to improve zero-shot cross-lingual performance. Given a Persian utterance translated into English, our method retrieves semantically and lexically similar English examples using a hybrid similarity function, translates them back into Persian, and constructs a few-shot prompt tailored to the input. This input-sensitive strategy enhances the informativeness of the examples, helping the model align more effectively with each instance. Experimental results on the Persian-ATIS dataset show that our approach improves intent detection and achieves competitive slot filling performance, outperforming state-of-the-art baselines without requiring any supervision in the target language. The modular pipeline is easy to reproduce and, in future work, can be extended to other low-resource languages, tasks, or retrieval configurations.
</p>

More details will be released upon acceptance...

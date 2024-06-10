# USPTO - Explainable AI for Patent Professionals with [KerasNLP](https://github.com/keras-team/keras-nlp) and [Keras](https://github.com/keras-team/keras)

<div align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/75/Seal_of_the_United_States_Patent_and_Trademark_Office.svg" width="150">
</div>

In this competition, our aim is to enable patent professionals to interpret the results of AI-powered searches in familiar language and syntax through Boolean search queries. These queries, which effectively characterize groups of patents, are well known to patent professionals. Specifically, we need to create a model that will generate binary search queries from a patent and its neighbor $50$ patents, which will return the same set of $50$ neighbor patents when searched in the USPTO database. The problem in this competition can be visually described as below:

<div align="center"><img src="https://github.com/awsaf49/uspto-interpret-patent-search/assets/36858976/63cee6a2-328e-4b20-af74-600993a4124d" width="550"></div>

In thie following notebook, we will demonstrate how to leverage Large Language Models (LLMs) to approach this problem with an iterative comparison method to extract effective queries. Specifically, this notebook uses the **Gemma 1.1 2B** instruction tuned model to perform query extraction from the patents.

> **Note**: You can find the noteboooks on [**Kaggle**](https://www.kaggle.com/code/awsaf49/uspto-kerasnlp-starter) or from here in the `/notebook` folder.

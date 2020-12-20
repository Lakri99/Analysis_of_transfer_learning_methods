# Exploring the limits of transfer learning with text-to-text transformer
Report for Machine learning for NLP seminar offered by Language technology department @ Uds

## Abstract
Transfer learning has become widely popular learning technique in many applications specifically in a natural language processing setting. There can be many ways to transfer the knowledge from one setting to another. In this report, the popular technique of building pre-trained transfer models and its performance of
downstream task is discussed in detail.

This type of transfer learning involves two steps, First is to train a machine learning model on a data rich task. Here, data rich task refers to the task for which
data is easily available such as language modelling where the data can be simply scraped from the web pages which are abundantly available. This model called
the pretrained model captures the low-level details of the task such as semantics or grammar of the language. Second step involves reusing this general-purpose
knowledge gained by fine tuning the pretrained model on specific NLP tasks such as named entity recognition or sentiment classification task.

The paper “Exploring the limits of transfer learning with text-to-text transformer” extends this idea into a text-in, text out model that can be used across many NLP tasks. It also presents a detailed comparative study of different transfer learning techniques and incorporates the best performing methods to present the final model T5 along with the C4 dataset that was used to train it. Together it achieves state of the art performance at the time of its release on many NLP tasks.

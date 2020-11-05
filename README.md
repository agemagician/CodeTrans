<br/>
<h1 align="center">CodeTrans</h1>
<br/>

<br/>

[CodeTrans](https://github.com/agemagician/CodeTrans/) is providing **state of the art pre-trained models for source code**. CodeTrans was trained on **several Nvidia RTX 8000 GPUs** and **couple of Google TPUs** using various **State of the Art Transformers Models**.

Soon you will be able to gave a look at our paper [CodeTrans: cracking the languages of computer’s code through self-supervised deep learning and high performance computing]<!--(https://www.biorxiv.org/content/10.1101/2020.07.12.199554v2)--> for more information about our work.

<br/>
<p align="center">
    <img width="70%" src="https://cdn.pixabay.com/photo/2019/10/02/14/44/head-4521114_960_720.jpg" alt="CodeTrans Attention Visualization">
</p>
<br/>


This repository will be updated regulary with **new pre-trained models for source code** as part of supporting **software engineering** community in general, and **AI research on source code** specifically.

Table of Contents
=================
* [ ⌛️&nbsp; Models Availability](#models)
* [ 🚀&nbsp; Usage ](#usage)
  * [ 🤖&nbsp; Feature Extraction (FE)](#feature-extraction)
  * [ 💥&nbsp; Fine Tuning (FT)](#fine-tuning)
  * [ 🧠&nbsp; Prediction](#prediction)
  * [ ⚗️&nbsp; Source Code Generation ](#protein-generation)
  * [ 🧐&nbsp; Visualization ](#visualization)
  * [ 📈&nbsp; Benchmark ](#benchmark)
* [ 📊&nbsp; Expected Results  ](#results)
  * [ 💻&nbsp; Function Documentation Generation ](#function-documentation-generation)
  * [ 💻&nbsp; Source Code Summarization ](#source-code-summarization)
  * [ 💻&nbsp; Code Comment Generation ](#code-comment-generation)
  * [ 💻&nbsp; Commit Message Generation ](#commit-message-generation)
  * [ 💻&nbsp; API Sequence Recommendation ](#api-sequence-recommendation)
  * [ 💻&nbsp; Programming Language and Synthesis ](#programming-language-and-synthesis)

* [ ❤️&nbsp; Community and Contributions ](#community)
* [ 📫&nbsp; Have a question? ](#question)
* [ 🤝&nbsp; Found a bug? ](#bug)
* [ ✅&nbsp; Requirements ](#requirements)
* [ 🤵&nbsp; Team ](#team)
* [ 💰&nbsp; Sponsors ](#sponsors)
* [ 📘&nbsp; License ](#license)
* [ ✏️&nbsp; Citation ](#citation)

<a name="models"></a>
## ⌛️&nbsp; Models Availability

|          Model              |       Tensorflow      |
| --------------------------- | :-------------------: |
| CodeT5-Small                |     coming soon       |
| CodeT5-Base                 |     coming soon       |
| CodeT5-Large                |     coming soon       |

<a name="usage"></a>
## 🚀&nbsp; Usage  

How to use CodeTrans:

<a name="feature-extraction"></a>
 * <b>🤖&nbsp; Feature Extraction (FE):</b><br/>
 coming soon.

<a name="fine-tuning"></a>
 * <b>💥&nbsp; Fine Tuning (FT):</b><br/>
 coming soon.

<a name="prediction"></a>
 * <b>🧠&nbsp; Prediction:</b><br/>
 Please check:
 [Prediction Section](https://github.com/agemagician/CodeTrans/tree/master/prediction). More information coming soon.
  
<a name="code-generation"></a>
 * <b>⚗️&nbsp; Code Sequences Generation:</b><br/>
 coming soon.
 
<a name="visualization"></a>
* <b>🧐&nbsp; Visualization:</b><br/> 
coming soon.
 
<a name="benchmark"></a>
* <b>📈&nbsp; Benchmark:</b><br/> 
coming soon.

<a name="results"></a>
## 📊&nbsp; Expected Results 

<a name="function-documentation-generation"></a>
 * <b>💻&nbsp; Function Documentation Generation (Bleu):</b><br/>
 
|   Language / Model   |     Python     |      Java      |       Go       |      Php       |      Ruby      |   JavaScript   |
| -------------------- | :------------: | :------------: | :------------: | :------------: | :------------: | :------------: |
|   CodeT5-ST-Small    |      17.31     |     16.65      |     16.89      |     23.05      |      9.19      |      13.7      |
|   CodeT5-ST-Base     |       XX       |       XX       |       XX       |       XX       |       XX       |       XX       |   
|   CodeT5-TF-Small    |   **19.93**    |     19.48      |     18.88      |     25.35      |     13.15      |      17.23     |
|   CodeT5-TF-Base     |       XX       |       XX       |       XX       |       XX       |       XX       |       XX       |
|   CodeT5-TF-Large    |       XX       |       XX       |       XX       |       XX       |       XX       |       XX       |
|   CodeT5-MT-Small    |     19.64      |     19.00      |     19.15      |     24.68      |   **14.91**    |      15.26     |
|   CodeT5-MT-Base     |       XX       |       XX       |       XX       |       XX       |       XX       |       XX       |
|   CodeT5-MT-Large    |       XX       |       XX       |       XX       |       XX       |       XX       |       XX       |
|   CodeT5-MT-TF-Small |     19.77      |   **20.04**    |   **19.36**    |   **25.55**    |     13.70      |    **17.24**   |
|   CodeT5-MT-TF-Base  |       XX       |       XX       |       XX       |       XX       |       XX       |       XX       |
|   CodeT5-MT-TF-Large |       XX       |       XX       |       XX       |       XX       |       XX       |       XX       |
|   State of the art   |     19.06      |     17.65      |     18.07      |     25.16      |     12.16      |      14.90     |
 
<a name="source-code-summarization"></a>
 * <b>💻&nbsp; Source Code Summarization (Bleu):</b><br/>
 
|   Language / Model   |     Python     |       SQL      |       C#       |
| -------------------- | :------------: | :------------: | :------------: |
|   CodeT5-ST-Small    |      8.45      |     17.55      |     19.74      |
|   CodeT5-ST-Base     |       XX       |       XX       |       XX       | 
|   CodeT5-TF-Small    |     10.06      |     17.71      |     20.40      |
|   CodeT5-TF-Base     |       XX       |       XX       |       XX       |
|   CodeT5-TF-Large    |       XX       |       XX       |       XX       |
|   CodeT5-MT-Small    |   **13.11**    |    **19.15**   |    **22.39**   |
|   CodeT5-MT-Base     |       XX       |       XX       |       XX       |
|   CodeT5-MT-Large    |       XX       |       XX       |       XX       |
|   CodeT5-MT-TF-Small |      12.1      |     18.25      |     22.03      |
|   CodeT5-MT-TF-Base  |       XX       |       XX       |       XX       |
|   CodeT5-MT-TF-Large |       XX       |       XX       |       XX       |
|   State of the art   |       XX       |     18.40      |     20.05      |

<a name="code-comment-generation"></a>
 * <b>💻&nbsp; Code Comment Generation (Bleu):</b><br/>
 
|   Language / Model   |      Java      |
| -------------------- | :------------: |
|   CodeT5-ST-Small    |     37.98      |
|   CodeT5-ST-Base     |       XX       |
|   CodeT5-TF-Small    |   **38.56**    |
|   CodeT5-TF-Base     |       XX       |
|   CodeT5-TF-Large    |       XX       |
|   CodeT5-MT-Small    |     20.15      |
|   CodeT5-MT-Base     |       XX       |
|   CodeT5-MT-Large    |       XX       |
|   CodeT5-MT-TF-Small |     38.37      |
|   CodeT5-MT-TF-Base  |       XX       |
|   CodeT5-MT-TF-Large |       XX       |
|   State of the art   |     38.17      |

<a name="commit-message-generation"></a>
 * <b>💻&nbsp; Commit Message Generation (Bleu):</b><br/>
 
|   Language / Model   |      Java      |
| -------------------- | :------------: |
|   CodeT5-ST-Small    |     39.61      |
|   CodeT5-ST-Base     |       XX       |
|   CodeT5-TF-Small    |   **44.216**   |
|   CodeT5-TF-Base     |       XX       |
|   CodeT5-TF-Large    |       XX       |
|   CodeT5-MT-Small    |     36.166     |
|   CodeT5-MT-Base     |       XX       |
|   CodeT5-MT-Large    |       XX       |
|   CodeT5-MT-TF-Small |     43.96      |
|   CodeT5-MT-TF-Base  |       XX       |
|   CodeT5-MT-TF-Large |       XX       |
|   State of the art   |     32.82      |

<a name="api-sequence-recommendation"></a>
 * <b>💻&nbsp; API Sequence Recommendation (Bleu):</b><br/>
 
|   Language / Model   |      Java      |
| -------------------- | :------------: |
|   CodeT5-ST-Small    |     68.709     |
|   CodeT5-ST-Base     |       XX       |
|   CodeT5-TF-Small    |     68.90      |
|   CodeT5-TF-Base     |       XX       |
|   CodeT5-TF-Large    |       XX       |
|   CodeT5-MT-Small    |     58.43      |
|   CodeT5-MT-Base     |       XX       |
|   CodeT5-MT-Large    |       XX       |
|   CodeT5-MT-TF-Small |   **69.29**    |
|   CodeT5-MT-TF-Base  |       XX       |
|   CodeT5-MT-TF-Large |       XX       |
|   State of the art   |     54.42      |

<a name="programming-language-and-synthesis"></a>
 * <b>💻&nbsp; Programming Language and Synthesis (Accuarcy):</b><br/>
 
|   Language / Model   |      English   |
| -------------------- | :------------: |
|   CodeT5-ST-Small    |     89.43      |
|   CodeT5-ST-Base     |       XX       |
|   CodeT5-TF-Small    |     90.30      |
|   CodeT5-TF-Base     |       XX       |
|   CodeT5-TF-Large    |       XX       |
|   CodeT5-MT-Small    |     82.88      |
|   CodeT5-MT-Base     |       XX       |
|   CodeT5-MT-Large    |       XX       |
|   CodeT5-MT-TF-Small |   **90.31**    |
|   CodeT5-MT-TF-Base  |       XX       |
|   CodeT5-MT-TF-Large |       XX       |
|   State of the art   |     85.80      |

<a name="community"></a>
## ❤️&nbsp; Community and Contributions

The CodeTrans project is a **open source project** supported by various partner companies and research institutions. We are committed to **share all our pre-trained models and knowledge**. We are more than happy if you could help us on sharing new ptrained models, fixing bugs, proposing new feature, improving our documentation, spreading the word, or support our project.

<a name="question"></a>
## 📫&nbsp; Have a question?

We are happy to hear your question in our issues page [CodeTrans](https://github.com/agemagician/CodeTrans/issues)! Obviously if you have a private question or want to cooperate with us, you can always **reach out to us directly** via our [RostLab email](mailto:assistant@rostlab.org?subject=[GitHub]CodeTrans) 

<a name="bug"></a>
## 🤝&nbsp; Found a bug?

Feel free to **file a new issue** with a respective title and description on the the [CodeTrans](https://github.com/agemagician/CodeTrans/issues) repository. If you already found a solution to your problem, **we would love to review your pull request**!.

<a name="requirements"></a>
## ✅&nbsp; Requirements

For prediction, [Text to Text](https://github.com/google-research/text-to-text-transfer-transformer) libraray is needed. For source code feature extraction or fine-tuning our pre-trained models, [Pytorch](https://github.com/pytorch/pytorch) and [Transformers](https://github.com/huggingface/transformers) library from huggingface is needed. For model visualization, you need to install [BertViz](https://github.com/jessevig/bertviz) library.

<a name="team"></a>
## 🤵&nbsp; Team

 * <b>Technical University of Munich:</b><br/>
 
| Ahmed Elnaggar       |       Wei Ding  |  Florian Matthes | Burkhard Rost |
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
| <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/ElnaggarAhmend.jpg?raw=true"> | <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/female.png?raw=true"> | <img width=120/ src="https://wwwmatthes.in.tum.de/file/swwvbhnquwxq/Sebis-Public-Website/Team/20140717_7D_%2047488-3-florian-300x300.jpg"> | <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/B.Rost.jpg?raw=true"> |

* <b>Google:</b><br/>

| Llion Jones       |
|:-------------------------:|
| <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/Llion-Jones.jpg?raw=true"> |

* <b>Nvidia:</b><br/>

| Tom Gibbs       | Tamas Feher | Christoph Angerer |
|:-------------------------:|:-------------------------:|:-------------------------:|
| <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/Tom-Gibbs.png?raw=true"> | <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/Tamas-Feher.jpeg?raw=true"> | <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/Christoph-Angerer.jpg?raw=true"> |


<a name="sponsors"></a>
## 💰&nbsp; Sponsors

Nvidia       |      Google  |      Google   | Software Campus
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/agemagician/ProtTrans/blob/master/images/1200px-Nvidia_image_logo.svg.png?raw=true) | ![](https://github.com/agemagician/ProtTrans/blob/master/images/google-cloud-logo.jpg?raw=true) | ![](https://github.com/agemagician/ProtTrans/blob/master/images/tfrc.png?raw=true) | ![](https://github.com/agemagician/ProtTrans/blob/master/images/SOFTWARE_CAMPUS_logo_cmyk.jpg?raw=true)

<a name="license"></a>
## 📘&nbsp; License
The CodeTrans pretrained models are released under the under terms of the [MIT License](LICENSE).

<a name="citation"></a>
## ✏️&nbsp; Citation
If you use this code or our pretrained models for your publication, please cite the original paper:
```
Soon
```

<br/>
<h1 align="center">CodeTrans</h1>
<br/>

<br/>

[CodeTrans](https://github.com/agemagician/CodeTrans/) is providing **state of the art pre-trained models for source code**. CodeTrans was trained on **several Nvidia RTX 8000 GPUs** and **couple of Google TPUs** using various **State of the Art Transformers Models**.

Take a look into our paper [CodeTrans: Towards Cracking the Language of Silicon's Code Through Self-Supervised Deep Learning and High Performance Computing](https://arxiv.org/abs/2104.02443) for more information about our work.

<br/>
<p align="center">
    <img width="70%" src="https://cdn.pixabay.com/photo/2019/10/02/14/44/head-4521114_960_720.jpg" alt="CodeTrans Attention Visualization">
</p>
<br/>


This repository will be updated regulary with **new pre-trained models for source code** as part of supporting **software engineering** community in general, and **Source Code for Covid-19 research** specifically.

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

All CodeTrans original Tensorflow checkpoints are downloadable from this [dropbox folder](https://www.dropbox.com/sh/488bq2of10r4wvw/AABrmE2V8lc8tRqV-qtLu4pUa?dl=0) and the pytorch checkpoints in the [Hugging Face model hub](https://huggingface.co/models?search=code_trans).

You can download all the datasets used in this research from [dropbox folder](https://www.dropbox.com/sh/mzxa2dq30gnot29/AABIf7wPxH5Oe0PZHJ5jPV22a?dl=0).

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
|   CodeTrans-ST-Small    |      17.31     |     16.65      |     16.89      |     23.05      |      9.19      |      13.7      |
|   CodeTrans-ST-Base     |      16.86     |     17.17      |     17.16      |     22.98      |      8.23      |      13.17     |   
|   CodeTrans-TF-Small    |      19.93     |     19.48      |     18.88      |     25.35      |     13.15      |      17.23     |
|   CodeTrans-TF-Base     |      20.26     |     20.19      |     19.50      |     25.84      |     14.07      |      18.25     |
|   CodeTrans-TF-Large    |      20.35     |     20.06      |   **19.54**    |     26.18      |     14.94      |    **18.98**   |
|   CodeTrans-MT-Small    |      19.64     |     19.00      |     19.15      |     24.68      |     14.91      |      15.26     |
|   CodeTrans-MT-Base     |    **20.39**   |     21.22      |     19.43      |   **26.23**    |   **15.26**    |      16.11     |
|   CodeTrans-MT-Large    |      20.18     |   **21.87**    |     19.38      |     26.08      |     15.00      |      16.23     |
|   CodeTrans-MT-TF-Small |      19.77     |     20.04      |     19.36      |     25.55      |     13.70      |      17.24     |
|   CodeTrans-MT-TF-Base  |      19.77     |     21.12      |     18.86      |     25.79      |     14.24      |      18.62     |
|   CodeTrans-MT-TF-Large |      18.94     |     21.42      |     18.77      |     26.20      |     14.19      |      18.83     |
|   State of the art   |      19.06     |     17.65      |     18.07      |     25.16      |     12.16      |      14.90     |
 
<a name="source-code-summarization"></a>
 * <b>💻&nbsp; Source Code Summarization (Bleu):</b><br/>
 
|   Language / Model   |     Python     |       SQL      |       C#       |
| -------------------- | :------------: | :------------: | :------------: |
|   CodeTrans-ST-Small    |      8.45      |     17.55      |     19.74      |
|   CodeTrans-ST-Base     |      9.12      |     15.00      |     18.65      | 
|   CodeTrans-TF-Small    |     10.06      |     17.71      |     20.40      |
|   CodeTrans-TF-Base     |     10.94      |     17.66      |     21.12      |
|   CodeTrans-TF-Large    |     12.41      |     18.40      |     21.43      |
|   CodeTrans-MT-Small    |     13.11      |     19.15      |     22.39      |
|   CodeTrans-MT-Base     |   **13.37**    |     19.24      |     23.20      |
|   CodeTrans-MT-Large    |     13.24      |     19.40      |   **23.57**    |
|   CodeTrans-MT-TF-Small |     12.10      |     18.25      |     22.03      |
|   CodeTrans-MT-TF-Base  |     10.64      |     16.91      |     21.40      |
|   CodeTrans-MT-TF-Large |     12.14      |   **19.98**    |     21.10      |
|   State of the art   |       --       |     18.40      |     20.50      |

<a name="code-comment-generation"></a>
 * <b>💻&nbsp; Code Comment Generation (Bleu):</b><br/>
 
|   Language / Model   |      Java      |
| -------------------- | :------------: |
|   CodeTrans-ST-Small    |     37.98      |
|   CodeTrans-ST-Base     |     38.07      |
|   CodeTrans-TF-Small    |     38.56      |
|   CodeTrans-TF-Base     |     39.06      |
|   CodeTrans-TF-Large    |   **39.50**    |
|   CodeTrans-MT-Small    |     20.15      |
|   CodeTrans-MT-Base     |     27.44      |
|   CodeTrans-MT-Large    |     34.69      |
|   CodeTrans-MT-TF-Small |     38.37      |
|   CodeTrans-MT-TF-Base  |     38.90      |
|   CodeTrans-MT-TF-Large |     39.25      |
|   State of the art   |     38.17      |

<a name="commit-message-generation"></a>
 * <b>💻&nbsp; Commit Message Generation (Bleu):</b><br/>
 
|   Language / Model   |      Java      |
| -------------------- | :------------: |
|   CodeTrans-ST-Small    |     39.61      |
|   CodeTrans-ST-Base     |     38.67      |
|   CodeTrans-TF-Small    |     44.22      |
|   CodeTrans-TF-Base     |     44.17      |
|   CodeTrans-TF-Large    |   **44.41**    |
|   CodeTrans-MT-Small    |     36.17      |
|   CodeTrans-MT-Base     |     39.25      |
|   CodeTrans-MT-Large    |     41.18      |
|   CodeTrans-MT-TF-Small |     43.96      |
|   CodeTrans-MT-TF-Base  |     44.19      |
|   CodeTrans-MT-TF-Large |     44.34      |
|   State of the art   |     32.81      |

<a name="api-sequence-recommendation"></a>
 * <b>💻&nbsp; API Sequence Recommendation (Bleu):</b><br/>
 
|   Language / Model   |      Java      |
| -------------------- | :------------: |
|   CodeTrans-ST-Small    |     68.71      |
|   CodeTrans-ST-Base     |     70.45      |
|   CodeTrans-TF-Small    |     68.90      |
|   CodeTrans-TF-Base     |     72.11      |
|   CodeTrans-TF-Large    |     73.26      |
|   CodeTrans-MT-Small    |     58.43      |
|   CodeTrans-MT-Base     |     67.97      |
|   CodeTrans-MT-Large    |     72.29      |
|   CodeTrans-MT-TF-Small |     69.29      |
|   CodeTrans-MT-TF-Base  |     72.89      |
|   CodeTrans-MT-TF-Large |   **73.39**    |
|   State of the art   |     54.42      |

<a name="programming-language-and-synthesis"></a>
 * <b>💻&nbsp; Programming Language and Synthesis (Accuracy):</b><br/>
 
|   Language / Model   |      LISP      |
| -------------------- | :------------: |
|   CodeTrans-ST-Small    |     89.43      |
|   CodeTrans-ST-Base     |     89.65      |
|   CodeTrans-TF-Small    |     90.30      |
|   CodeTrans-TF-Base     |     90.24      |
|   CodeTrans-TF-Large    |     90.21      |
|   CodeTrans-MT-Small    |     82.88      |
|   CodeTrans-MT-Base     |     86.99      |
|   CodeTrans-MT-Large    |     90.27      |
|   CodeTrans-MT-TF-Small |   **90.31**    |
|   CodeTrans-MT-TF-Base  |     90.30      |
|   CodeTrans-MT-TF-Large |     90.17      |
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
| <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/ElnaggarAhmend.jpg?raw=true"> | <img width=120/ src="https://github.com/matchlesswei/application_project_nlp_company_description/blob/master/image/Wei_Ding.jpg?raw=true"> | <img width=120/ src="https://wwwmatthes.in.tum.de/file/swwvbhnquwxq/Sebis-Public-Website/Team/20140717_7D_%2047488-3-florian-300x300.jpg"> | <img width=120/ src="https://github.com/agemagician/ProtTrans/blob/master/images/B.Rost.jpg?raw=true"> |

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

Google       |      Google  |      Nvidia   | Software Campus
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/agemagician/ProtTrans/blob/master/images/google-cloud-logo.jpg?raw=true) | ![](https://github.com/agemagician/ProtTrans/blob/master/images/tfrc.png?raw=true)  | ![](https://github.com/agemagician/ProtTrans/blob/master/images/1200px-Nvidia_image_logo.svg.png?raw=true)| ![](https://github.com/agemagician/ProtTrans/blob/master/images/SOFTWARE_CAMPUS_logo_cmyk.jpg?raw=true)

<a name="license"></a>
## 📘&nbsp; License
The CodeTrans pretrained models are released under the under terms of the [MIT License](LICENSE).

<a name="citation"></a>
## ✏️&nbsp; Citation
If you use this code or our pretrained models for your publication, please cite the original paper:
```
@misc{elnaggar2021codetrans,
      title={CodeTrans: Towards Cracking the Language of Silicon's Code Through Self-Supervised Deep Learning and High Performance Computing}, 
      author={Ahmed Elnaggar and Wei Ding and Llion Jones and Tom Gibbs and Tamas Feher and Christoph Angerer and Silvia Severini and Florian Matthes and Burkhard Rost},
      year={2021},
      eprint={2104.02443},
      archivePrefix={arXiv},
      primaryClass={cs.SE}
}
```

# K-LLMS
Literature Review and Roadmaps for robust  Knowledge-based LLMs

This is a list of important knowledge-based natural language processing (NLP) papers that discuss the current research in the field. This list is compiled by the collaborators from **University of Notre Dame, and Deloitte**. 

This list is far from complete or objective, and is evolving, as important papers are being published year after year.

A paper doesn't have to be a peer-reviewed conference/journal paper to appear here. We also include tutorial/survey-style papers and blog posts that are often easier to understand than the original papers.


## KG & LLM fusion (pretraining)
* ICLR 2022 - [GREASELM: GRAPH REASONING ENHANCED LANGUAGE MODELS FOR QUESTION ANSWERING](https://arxiv.org/pdf/2201.08860.pdf) 
* NEURIPS 2022 - [Deep Bidirectional Language-Knowledge Graph Pretraining](https://proceedings.neurips.cc/paper_files/paper/2022/file/f224f056694bcfe465c5d84579785761-Supplemental-Conference.pdf) 
  - The difference from GreaseLM is that while GreaseLM only performs finetuning (hence, it is an LM finetuned with KGs), DRAGON performs self-supervised pretraining (hence, it can       be viewed as an LM pretrained + finetuned with KGs). Both of these papers are out of Stanford.

* EMNLP 2023 WORKSHOP - [FLEEK: Factual Error Detection and Correction with Evi Re External edge](https://arxiv.org/pdf/2310.17119.pdf)

## Knowledge-based LLMs
* Lin et al. [RA-DIT: RETRIEVAL-AUGMENTED DUAL INSTRUCTION TUNING](https://arxiv.org/pdf/2310.01352.pdf)
* Kai Sun et al. [Head-to-Tail: How Knowledgeable are Large Language Models (LLM)? A.K.A. Will LLMs Replace Knowledge Graphs?]( https://arxiv.org/pdf/2308.10168.pdf)
  - An evaluation of multiple LLMs to confidently internalize factual knowledge especially for facts of _torso-to-tail_ entities (non popular and still emerging knowledge) which concludes that these set of LLMs are still far from _perfect_. 
* Jiongnan Liu et al. [RETA-LLM: A Retrieval-Augmented Large Language Model Toolkit](https://arxiv.org/abs/2306.05212)
* Ilia Shumailov et al. [THE CURSE OF RECURSION: TRAINING ON GENERATED DATA MAKES MODELS FORGET](https://arxiv.org/pdf/2305.17493.pdf)
* Potsawee Manakul et al. [SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models](https://arxiv.org/abs/2303.08896)
* Chengrun Yang et al.  [Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409)
* Shehzaad Dhuliawala et al. [CHAIN-OF-VERIFICATION REDUCES HALLUCINATION IN LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2309.11495.pdf)
* Sebastian Borgeaud et al. [Improving language models by retrieving from trillions of tokens](https://arxiv.org/pdf/2112.04426.pdf)
* Yike Wu et al. [KG-to-Text Enhanced LLMs Framework for Knowledge Graph Question Answering](https://arxiv.org/abs/2309.11206)
* Yu et al. 2023, [Grounding Language Models to Real-World Environments](https://aclanthology.org/2023.acl-long.270.pdf)
  - Grounding "languate understaning that uses discriminative ability of LMs instea of their generative ability"
* Swamy et al., 2021, [Interpreting Language Models Through Knowledge Graph Extraction](https://openreview.net/pdf?id=PW4AGjla3sx)
  - Generate or drive the creation of KGs from LLMs
* Asai et al., [SELF-RAG: LEARNING TO RETRIEVE, GENERATE, AND CRITIQUE THROUGH SELF-REFLECTION](https://arxiv.org/pdf/2310.11511.pdf)
* Huang et al.,[LARGE LANGUAGE MODELS CANNOT SELF-CORRECT REASONING YET](https://arxiv.org/pdf/2310.01798.pdf)

## Interesting

* Lukas Berglund et al. [The Reversal Curse: LLMs trained on “A is B” fail to learn “B is A](https://arxiv.org/pdf/2309.12288.pdf)
* Encoding clinical knowledge (2023 Nature by Google Research folks)- [Aligning LLMs to new domains](https://www.nature.com/articles/s41586-023-06291-2)
* Using logical reasoning to _guide_ an LM allows for training on certified self-generated reasoning to help avoid halucinaitions. [Certified Reasoning with Language Models](https://arxiv.org/pdf/2306.04031.pdf)  

## Survey Papers

* Shirui Pan et al., 2023, [Unifying Large Language Models and Knowledge Graphs: A Roadmap](https://arxiv.org/abs/2306.08302)
  - Collection of papers and resources about LLMs and KGs. [github repo](https://github.com/RManLuo/Awesome-LLM-KG)   

## Others

* Connor McMahon et al. [The Substantial Interdependence of Wikipedia and Google:  A Case Study on the Relationship Between Peer Production  Communities and Information Technologies](https://ojs.aaai.org/index.php/ICWSM/article/view/14883/14733)

## From the Web

* https://diff.wikimedia.org/2023/07/13/exploring-paths-for-the-future-of-free-knowledge-new-wikipedia-chatgpt-plugin-leveraging-rich-media-social-apps-and-other-experiments/

* [RETRO - JAY ALAMMAR](http://jalammar.github.io/illustrated-retrieval-transformer/)



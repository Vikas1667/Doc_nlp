# Doc_nlp
## Muti model Deep learning

A multimodal architecture is a type of deep learning model 
that incorporates multiple modalities of input data, such as 
images, text, and audio. These models can be used for tasks such as image captioning, visual question answering, 
and speech recognition. Here's an example of a multimodal architecture using Python code:

Multimodal Image-text Classification

https://vaclavkosar.com/ml/Multimodal-Image-Text-Classification

https://towardsdatascience.com/cross-attention-is-what-you-need-fusatnet-fusion-network-b8e6f673491

### PERCEIVER IO
Perceiver IO is a general-purpose multi-modal architecture that can handle wide variety of inputs as well as outputs.
Perceiver can be applied to for example image-text classification. 
Perceiver IO uses cross-attention for merging:

multimodal input sequences (e.g. image, text, audio) into a low dimensional latent sequence
“output query” or “command” to decode the output value e.g. predict this masked word


Advantage of the Perceiver architecture is that in general you can work with very large inputs. 
Architecture Hierarchical Perceiver has ability to process even longer input sequences by splitting into subsequences and then merging them. Hierarchical Perceiver also learns the positional encodings with a separate training step with a reconstruction loss

[pytorch based git repo](https://github.com/krasserm/perceiver-io)

[Jax based git repo](https://github.com/2796gaurav/code_examples/tree/main/Perceiver)

[Jax details repo](https://github.com/google/jax)

### SelfDoc

Self-Supervised Document Representation Learning

### LayoutLM
The LayoutLM model was proposed in the paper 
LayoutLM: Pre-training of Text and Layout for Document Image Understanding by Yiheng Xu, Minghao Li, Lei Cui, 
Shaohan Huang, Furu Wei, and Ming Zhou. It’s a simple but effective pretraining method of text and layout 
for document image understanding and information extraction tasks, 
such as form understanding and receipt understanding.
It obtains state-of-the-art results on several downstream tasks:

form understanding: the [FUNSD](https://guillaumejaume.github.io/FUNSD/) dataset (a collection of 199 annotated forms comprising more than 30,000 words).

receipt understanding: the SROIE dataset (a collection of 626 receipts for training and 347 receipts for testing).

document image classification: the [RVL-CDIP](https://adamharley.com/rvl-cdip/) dataset (a collection of 400,000 images belonging to one of 16 classes).

Release Dataset  
1. [DocBank Dataset](https://doc-analysis.github.io/docbank-page/)
   
2. [TableBank Dataset](https://doc-analysis.github.io/tablebank-page/)

Model and Git Links
1. huggingface v1 [link](https://huggingface.co/docs/transformers/model_doc/layoutlm)

2. huggingface v2 [link](https://huggingface.co/docs/transformers/model_doc/layoutlmv2)

3. LayoutLM github [repo](https://github.com/microsoft/unilm/tree/master/layoutlm/deprecated)


4. DocBank github [repo](https://github.com/doc-analysis/DocBank)

5. TableBank github [repo](https://github.com/doc-analysis/TableBank.)

6. CLIP: Connecting text and images[link](https://openai.com/research/clip)
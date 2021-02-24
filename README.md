<h1 align="center">
<p>DhivehiML :clipboard:</p>
<p align="center">
<a href="https://github.com/TensorSpeech/TensorFlowASR/blob/main/LICENSE">
  <img alt="GitHub" src="https://img.shields.io/github/license/TensorSpeech/TensorFlowASR?logo=apache&logoColor=green">
</a>

</a>
</p>
</h1>
<h2 align="center">
<p>Curating and organizing Dhivehi ML projects and experiments</p>
</h2>

<p align="center">
The goal of this repo is to curate resources related to  Machine Learning and language tools in general aimed for dhivehi, as such any new comer can easily get to an understanding about the current state and use the prebuiilt tools :smile:
</p>

# Current State

### Language models

  [@mapmeid](https://twitter.com/mapmeld) has done some amazing work training and fine tuning langauge models for dhivehi

- [dv-wave](https://huggingface.co/monsoon-nlp/dv-wave):ELECTRA model trained from scratch on dhivehi text
- [dv-muril](https://huggingface.co/monsoon-nlp/dv-muril):Experiment in inserting equivelent dhivehi words to muril
- [dv-labse](https://huggingface.co/monsoon-nlp/dv-labse): Inserting dhivehi wordpeice tokens to Google's LaBSE models

### Text to Speech
Tacotron2 trained on Commonvoice data upto about 300k
[demo](https://github.com/Dharisd/DhivehiML/blob/main/demo/tts/tactoron2/griffinlim/maabageechaa.wav)

- Synthesis audio from Tacotron2 (griffin Lim) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/espnet/notebook/blob/master/espnet2_tts_realtime_demo.ipynb)

Current best model: [Tacotron2 ~300k](https://drive.google.com/drive/folders/18dc75nAVLLI5-Re7yC_7jA4L8aFIIUS3)

### Speech to Text
No work has been done in this area in a way that benefits the publlic

# Notebooks

### Text to speech experiments
- Training Mozilla's tacotron2 implementation with data from Mozilla common voice (griffin Lim) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EMYrjmENBAj9MnNvTrYXL5gQCFld0mJM)
- Also Training Mozilla's tacotron2 implementation with data from Mozilla common voice (griffin Lim) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GETA0FNxF-O1uYTpFB6A77Tapov5NFh6?usp=sharing#scrollTo=LB-zPKpzlXKt)
- Training MultiBand MelGAN on mozilla common voice data(Single Speaker) [~10k model](https://drive.google.com/drive/folders/1-82FugR3oBKAnbx_n2BQnReo3Nr7DLun) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/drive/folders/1-82FugR3oBKAnbx_n2BQnReo3Nr7DLun)
- Process Commonvoice data to LJspeech-1.1 format(Also allows to generate audio only from specified speakers)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YiMHhawvgy3enhwfL0cieAqlKxA900tm#scrollTo=MQdnZb21d41I)



### Speech to text
- [WIP]

### Transliteration
- Training Seq2Seq model to transliterate dhivehi to latin based on [div-transliteration](https://github.com/Sofwath/div-transliteration) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YiMHhawvgy3enhwfL0cieAqlKxA900tm#scrollTo=MQdnZb21d41I)
- Inference for the [div-transliteration](https://github.com/Sofwath/div-transliteration) model [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TFlqhY4isLiHlzo-WKTMtxJUag7Zqm8S)

### Name Entity recognition
- [Spacy NER](https://github.com/Dharisd/dhivehi-ner)

### Datatsets

- [DhivehiDatasets](https://github.com/Sofwath/DhivehiDatasets): Many types of Curated Dhivehi datasets from many sources(News, )
- [Common Voice](https://commonvoice.mozilla.org/dv): Crowd sourced voice dataset
- [opendatamv](https://github.com/opendatamv): Effort to collect various types data by the Open Source community  

### Tasks For Evaluation
*needs to decided and created* 


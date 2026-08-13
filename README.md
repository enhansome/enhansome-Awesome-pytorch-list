# Awesome-Pytorch-list with stars

![pytorch-logo-dark](https://raw.githubusercontent.com/pytorch/pytorch/master/docs/source/_static/img/pytorch-logo-dark.png)

<p align="center">
	<img src="https://img.shields.io/badge/stars-12400+-brightgreen.svg?style=flat"/>
	<img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat">
</p>

## Contents

* [Pytorch & related libraries](#pytorch--related-libraries)
  * [NLP & Speech Processing](#nlp--Speech-Processing)
  * [Computer Vision](#cv)
  * [Probabilistic/Generative Libraries](#probabilisticgenerative-libraries)
  * [Other libraries](#other-libraries)
* [Tutorials, books & examples](#tutorials-books--examples)
* [Paper implementations](#paper-implementations)
* [Talks & Conferences](#talks--conferences)
* [Pytorch elsewhere](#pytorch-elsewhere)

## Pytorch & related libraries

1. [pytorch](http://pytorch.org): Tensors and Dynamic neural networks in Python with strong GPU acceleration.
2. [Captum](https://github.com/pytorch/captum) ⭐ 5,685 | 🐛 66 | 🌐 Python | 📅 2026-08-11: Model interpretability and understanding for PyTorch.

### NLP & Speech Processing:

1. [transformers](https://github.com/huggingface/transformers) ⭐ 164,027 | 🐛 2,378 | 🌐 Python | 📅 2026-08-12: huggingface Transformers: State-of-the-art Natural Language Processing for TensorFlow 2.0 and PyTorch. huggingface.co/transformers
2. [NeMo](https://github.com/NVIDIA/NeMo) ⭐ 18,116 | 🐛 235 | 🌐 Python | 📅 2026-08-13: Neural Modules: a toolkit for conversational AI nvidia.github.io/NeMo
3. [flair](https://github.com/zalandoresearch/flair) ⭐ 14,382 | 🐛 32 | 🌐 Python | 📅 2025-10-27: A very simple framework for state-of-the-art Natural Language Processing (NLP)
4. [AllenNLP](https://github.com/allenai/allennlp) ⚠️ Archived: An open-source NLP research library, built on PyTorch.
5. [speechbrain](https://github.com/speechbrain/speechbrain) ⭐ 11,751 | 🐛 188 | 🌐 Python | 📅 2026-06-15: SpeechBrain is an open-source and all-in-one speech toolkit based on PyTorch.
6. [pyannote-audio](https://github.com/pyannote/pyannote-audio) ⭐ 10,407 | 🐛 34 | 🌐 Jupyter Notebook | 📅 2026-08-04: Neural building blocks for speaker diarization: speech activity detection, speaker change detection, speaker embedding
7. [TTS](https://github.com/mozilla/TTS) ⭐ 10,168 | 🐛 38 | 🌐 Jupyter Notebook | 📅 2023-11-09: Deep learning for Text2Speech
8. [espnet](https://github.com/espnet/espnet) ⭐ 9,920 | 🐛 58 | 🌐 Python | 📅 2026-08-11: End-to-End Speech Processing Toolkit espnet.github.io/espnet
9. [OpenNMT-py](https://github.com/OpenNMT/OpenNMT-py) ⭐ 7,011 | 🐛 23 | 🌐 Python | 📅 2025-10-14: Open-Source Neural Machine Translation in PyTorch <http://opennmt.net>
10. [BERT-PyTorch](https://github.com/codertimo/BERT-pytorch) ⭐ 6,527 | 🐛 68 | 🌐 Python | 📅 2023-09-15: Pytorch implementation of Google AI's 2018 BERT, with simple annotation
11. [pytext](https://github.com/facebookresearch/pytext) ⚠️ Archived: A natural language modeling framework based on PyTorch fb.me/pytextdocs
12. [pythia](https://github.com/facebookresearch/pythia) ⭐ 5,634 | 🐛 150 | 🌐 Python | 📅 2026-07-07: A software suite for Visual Question Answering
13. [LASER](https://github.com/facebookresearch/LASER) ⚠️ Archived: Language-Agnostic SEntence Representations
14. [pytorch text](https://github.com/pytorch/text) ⚠️ Archived: Torch text related contents.
15. [MUSE](https://github.com/facebookresearch/MUSE) ⚠️ Archived: A library for Multilingual Unsupervised or Supervised word Embeddings
16. [audio](https://github.com/pytorch/audio) ⭐ 2,922 | 🐛 338 | 🌐 Python | 📅 2026-08-12: simple audio I/O for pytorch.
17. [neuralcoref](https://github.com/huggingface/neuralcoref) ⭐ 2,893 | 🐛 65 | 🌐 C | 📅 2023-04-13: State-of-the-art coreference resolution based on neural nets and spaCy huggingface.co/coref
18. [pytorch-kaldi](https://github.com/mravanelli/pytorch-kaldi) ⭐ 2,404 | 🐛 26 | 🌐 Python | 📅 2022-03-14: pytorch-kaldi is a project for developing state-of-the-art DNN/RNN hybrid speech recognition systems. The DNN part is managed by pytorch, while feature extraction, label computation, and decoding are performed with the kaldi toolkit.
19. [InferSent](https://github.com/facebookresearch/InferSent) ⚠️ Archived: Sentence embeddings (InferSent) and training code for NLI.
20. [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) ⚠️ Archived: Text utilities and datasets for PyTorch pytorchnlp.readthedocs.io
21. [reformer-pytorch](https://github.com/lucidrains/reformer-pytorch) ⭐ 2,191 | 🐛 17 | 🌐 Python | 📅 2023-06-21: Reformer, the efficient Transformer, in Pytorch
22. [jiant](https://github.com/jsalt18-sentence-repl/jiant) ⭐ 1,674 | 🐛 77 | 🌐 Python | 📅 2023-07-06: The jiant sentence representation learning toolkit.
23. [uis-rnn](https://github.com/google/uis-rnn) ⚠️ Archived:This is the library for the Unbounded Interleaved-State Recurrent Neural Network (UIS-RNN) algorithm, corresponding to the paper Fully Supervised Speaker Diarization. arxiv.org/abs/1810.04719
24. [pytorch-seq2seq](https://github.com/IBM/pytorch-seq2seq) ⚠️ Archived: A framework for sequence-to-sequence (seq2seq) models implemented in PyTorch.
25. [UnsupervisedMT](https://github.com/facebookresearch/UnsupervisedMT) ⚠️ Archived: Phrase-Based & Neural Unsupervised Machine Translation.
26. [BERT-NER](https://github.com/kamalkraj/BERT-NER) ⭐ 1,250 | 🐛 33 | 🌐 Python | 📅 2021-05-06: Pytorch-Named-Entity-Recognition-with-BERT.
27. [voicefilter](https://github.com/mindslab-ai/voicefilter) ⭐ 1,214 | 🐛 13 | 🌐 Python | 📅 2024-07-25: Unofficial PyTorch implementation of Google AI's VoiceFilter system <http://swpark.me/voicefilter>
28. [pytorch-struct](https://github.com/harvardnlp/pytorch-struct) ⭐ 1,133 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2022-04-20: A library of vectorized implementations of core structured prediction algorithms (HMM, Dep Trees, CKY, ..,)
29. [sentiment-discovery](https://github.com/NVIDIA/sentiment-discovery) ⭐ 1,064 | 🐛 48 | 🌐 Python | 📅 2020-06-28: Unsupervised Language Modeling at scale for robust sentiment classification.
30. [pytorch-wavenet](https://github.com/vincentherrmann/pytorch-wavenet) ⭐ 1,029 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2020-09-17: An implementation of WaveNet with fast generation
31. [espresso](https://github.com/freewym/espresso) ⭐ 939 | 🐛 7 | 🌐 Python | 📅 2024-09-04: Espresso: A Fast End-to-End Neural Speech Recognition Toolkit
32. [loop](https://github.com/facebookresearch/loop) ⚠️ Archived: A method to generate speech across multiple speakers
33. [translate](https://github.com/pytorch/translate) ⚠️ Archived: Translate - a PyTorch Language Library.
34. [speech](https://github.com/awni/speech) ⭐ 768 | 🐛 24 | 🌐 Python | 📅 2023-07-06: PyTorch ASR Implementation.
35. [texar-pytorch](https://github.com/asyml/texar-pytorch) ⭐ 746 | 🐛 35 | 🌐 Python | 📅 2022-04-14: Toolkit for Machine Learning and Text Generation, in PyTorch texar.io
36. [nmtpytorch](https://github.com/lium-lst/nmtpytorch) ⚠️ Archived: Neural Machine Translation Framework in PyTorch.
37. [gensen](https://github.com/Maluuba/gensen) ⚠️ Archived: Learning General Purpose Distributed Sentence Representations via Large Scale Multi-task Learning.
38. [transfer-nlp](https://github.com/feedly/transfer-nlp) ⚠️ Archived: NLP library designed for flexible research and development
39. [quick-nlp](https://github.com/outcastofmusic/quick-nlp) ⭐ 283 | 🐛 1 | 🌐 Python | 📅 2018-07-04: Pytorch NLP library based on FastAI.
40. [Backprop](https://github.com/backprop-ai/backprop) ⭐ 240 | 🐛 5 | 🌐 Python | 📅 2021-05-03: Backprop makes it simple to use, finetune, and deploy state-of-the-art ML models.
41. [Tacotron-pytorch](https://github.com/soobinseo/Tacotron-pytorch) ⭐ 206 | 🐛 6 | 🌐 Python | 📅 2018-11-01: Tacotron: Towards End-to-End Speech Synthesis.
42. [torch-metrics](https://github.com/enochkan/torch-metrics) ⭐ 110 | 🐛 5 | 🌐 Python | 📅 2026-07-22: Metrics for model evaluation in pytorch
43. [anuvada](https://github.com/Sandeep42/anuvada) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2018-01-22: Interpretable Models for NLP using PyTorch.
44. [fairseq-py](https://github.com/facebookresearch/fairseq-py): Facebook AI Research Sequence-to-Sequence Toolkit written in Python.

### CV:

1. [detectron2](https://github.com/facebookresearch/detectron2) ⭐ 34,664 | 🐛 586 | 🌐 Python | 📅 2026-07-24: Detectron2 is FAIR's next-generation research platform for object detection and segmentation.
2. [MMDetection](https://github.com/open-mmlab/mmdetection) ⭐ 32,873 | 🐛 1,960 | 🌐 Python | 📅 2024-08-21: MMDetection is an open source object detection toolbox, a part of the [OpenMMLab project](https://open-mmlab.github.io/).
3. [pytorch vision](https://github.com/pytorch/vision) ⭐ 17,860 | 🐛 1,192 | 🌐 Python | 📅 2026-08-12: Datasets, Transforms and Models specific to Computer Vision.
4. [albumentations](https://github.com/albu/albumentations) ⚠️ Archived: Fast image augmentation library.
5. [kornia](https://github.com/arraiyopensource/kornia) ⭐ 11,314 | 🐛 75 | 🌐 Python | 📅 2026-08-11: Differentiable computer vision library.
6. [pytorch3d](https://github.com/facebookresearch/pytorch3d) ⭐ 9,949 | 🐛 316 | 🌐 Python | 📅 2026-07-28: PyTorch3D is FAIR's library of reusable components for deep learning with 3D data pytorch3d.org
7. [MMSegmentation](https://github.com/open-mmlab/mmsegmentation) ⭐ 9,911 | 🐛 867 | 🌐 Python | 📅 2024-08-13: MMSegmentation is a semantic segmentation toolbox and benchmark, a part of the [OpenMMLab project](https://open-mmlab.github.io/).
8. [maskrcnn-benchmark](https://github.com/facebookresearch/maskrcnn-benchmark) ⚠️ Archived: Fast, modular reference implementation of Instance Segmentation and Object Detection algorithms in PyTorch.
9. [MMPose](https://github.com/open-mmlab/mmpose) ⭐ 7,821 | 🐛 332 | 🌐 Python | 📅 2025-08-04: MMPose is a pose estimation toolbox and benchmark, a part of the [OpenMMLab project](https://open-mmlab.github.io/).
10. [face-alignment](https://github.com/1adrianb/face-alignment) ⭐ 7,536 | 🐛 91 | 🌐 Python | 📅 2026-04-06: :fire: 2D and 3D Face alignment library build using pytorch adrianbulat.com
11. [MMEditing](https://github.com/open-mmlab/mmediting) ⭐ 7,453 | 🐛 68 | 🌐 Jupyter Notebook | 📅 2024-08-06: MMEditing is a image and video editing toolbox, a part of the [OpenMMLab project](https://open-mmlab.github.io/).
12. [MMDetection3D](https://github.com/open-mmlab/mmdetection3d) ⭐ 6,501 | 🐛 654 | 🌐 Python | 📅 2024-07-10: MMDetection3D is OpenMMLab's next-generation platform for general 3D object detection, a part of the [OpenMMLab project](https://open-mmlab.github.io/).
13. [facenet-pytorch](https://github.com/timesler/facenet-pytorch) ⭐ 5,160 | 🐛 85 | 🌐 Python | 📅 2025-09-16: Pretrained Pytorch face detection and recognition models ported from davidsandberg/facenet.
14. [Augmentor](https://github.com/mdbloice/Augmentor) ⭐ 5,134 | 🐛 140 | 🌐 Python | 📅 2024-03-21: Image augmentation library in Python for machine learning. <http://augmentor.readthedocs.io>
15. [MMAction2](https://github.com/open-mmlab/mmaction2) ⭐ 5,130 | 🐛 319 | 🌐 Python | 📅 2026-03-18: MMAction2 is OpenMMLab's next generation action understanding toolbox and benchmark, a part of the [OpenMMLab project](https://open-mmlab.github.io/).
16. [lightly](https://github.com/lightly-ai/lightly) ⭐ 3,794 | 🐛 100 | 🌐 Python | 📅 2026-08-12 - Lightly is a computer vision framework for self-supervised learning.
17. [image-classification-mobile](https://github.com/osmr/imgclsmob) ⭐ 3,016 | 🐛 14 | 🌐 Python | 📅 2024-09-06: Collection of classification models pretrained on the ImageNet-1K.
18. [TorchCV](https://github.com/donnyyou/torchcv) ⭐ 2,251 | 🐛 42 | 🌐 Shell | 📅 2020-11-19: A PyTorch-Based Framework for Deep Learning in Computer Vision.
19. [SparseConvNet](https://github.com/facebookresearch/SparseConvNet) ⚠️ Archived: Submanifold sparse convolutional networks.
20. [pytorch-semantic-segmentation](https://github.com/ZijunDeng/pytorch-semantic-segmentation) ⭐ 1,736 | 🐛 48 | 🌐 Python | 📅 2019-10-25: PyTorch for Semantic Segmentation.
21. [ClassyVision](https://github.com/facebookresearch/ClassyVision) ⚠️ Archived: An end-to-end PyTorch framework for image and video classification.
22. [s2cnn](https://github.com/jonas-koehler/s2cnn) ⭐ 972 | 🐛 18 | 🌐 Python | 📅 2024-11-11:
    This library contains a PyTorch implementation of the SO(3) equivariant CNNs for spherical signals (e.g. omnidirectional cameras, signals on the globe)
23. [medicaltorch](https://github.com/perone/medicaltorch) ⭐ 873 | 🐛 17 | 🌐 Python | 📅 2024-04-26: A medical imaging framework for Pytorch <http://medicaltorch.readthedocs.io>
24. [Convolution\_LSTM\_pytorch](https://github.com/automan000/Convolution_LSTM_pytorch) ⚠️ Archived: A multi-layer convolution LSTM module
25. [FlashTorch](https://github.com/MisaOgura/flashtorch) ⭐ 743 | 🐛 10 | 🌐 HTML | 📅 2023-09-21: Visualization toolkit for neural networks in PyTorch!
26. [pytorch-cnn-finetune](https://github.com/creafz/pytorch-cnn-finetune) ⭐ 722 | 🐛 6 | 🌐 Python | 📅 2024-08-16: Fine-tune pretrained Convolutional Neural Networks with PyTorch.
27. [Lucent](https://github.com/greentfrapp/lucent) ⭐ 664 | 🐛 22 | 🌐 Python | 📅 2025-03-21: Tensorflow and OpenAI Clarity's Lucid adapted for PyTorch.
28. [detecto](https://github.com/alankbi/detecto) ⭐ 627 | 🐛 48 | 🌐 Python | 📅 2024-07-25:Computer vision in Python with less than 10 lines of code
29. [detectorch](https://github.com/ignacio-rocco/detectorch) ⭐ 559 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2018-10-30: Detectorch - detectron for PyTorch
30. [RoIAlign.pytorch](https://github.com/longcw/RoIAlign.pytorch) ⭐ 555 | 🐛 39 | 🌐 C++ | 📅 2022-03-01: This is a PyTorch version of RoIAlign. This implementation is based on crop\_and\_resize and supports both forward and backward on CPU and GPU.
31. [vedaseg](https://github.com/Media-Smart/vedaseg) ⭐ 407 | 🐛 7 | 🌐 Python | 📅 2021-11-29: A semantic segmentation framework by pyotrch
32. [img\_classification\_pk\_pytorch](https://github.com/felixgwu/img_classification_pk_pytorch) ⭐ 372 | 🐛 2 | 🌐 Python | 📅 2019-04-12: Quickly comparing your image classification models with the state-of-the-art models (such as DenseNet, ResNet, ...)
33. [OpenFacePytorch](https://github.com/thnkim/OpenFacePytorch) ⭐ 189 | 🐛 5 | 🌐 Python | 📅 2020-02-20:  PyTorch module to use OpenFace's nn4.small2.v1.t7 model
34. [pytorch-text-recognition](https://github.com/s3nh/pytorch-text-recognition) ⭐ 181 | 🐛 3 | 🌐 Python | 📅 2019-09-10: Text recognition combo - CRAFT + CRNN.
35. [neural-dream](https://github.com/ProGamerGov/neural-dream) ⭐ 146 | 🐛 10 | 🌐 Python | 📅 2021-09-29: A PyTorch implementation of the DeepDream algorithm. Creates dream-like hallucinogenic visuals.
36. [pt-styletransfer](https://github.com/tymokvo/pt-styletransfer) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2017-04-03: Neural style transfer as a class in PyTorch.
37. [RoMa](https://naver.github.io/roma/): a lightweight and efficient library to deal with 3D rotations.

### Probabilistic/Generative Libraries:

1. [pyro](https://github.com/uber/pyro) ⭐ 9,037 | 🐛 283 | 🌐 Python | 📅 2026-08-04: Deep universal probabilistic programming with Python and PyTorch <http://pyro.ai>
2. [botorch](https://github.com/pytorch/botorch) ⭐ 3,584 | 🐛 98 | 🌐 Jupyter Notebook | 📅 2026-08-13: Bayesian optimization in PyTorch
3. [probtorch](https://github.com/probtorch/probtorch) ⭐ 892 | 🐛 14 | 🌐 Python | 📅 2024-05-12: Probabilistic Torch is library for deep generative models that extends PyTorch.
4. [pro\_gan\_pytorch](https://github.com/akanimax/pro_gan_pytorch) ⭐ 541 | 🐛 5 | 🌐 Python | 📅 2023-10-03: ProGAN package implemented as an extension of PyTorch nn.Module.
5. [pyvarinf](https://github.com/ctallec/pyvarinf) ⭐ 362 | 🐛 4 | 🌐 Python | 📅 2019-10-12: Python package facilitating the use of Bayesian Deep Learning methods with Variational Inference for PyTorch.
6. [mia](https://github.com/spring-epfl/mia) ⚠️ Archived: A library for running membership inference attacks against ML models.
7. [paysage](https://github.com/drckf/paysage) ⭐ 118 | 🐛 16 | 🌐 Python | 📅 2022-11-21: Unsupervised learning and generative models in python/pytorch.
8. [ptstat](https://github.com/stepelu/ptstat) ⭐ 112 | 🐛 0 | 🌐 Python | 📅 2017-07-04: Probabilistic Programming and Statistical Inference in PyTorch
9. [pyprob](https://github.com/probprog/pyprob) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2020-04-15: A PyTorch-based library for probabilistic programming and inference compilation.

### Other libraries:

1. [ray](https://github.com/ray-project/ray) ⭐ 43,505 | 🐛 3,477 | 🌐 Python | 📅 2026-08-12: A fast and simple framework for building and running distributed applications. Ray is packaged with RLlib, a scalable reinforcement learning library, and Tune, a scalable hyperparameter tuning library. ray.io
2. [pytorch-lightning](https://github.com/williamFalcon/pytorch-lightning) ⭐ 31,288 | 🐛 1,064 | 🌐 Python | 📅 2026-08-09: Rapid research framework for Pytorch. The researcher's version of keras.
3. [fastai](https://github.com/fastai/fastai) ⭐ 28,117 | 🐛 267 | 🌐 Jupyter Notebook | 📅 2026-07-30: The fast.ai deep learning library, lessons, and tutorials
4. [pytorch\_geometric](https://github.com/rusty1s/pytorch_geometric) ⭐ 24,006 | 🐛 1,306 | 🌐 Python | 📅 2026-07-31: Geometric Deep Learning Extension Library for PyTorch
5. [dgl](https://github.com/dmlc/dgl) ⭐ 14,278 | 🐛 608 | 🌐 Python | 📅 2025-07-31: Python package built to ease deep learning on graph, on top of existing DL frameworks. <http://dgl.ai>.
6. [torchgeometry](https://github.com/arraiyopensource/torchgeometry) ⭐ 11,314 | 🐛 75 | 🌐 Python | 📅 2026-08-11: TGM: PyTorch Geometry
7. [accelerate](https://github.com/huggingface/accelerate) ⭐ 9,816 | 🐛 110 | 🌐 Python | 📅 2026-08-10 : A simple way to train and use PyTorch models with multi-GPU, TPU, mixed-precision
8. [pretrained-models.pytorch](https://github.com/Cadene/pretrained-models.pytorch) ⭐ 9,098 | 🐛 109 | 🌐 Python | 📅 2022-04-22: The goal of this repo is to help to reproduce research papers results.
9. [apex](https://github.com/NVIDIA/apex) ⭐ 8,990 | 🐛 770 | 🌐 Python | 📅 2026-08-10: An Experimental PyTorch Extension(will be deprecated at a later point)
10. [EfficientNet PyTorch](https://github.com/lukemelas/EfficientNet-PyTorch) ⭐ 8,222 | 🐛 167 | 🌐 Python | 📅 2022-04-08: It contains an op-for-op PyTorch reimplementation of EfficientNet, along with pre-trained models and examples.
11. [tensorboard-pytorch](https://github.com/lanpa/tensorboard-pytorch) ⭐ 7,996 | 🐛 85 | 🌐 Python | 📅 2026-07-14: This module saves PyTorch tensors in tensorboard format for inspection. Currently supports scalar, image, audio, histogram features in tensorboard.
12. [PyTorch-VAE](https://github.com/AntixK/PyTorch-VAE) ⭐ 7,663 | 🐛 68 | 🌐 Python | 📅 2025-03-21: A Collection of Variational Autoencoders (VAE) in PyTorch.
13. [torchdiffeq](https://github.com/rtqichen/torchdiffeq) ⭐ 6,472 | 🐛 95 | 🌐 Python | 📅 2025-04-04: Differentiable ODE solvers with full GPU support and O(1)-memory backpropagation.
14. [pytorch-metric-learning](https://github.com/KevinMusgrave/pytorch-metric-learning) ⭐ 6,336 | 🐛 77 | 🌐 Python | 📅 2025-08-17: The easiest way to use metric learning in your application. Modular, flexible, and extensible. Written in PyTorch.
15. [inferno-sklearn](https://github.com/dnouri/inferno) ⭐ 6,172 | 🐛 65 | 🌐 Jupyter Notebook | 📅 2026-08-10: A scikit-learn compatible neural network library that wraps pytorch.
16. [skorch](https://github.com/dnouri/skorch) ⭐ 6,172 | 🐛 65 | 🌐 Jupyter Notebook | 📅 2026-08-10: A scikit-learn compatible neural network library that wraps pytorch
17. [kaolin](https://github.com/NVIDIAGameWorks/kaolin) ⭐ 5,157 | 🐛 31 | 🌐 Python | 📅 2026-08-09: PyTorch library aimed at accelerating 3D deep learning research
18. [pytorch-OpCounter](https://github.com/Lyken17/pytorch-OpCounter) ⭐ 5,079 | 🐛 84 | 🌐 Python | 📅 2024-07-08: Count the FLOPs of your PyTorch model.
19. [ignite](https://github.com/pytorch/ignite) ⭐ 4,773 | 🐛 187 | 🌐 Python | 📅 2026-08-01: Ignite is a high-level library to help with training neural networks in PyTorch.
20. [pytorch-summary](https://github.com/sksq96/pytorch-summary) ⭐ 4,054 | 🐛 141 | 🌐 Python | 📅 2024-03-02: Model summary in PyTorch similar to `model.summary()` in Keras
21. [simple-faster-rcnn-pytorch](https://github.com/chenyuntc/simple-faster-rcnn-pytorch) ⭐ 4,032 | 🐛 181 | 🌐 Jupyter Notebook | 📅 2021-05-15: A simplified implemention of Faster R-CNN with competitive performance.
22. [gpytorch](https://github.com/jrg365/gpytorch) ⭐ 3,906 | 🐛 411 | 🌐 Python | 📅 2026-07-10: GPyTorch is a Gaussian Process library, implemented using PyTorch. It is designed for creating flexible and modular Gaussian Process models with ease, so that you don't have to be an expert to use GPs.
23. [gpytorch](https://github.com/cornellius-gp/gpytorch) ⭐ 3,906 | 🐛 411 | 🌐 Python | 📅 2026-07-10: A highly efficient and modular implementation of Gaussian Processes in PyTorch.
24. [pytorchviz](https://github.com/szagoruyko/pytorchviz) ⭐ 3,502 | 🐛 36 | 🌐 Jupyter Notebook | 📅 2024-12-30: A small package to create visualizations of PyTorch execution graphs.
25. [PyTorch-StudioGAN](https://github.com/POSTECH-CVLab/PyTorch-StudioGAN) ⭐ 3,485 | 🐛 40 | 🌐 Python | 📅 2024-08-09: StudioGAN is a Pytorch library providing implementations of representative Generative Adversarial Networks (GANs) for conditional/unconditional image generation. StudioGAN aims to offer an identical playground for modern GANs so that machine learning researchers can readily compare and analyze a new idea.
26. [tensorwatch](https://github.com/microsoft/tensorwatch) ⭐ 3,470 | 🐛 54 | 🌐 Jupyter Notebook | 📅 2026-03-30: Debugging, monitoring and visualization for Deep Learning and Reinforcement Learning from Microsoft Research.
27. [ELF](https://github.com/pytorch/ELF) ⚠️ Archived: ELF: a platform for game research.
28. [Catalyst](https://github.com/catalyst-team/catalyst) ⭐ 3,380 | 🐛 6 | 🌐 Python | 📅 2026-07-08: High-level utils for PyTorch DL & RL research. It was developed with a focus on reproducibility, fast experimentation and code/ideas reusing. Being able to research/develop something new, rather than write another regular train loop.
29. [pytorch-optimizer](https://github.com/jettify/pytorch-optimizer) ⭐ 3,170 | 🐛 57 | 🌐 Python | 📅 2024-03-22: Collections of modern optimization algorithms for PyTorch, includes: AccSGD, AdaBound, AdaMod, DiffGrad, Lamb, RAdam, RAdam, Yogi.
30. [webdataset](https://github.com/tmbdev/webdataset) ⭐ 3,159 | 🐛 140 | 🌐 Python | 📅 2026-02-09: WebDataset is a PyTorch Dataset (IterableDataset) implementation providing efficient access to datasets stored in POSIX tar archives.
31. [spotlight](https://github.com/maciejkula/spotlight) ⭐ 3,044 | 🐛 73 | 🌐 Python | 📅 2022-12-21: Deep recommender models using PyTorch.
32. [Pytorch Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) ⭐ 2,993 | 🐛 30 | 🌐 Python | 📅 2026-05-30: A temporal extension library for PyTorch Geometric
33. [MinkowskiEngine](https://github.com/StanfordVL/MinkowskiEngine) ⭐ 2,953 | 🐛 234 | 🌐 Python | 📅 2024-03-05: Minkowski Engine is an auto-diff library for generalized sparse convolutions and high-dimensional sparse tensors.
34. [AdaBound](https://github.com/Luolc/AdaBound) ⭐ 2,903 | 🐛 19 | 🌐 Python | 📅 2023-07-23: An optimizer that trains as fast as Adam and as good as SGD.a
35. [learn2learn](https://github.com/learnables/learn2learn) ⭐ 2,890 | 🐛 34 | 🌐 Python | 📅 2025-12-16: PyTorch Meta-learning Framework for Researchers <http://learn2learn.net>
36. [PyTorch/XLA](https://github.com/pytorch/xla) ⭐ 2,799 | 🐛 885 | 🌐 C++ | 📅 2026-05-27: PyTorch/XLA is a Python package that uses the XLA deep learning compiler to connect the PyTorch deep learning framework and Cloud TPUs.
37. [Ax](https://github.com/facebook/Ax) ⭐ 2,787 | 🐛 186 | 🌐 Python | 📅 2026-08-13: Adaptive Experimentation Platform
38. [RepDistiller](https://github.com/HobbitLong/RepDistiller) ⭐ 2,437 | 🐛 34 | 🌐 Python | 📅 2023-10-16: Contrastive Representation Distillation (CRD), and benchmark of recent knowledge distillation methods
39. [rlpyt](https://github.com/astooke/rlpyt) ⭐ 2,278 | 🐛 63 | 🌐 Python | 📅 2021-01-04: Reinforcement Learning in PyTorch
40. [cvxpylayers](https://github.com/cvxgrp/cvxpylayers) ⭐ 2,126 | 🐛 23 | 🌐 Python | 📅 2026-05-19: cvxpylayers is a Python library for constructing differentiable convex optimization layers in PyTorch
41. [PyTorch-Encoding](https://github.com/zhanghang1989/PyTorch-Encoding) ⭐ 2,046 | 🐛 151 | 🌐 Python | 📅 2024-12-21: PyTorch Deep Texture Encoding Network <http://hangzh.com/PyTorch-Encoding>
42. [torch-sampling](https://github.com/ncullen93/torchsample) ⭐ 1,880 | 🐛 4 | 🌐 Python | 📅 2024-06-13: This package provides a set of transforms and data structures for sampling from in-memory or out-of-memory data.
43. [Koila](https://github.com/rentruewang/koila) ⭐ 1,826 | 🐛 26 | 🌐 Python | 📅 2026-08-11: A simple wrapper around pytorch that prevents CUDA out of memory issues.
44. [gandissect](https://github.com/CSAILVision/gandissect) ⭐ 1,766 | 🐛 16 | 🌐 Python | 📅 2021-05-23: Pytorch-based tools for visualizing and understanding the neurons of a GAN. gandissect.csail.mit.edu
45. [lightning-flash](https://github.com/PyTorchLightning/lightning-flash) ⚠️ Archived: Flash is a collection of tasks for fast prototyping, baselining and fine-tuning scalable Deep Learning models, built on PyTorch Lightning.
46. [bindsnet](https://github.com/Hananel-Hazan/bindsnet) ⭐ 1,691 | 🐛 15 | 🌐 Python | 📅 2026-08-09: A Python package used for simulating spiking neural networks (SNNs) on CPUs or GPUs using PyTorch
47. [CrypTen](https://github.com/facebookresearch/CrypTen) ⚠️ Archived: CrypTen is a Privacy Preserving Machine Learning framework written using PyTorch that allows researchers and developers to train models using encrypted data. CrypTen currently supports Secure multi-party computation as its encryption mechanism.
48. [higher](https://github.com/facebookresearch/higher) ⚠️ Archived: higher is a pytorch library allowing users to obtain higher order gradients over losses spanning training loops rather than individual training steps.
49. [pytorch-toolbelt](https://github.com/BloodAxe/pytorch-toolbelt) ⭐ 1,575 | 🐛 6 | 🌐 Python | 📅 2025-10-09: PyTorch extensions for fast R\&D prototyping and Kaggle farming
50. [QNNPACK](https://github.com/pytorch/QNNPACK) ⚠️ Archived: Quantized Neural Network PACKage - mobile-optimized implementation of quantized neural network operators.
51. [torchstat](https://github.com/Swall0w/torchstat) ⭐ 1,500 | 🐛 45 | 🌐 Python | 📅 2023-03-19: Model analyzer in PyTorch.
52. [redner](https://github.com/BachiLi/redner) ⭐ 1,444 | 🐛 53 | 🌐 NASL | 📅 2022-08-19: A differentiable Monte Carlo path tracer
53. [hub](https://github.com/pytorch/hub) ⭐ 1,433 | 🐛 56 | 🌐 Python | 📅 2024-04-15: Pytorch Hub is a pre-trained model repository designed to facilitate research reproducibility.
54. [AdverTorch](https://github.com/BorealisAI/advertorch) ⭐ 1,364 | 🐛 27 | 🌐 Jupyter Notebook | 📅 2023-09-14: A Toolbox for Adversarial Robustness (attack/defense/training) Research
55. [SLM-Lab](https://github.com/kengz/SLM-Lab) ⭐ 1,362 | 🐛 5 | 🌐 Python | 📅 2026-06-20: Modular Deep Reinforcement Learning framework in PyTorch.
56. [extension-cpp](https://github.com/pytorch/extension-cpp) ⭐ 1,200 | 🐛 53 | 🌐 Python | 📅 2026-01-13: C++ extensions in PyTorch
57. [geoopt](https://github.com/ferrine/geoopt) ⭐ 1,089 | 🐛 36 | 🌐 Python | 📅 2026-05-09: Riemannian Adaptive Optimization Methods with pytorch optim
58. [mushroom](https://github.com/AIRLab-POLIMI/mushroom) ⭐ 942 | 🐛 4 | 🌐 Python | 📅 2026-08-12: Python library for Reinforcement Learning experiments.
59. [jetson-reinforcement](https://github.com/dusty-nv/jetson-reinforcement) ⭐ 932 | 🐛 30 | 🌐 C++ | 📅 2022-01-27: Deep reinforcement learning libraries for NVIDIA Jetson TX1/TX2 with PyTorch, OpenAI Gym, and Gazebo robotics simulator.
60. [pytorch\_cluster](https://github.com/rusty1s/pytorch_cluster) ⭐ 928 | 🐛 21 | 🌐 C++ | 📅 2026-06-05: PyTorch Extension Library of Optimised Graph Cluster Algorithms.
61. [pytorch-maml-rl](https://github.com/tristandeleu/pytorch-maml-rl) ⭐ 884 | 🐛 29 | 🌐 Python | 📅 2022-12-27: Reinforcement Learning with Model-Agnostic Meta-Learning in Pytorch.
62. [torchgpipe](https://github.com/kakaobrain/torchgpipe) ⭐ 865 | 🐛 9 | 🌐 Python | 📅 2024-07-25: A GPipe implementation in PyTorch torchgpipe.readthedocs.io
63. [pytorch2keras](https://github.com/nerox8664/pytorch2keras) ⭐ 862 | 🐛 62 | 🌐 Python | 📅 2022-12-08: Convert PyTorch dynamic graph to Keras model.
64. [OpenChem](https://github.com/Mariewelt/OpenChem) ⭐ 755 | 🐛 17 | 🌐 Python | 📅 2023-11-26: OpenChem: Deep Learning toolkit for Computational Chemistry and Drug Design Research mariewelt.github.io/OpenChem
65. [torchbeast](https://github.com/facebookresearch/torchbeast) ⚠️ Archived: A PyTorch Platform for Distributed RL
66. [semi-supervised-pytorch](https://github.com/wohlert/semi-supervised-pytorch) ⭐ 709 | 🐛 6 | 🌐 Python | 📅 2020-03-02: Implementations of different VAE-based semi-supervised and generative models in PyTorch.
67. [autonomous-learning-library](https://github.com/cpnota/autonomous-learning-library) ⭐ 656 | 🐛 24 | 🌐 Python | 📅 2024-03-17: A PyTorch library for building deep reinforcement learning agents.
68. [torchbearer](https://github.com/ecs-vlc/torchbearer) ⭐ 641 | 🐛 10 | 🌐 Python | 📅 2023-12-04: torchbearer: A model training library for researchers using PyTorch.
69. [euclidesdb](https://github.com/perone/euclidesdb) ⭐ 639 | 🐛 12 | 🌐 C++ | 📅 2019-12-30: A multi-model machine learning feature embedding database <http://euclidesdb.readthedocs.io>
70. [PyTorch-LBFGS](https://github.com/hjmshi/PyTorch-LBFGS) ⭐ 627 | 🐛 9 | 🌐 Python | 📅 2023-02-21: A PyTorch implementation of L-BFGS.
71. [lightning-transformers](https://github.com/PyTorchLightning/lightning-transformers) ⚠️ Archived:  Flexible interface for high-performance research using SOTA Transformers leveraging Pytorch Lightning, Transformers, and Hydra.
72. [torchprof](https://github.com/awwong1/torchprof) ⚠️ Archived: A minimal dependency library for layer-by-layer profiling of Pytorch models.
73. [colorization-pytorch](https://github.com/richzhang/colorization-pytorch) ⭐ 601 | 🐛 15 | 🌐 Python | 📅 2020-06-04: PyTorch reimplementation of Interactive Deep Colorization richzhang.github.io/ideepcolor
74. [functional zoo](https://github.com/szagoruyko/functional-zoo) ⭐ 584 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2018-02-01: PyTorch, unlike lua torch, has autograd in it's core, so using modular structure of torch.nn modules is not necessary, one can easily allocate needed Variables and write a function that utilizes them, which is sometimes more convenient. This repo contains model definitions in this functional way, with pretrained weights for some models.
75. [pytoune](https://github.com/GRAAL-Research/pytoune) ⭐ 578 | 🐛 9 | 🌐 Python | 📅 2026-06-07: A Keras-like framework and utilities for PyTorch
76. [Poutyne](https://github.com/GRAAL-Research/poutyne) ⭐ 578 | 🐛 9 | 🌐 Python | 📅 2026-06-07: A Keras-like framework for PyTorch that handles much of the boilerplating code needed to train neural networks.
77. [pytorch-dense-correspondence](https://github.com/RobotLocomotion/pytorch-dense-correspondence) ⭐ 576 | 🐛 11 | 🌐 Python | 📅 2023-05-09: Code for "Dense Object Nets: Learning Dense Visual Object Descriptors By and For Robotic Manipulation" arxiv.org/pdf/1806.08756.pdf
78. [torchani](https://github.com/aiqm/torchani) ⭐ 554 | 🐛 8 | 🌐 Python | 📅 2026-07-20: Accurate Neural Network Potential on PyTorch aiqm.github.io/torchani
79. [wavetorch](https://github.com/fancompute/wavetorch) ⭐ 543 | 🐛 3 | 🌐 Python | 📅 2020-02-08: Numerically solving and backpropagating through the wave equation arxiv.org/abs/1904.12831
80. [convert\_torch\_to\_pytorch](https://github.com/clcarwin/convert_torch_to_pytorch) ⭐ 541 | 🐛 28 | 🌐 Python | 📅 2023-07-10: Convert torch t7 model to pytorch model and source.
81. [pro\_gan\_pytorch](https://github.com/akanimax/pro_gan_pytorch) ⭐ 541 | 🐛 5 | 🌐 Python | 📅 2023-10-03: ProGAN package implemented as an extension of PyTorch nn.Module
82. [pytorch2caffe](https://github.com/longcw/pytorch2caffe) ⭐ 538 | 🐛 25 | 🌐 Python | 📅 2019-05-28: Convert PyTorch model to Caffemodel
83. [Arnold](https://github.com/glample/Arnold) ⭐ 534 | 🐛 12 | 🌐 Python | 📅 2022-01-20: Arnold - DOOM Agent
84. [pytorch-cpp-rl](https://github.com/Omegastick/pytorch-cpp-rl) ⚠️ Archived: PyTorch C++ Reinforcement Learning
85. [pixyz](https://github.com/masa-su/pixyz) ⭐ 504 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2025-09-22: a library for developing deep generative models in a more concise, intuitive and extendable way.
86. [matchbox](https://github.com/salesforce/matchbox) ⚠️ Archived: Write PyTorch code at the level of individual examples, then run it efficiently on minibatches.
87. [pytorch-hessian-eigenthings](https://github.com/noahgolmant/pytorch-hessian-eigenthings) ⭐ 474 | 🐛 3 | 🌐 Python | 📅 2026-08-09: Efficient PyTorch Hessian eigendecomposition using the Hessian-vector product and stochastic power iteration.
88. [joint-vae](https://github.com/Schlumberger/joint-vae) ⭐ 470 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2019-04-02: Pytorch implementation of JointVAE, a framework for disentangling continuous and discrete factors of variation star2
89. [Xlearn](https://github.com/thuml/Xlearn) ⭐ 463 | 🐛 21 | 🌐 Jupyter Notebook | 📅 2021-04-09: Transfer Learning Library
90. [Pytorch-Toolbox](https://github.com/PistonY/torch-toolbox) ⭐ 419 | 🐛 4 | 🌐 Python | 📅 2024-05-13: This is toolbox project for Pytorch. Aiming to make you write Pytorch code more easier, readable and concise.
91. [pywick](https://github.com/achaiah/pywick) ⭐ 399 | 🐛 1 | 🌐 Python | 📅 2022-02-04: High-level batteries-included neural network training library for Pytorch
92. [caffemodel2pytorch](https://github.com/vadimkantorov/caffemodel2pytorch) ⭐ 396 | 🐛 10 | 🌐 Python | 📅 2023-03-30: Convert Caffe models to PyTorch.
93. [Pytorch-contrib](https://github.com/pytorch/contrib) ⚠️ Archived: It contains reviewed implementations of ideas from recent machine learning papers.
94. [argus-tensor-stream](https://github.com/Fonbet/argus-tensor-stream) ⭐ 388 | 🐛 7 | 🌐 C++ | 📅 2023-04-27: A library for real-time video stream decoding to CUDA memory tensorstream.argus-ai.com
95. [torch2coreml](https://github.com/prisma-ai/torch2coreml) ⚠️ Archived: Torch7 -> CoreML
96. [lagom](https://github.com/zuoxingdong/lagom) ⭐ 378 | 🐛 16 | 🌐 Jupyter Notebook | 📅 2022-11-19: lagom: A light PyTorch infrastructure to quickly prototype reinforcement learning algorithms.
97. [nonechucks](https://github.com/msamogh/nonechucks) ⭐ 378 | 🐛 20 | 🌐 Python | 📅 2022-09-22: Skip bad items in your PyTorch DataLoader, use Transforms as Filters, and more!
98. [opencv\_transforms](https://github.com/jbohnslav/opencv_transforms) ⭐ 375 | 🐛 7 | 🌐 Python | 📅 2025-08-08: OpenCV implementation of Torchvision's image augmentations
99. [magnet](https://github.com/MagNet-DL/magnet) ⭐ 360 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2019-01-10: Deep Learning Projects that Build Themselves <http://magnet-dl.readthedocs.io/>
100. [salad](https://github.com/domainadaptation/salad) ⭐ 340 | 🐛 32 | 🌐 HTML | 📅 2021-05-15: Semi-Supervised Learning and Domain Adaptation.
101. [sparktorch](https://github.com/dmmiller612/sparktorch) ⭐ 339 | 🐛 16 | 🌐 Python | 📅 2023-05-11: Train and run Pytorch models on Apache Spark.
102. [torchdrift](https://github.com/torchdrift/torchdrift/) ⭐ 327 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2022-08-26: drift detection library
103. [pytorch\_fft](https://github.com/locuslab/pytorch_fft) ⭐ 317 | 🐛 14 | 🌐 Python | 📅 2018-10-28: PyTorch wrapper for FFTs
104. [Renate](https://github.com/awslabs/renate) ⚠️ Archived: A library for real-world continual learning.
105. [volksdep](https://github.com/Media-Smart/volksdep) ⭐ 285 | 🐛 6 | 🌐 Python | 📅 2021-02-05: volksdep is an open-source toolbox for deploying and accelerating PyTorch, Onnx and Tensorflow models with TensorRT.
106. [vel](https://github.com/MillionIntegrals/vel) ⭐ 280 | 🐛 16 | 🌐 Python | 📅 2022-12-08: Velocity in deep-learning research.
107. [pyinn](https://github.com/szagoruyko/pyinn) ⭐ 273 | 🐛 16 | 🌐 Python | 📅 2018-02-15: CuPy fused PyTorch neural networks ops
108. [flambe](https://github.com/asappresearch/flambe) ⭐ 271 | 🐛 22 | 🌐 Python | 📅 2024-09-03: An ML framework to accelerate research and its path to production. flambe.ai
109. [mctorch](https://github.com/mctorch/mctorch) ⭐ 255 | 🐛 10 | 🌐 Python | 📅 2021-08-10: A manifold optimization library for deep learning.
110. [inferno](https://github.com/nasimrahaman/inferno) ⚠️ Archived: A utility library around PyTorch
111. [torch-two-sample](https://github.com/josipd/torch-two-sample) ⭐ 244 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2025-11-12: A PyTorch library for two-sample tests
112. [dni-pytorch](https://github.com/koz4k/dni-pytorch) ⭐ 237 | 🐛 4 | 🌐 Python | 📅 2019-01-12: Decoupled Neural Interfaces using Synthetic Gradients for PyTorch.
113. [PySNN](https://github.com/BasBuller/PySNN) ⭐ 233 | 🐛 4 | 🌐 Python | 📅 2024-07-31: Efficient Spiking Neural Network framework, built on top of PyTorch for GPU acceleration.
114. [pytorch-tools](https://github.com/nearai/pytorch-tools) ⭐ 225 | 🐛 7 | 🌐 Python | 📅 2022-08-10: Tools for PyTorch
115. [delira](https://github.com/justusschock/delira) ⚠️ Archived: Lightweight framework for fast prototyping and training deep neural networks in medical imaging delira.rtfd.io
116. [pydlt](https://github.com/dmarnerides/pydlt) ⭐ 206 | 🐛 0 | 🌐 Python | 📅 2018-07-27: PyTorch based Deep Learning Toolbox
117. [fenchel-young-losses](https://github.com/mblondel/fenchel-young-losses) ⭐ 196 | 🐛 0 | 🌐 Python | 📅 2023-09-19: Probabilistic classification in PyTorch/TensorFlow/scikit-learn with Fenchel-Young losses
118. [beauty-net](https://github.com/cms-flash/beauty-net) ⭐ 191 | 🐛 0 | 🌐 Python | 📅 2023-11-07: A simple, flexible, and extensible template for PyTorch. It's beautiful.
119. [hessian](https://github.com/mariogeiger/hessian) ⭐ 187 | 🐛 0 | 🌐 Python | 📅 2020-10-27: hessian in pytorch.
120. [pywarm](https://github.com/blue-season/pywarm) ⭐ 183 | 🐛 0 | 🌐 Python | 📅 2019-09-23: A cleaner way to build neural networks for PyTorch. blue-season.github.io/pywarm
121. [QuCumber](https://github.com/PIQuIL/QuCumber) ⭐ 178 | 🐛 14 | 🌐 Python | 📅 2026-08-12: Neural Network Many-Body Wavefunction Reconstruction
122. [mpl.pytorch](https://github.com/BelBES/mpl.pytorch) ⭐ 177 | 🐛 4 | 🌐 Python | 📅 2018-06-09: Pytorch implementation of MaxPoolingLoss.
123. [caffe\_to\_torch\_to\_pytorch](https://github.com/fanq15/caffe_to_torch_to_pytorch) ⭐ 150 | 🐛 6 | 🌐 Python | 📅 2017-06-22
124. [Pytorch Geometric Signed Directed](https://github.com/SherylHYX/pytorch_geometric_signed_directed) ⭐ 147 | 🐛 0 | 🌐 Python | 📅 2026-04-15: A signed and directed extension library for PyTorch Geometric.
125. [logger](https://github.com/oval-group/logger) ⭐ 126 | 🐛 1 | 🌐 Python | 📅 2020-11-09: A simple logger for experiments.
126. [pytorch-extension](https://github.com/sniklaus/pytorch-extension) ⭐ 120 | 🐛 0 | 🌐 Python | 📅 2025-05-26: This is a CUDA extension for PyTorch which computes the Hadamard product of two tensors.
127. [NALU](https://github.com/bharathgs/NALU) ⭐ 115 | 🐛 0 | 🌐 Python | 📅 2018-10-03: Basic pytorch implementation of NAC/NALU from Neural Arithmetic Logic Units paper by trask et.al arxiv.org/pdf/1808.00508.pdf
128. [Torchelie](https://github.com/Vermeille/Torchelie/) ⭐ 111 | 🐛 24 | 🌐 Python | 📅 2026-07-20: Torchélie is a set of utility functions, layers, losses, models, trainers and other things for PyTorch. torchelie.readthedocs.org
129. [macarico](https://github.com/hal3/macarico) ⭐ 110 | 🐛 19 | 🌐 Python | 📅 2020-02-18: learning to search in pytorch
130. [pytorch-fitmodule](https://github.com/henryre/pytorch-fitmodule) ⚠️ Archived: Super simple fit method for PyTorch modules
131. [pytorch-mcn](https://github.com/albanie/pytorch-mcn) ⭐ 95 | 🐛 3 | 🌐 Python | 📅 2019-01-06: Convert models from MatConvNet to PyTorch
132. [cogitare](https://github.com/cogitare-ai/cogitare) ⚠️ Archived: Cogitare - A Modern, Fast, and Modular Deep Learning and Machine Learning framework in Python.
133. [candlegp](https://github.com/t-vi/candlegp) ⭐ 76 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-02-26: Gaussian Processes in Pytorch.
134. [torchcraft-py](https://github.com/deepcraft/torchcraft-py) ⚠️ Archived: Python wrapper for TorchCraft, a bridge between Torch and StarCraft for AI research.
135. [osqpth](https://github.com/oxfordcontrol/osqpth) ⭐ 67 | 🐛 8 | 🌐 Python | 📅 2022-12-26: The differentiable OSQP solver layer for PyTorch.
136. [aorun](https://github.com/ramon-oliveira/aorun) ⭐ 62 | 🐛 0 | 🌐 Python | 📅 2017-09-06: Aorun intend to be a Keras with PyTorch as backend.
137. [diffdist](https://github.com/ag14774/diffdist) ⭐ 62 | 🐛 1 | 🌐 Python | 📅 2020-06-18: diffdist is a python library for pytorch. It extends the default functionality of torch.autograd and adds support for differentiable communication between processes.
138. [Tor10](https://github.com/kaihsin/Tor10) ⭐ 59 | 🐛 1 | 🌐 Python | 📅 2019-06-21: A Generic Tensor-Network library that is designed for quantum simulation, base on the pytorch.
139. [Tor10](https://github.com/kaihsin/Tor10) ⭐ 59 | 🐛 1 | 🌐 Python | 📅 2019-06-21: A Generic Tensor-Network library that is designed for quantum simulation, base on the pytorch.
140. [generative\_zoo](https://github.com/DL-IT/generative_zoo) ⭐ 54 | 🐛 2 | 🌐 Python | 📅 2018-12-19: generative\_zoo is a repository that provides working implementations of some generative models in PyTorch.
141. [dpwa](https://github.com/loudinthecloud/dpwa) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2017-10-31: Distributed Learning by Pair-Wise Averaging.
142. [pytorch extras](https://github.com/mrdrozdov/pytorch-extras) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2017-03-13: Some extra features for pytorch.
143. [pytorch-ctc](https://github.com/ryanleary/pytorch-ctc) ⭐ 42 | 🐛 0 | 🌐 C++ | 📅 2018-01-31: PyTorch-CTC is an implementation of CTC (Connectionist Temporal Classification) beam search decoding for PyTorch. C++ code borrowed liberally from TensorFlow with some improvements to increase flexibility.
144. [netharn](https://github.com/Erotemic/netharn) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2020-10-23: Parameterized fit and prediction harnesses for pytorch.
145. [sru](https://github.com/taolei87/sru) ⭐ 38 | 🐛 1 | 📅 2021-09-28: Training RNNs as Fast as CNNs (arxiv.org/abs/1709.02755)
146. [PyTorch-docset](https://github.com/iamaziz/PyTorch-docset) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2017-08-15: PyTorch docset! use with Dash, Zeal, Velocity, or LovelyDocs.
147. [Torchlite](https://github.com/EKami/Torchlite) ⭐ 31 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2022-09-29: A high level library on top of(not only) Pytorch
148. [neural-assembly-compiler](https://github.com/aditya-khant/neural-assembly-compiler) ⭐ 27 | 🐛 0 | 🌐 Haskell | 📅 2018-03-27: A neural assembly compiler for pyTorch based on adaptive-neural-compilation.
149. [pytorch-cns](https://github.com/awentzonline/pytorch-cns) ⭐ 26 | 🐛 3 | 🌐 Python | 📅 2017-11-01: Compressed Network Search with PyTorch
150. [torchplus](https://github.com/knighton/torchplus) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2019-04-11: Implements the + operator on PyTorch modules, returning sequences.
151. [ANEE](https://github.com/abkmystery/ANEE) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-11-30 – Adaptive Neural Execution Engine for PyTorch transformers. Provides per-token dynamic layer skipping, profiler-based gating, and KV-cache-safe sparse inference.
152. [pytorch-caffe-darknet-convert](https://github.com/marvis/pytorch-caffe-darknet-convert): convert between pytorch, caffe prototxt/weights and darknet cfg/weights
153. [scVI-dev](https://github.com/YosefLab/scVI-dev): Development branch of the scVI project in PyTorch
154. [vegans](https://github.com/unit8co/vegans): A library providing various existing GANs in PyTorch.
155. [Flower](https://flower.dev/) A unified approach to federated learning, analytics, and evaluation. It allows to federated any machine learning workload.

## Tutorials, books, & examples

1. [LabML NN](https://github.com/lab-ml/nn) ⭐ 67,320 | 🐛 34 | 🌐 Python | 📅 2026-01-22: A collection of PyTorch implementations of neural networks architectures and algorithms with side-by-side notes.
2. [pytorch-image-models](https://github.com/rwightman/pytorch-image-models) ⭐ 37,063 | 🐛 61 | 🌐 Python | 📅 2026-08-11: PyTorch image models, scripts, pretrained weights -- (SE)ResNet/ResNeXT, DPN, EfficientNet, MobileNet-V3/V2/V1, MNASNet, Single-Path NAS, FBNet, and more.
3. [pytorch-tutorial](https://github.com/yunjey/pytorch-tutorial) ⭐ 32,450 | 🐛 90 | 🌐 Python | 📅 2023-08-15: tutorial for researchers to learn deep learning with pytorch.
4. [pytorch examples](https://github.com/pytorch/examples) ⭐ 24,004 | 🐛 251 | 🌐 Python | 📅 2025-09-01:  A repository showcasing examples of using pytorch
5. [pytorch tutorials](https://github.com/pytorch/tutorials) ⭐ 9,279 | 🐛 255 | 🌐 Python | 📅 2026-07-31: Various pytorch tutorials.
6. **[PyTorch-Tutorial](https://github.com/MorvanZhou/PyTorch-Tutorial) ⭐ 8,465 | 🐛 29 | 🌐 Jupyter Notebook | 📅 2023-03-23**: Build your neural network easy and fast  <https://morvanzhou.github.io/tutorials/>
7. [Run your PyTorch Example Fedarated with Flower](https://github.com/adap/flower/tree/main/examples/pytorch_from_centralized_to_federated) ⭐ 7,070 | 🐛 378 | 🌐 Python | 📅 2026-08-13: This example demonstrates how an already existing centralized PyTorch machine learning project can be federated with Flower. A Cifar-10 dataset is used together with a convolutional neural network (CNN).
8. [PyTorch-Deep-Learning-Minicourse](https://github.com/Atcold/PyTorch-Deep-Learning-Minicourse) ⭐ 6,809 | 🐛 62 | 🌐 Jupyter Notebook | 📅 2025-06-16: Minicourse in Deep Learning with PyTorch.
9. [pytorch-sentiment-analysis](https://github.com/bentrevett/pytorch-sentiment-analysis) ⭐ 4,612 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2024-03-27: Tutorials on getting started with PyTorch and TorchText for sentiment analysis.
10. **[Practical Pytorch](https://github.com/spro/practical-pytorch) ⚠️ Archived**: Tutorials explaining different RNN models
11. [d2l-pytorch](https://github.com/dsgiitr/d2l-pytorch) ⭐ 4,361 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2024-07-25: This is an attempt to modify Dive into Deep Learning, Berkeley STAT 157 (Spring 2019) textbook's code into PyTorch.
12. [RL-Adventure-2](https://github.com/higgsfield/RL-Adventure-2) ⭐ 4,060 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2024-05-25: PyTorch4 tutorial of: actor critic / proximal policy optimization / acer / ddpg / twin dueling ddpg / soft actor critic / generative adversarial imitation learning / hindsight experience replay
13. [RL-Adventure](https://github.com/higgsfield/RL-Adventure) ⭐ 3,178 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2021-11-04: Pytorch easy-to-follow step-by-step Deep Q Learning tutorial with clean readable code.
14. [DeepNLP-models-Pytorch](https://github.com/DSKSD/DeepNLP-models-Pytorch) ⭐ 2,944 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2019-10-15 Pytorch implementations of various Deep NLP models in cs-224n(Stanford Univ: NLP with Deep Learning)
15. [code-of-learn-deep-learning-with-pytorch](https://github.com/SherlockLiao/code-of-learn-deep-learning-with-pytorch) ⭐ 2,874 | 🐛 26 | 🌐 Jupyter Notebook | 📅 2024-03-04: This is code of book "Learn Deep Learning with PyTorch" item.jd.com/17915495606.html
16. [pytorch-cpp](https://github.com/prabhuomkar/pytorch-cpp) ⭐ 2,137 | 🐛 3 | 🌐 C++ | 📅 2025-08-25: C++ implementations of PyTorch tutorials for deep learning researchers (based on the Python tutorials from [pytorch-tutorial](https://github.com/yunjey/pytorch-tutorial) ⭐ 32,450 | 🐛 90 | 🌐 Python | 📅 2023-08-15).
17. [pytorch-classification](https://github.com/bearpaw/pytorch-classification) ⭐ 1,738 | 🐛 34 | 🌐 Python | 📅 2024-06-18: A unified framework for the image classification task on CIFAR-10/100 and ImageNet.
18. [grokking-pytorch](https://github.com/Kaixhin/grokking-pytorch) ⭐ 1,198 | 🐛 0 | 📅 2021-09-13: The Hitchiker's Guide to PyTorch
19. [Mila introductory tutorials](https://github.com/mila-udem/welcome_tutorials) ⭐ 984 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-06-27: Various tutorials given for welcoming new students at MILA.
20. [pytorch-custom-dataset-examples](https://github.com/utkuozbulak/pytorch-custom-dataset-examples) ⭐ 874 | 🐛 0 | 🌐 Python | 📅 2020-04-08: Some custom dataset examples for PyTorch
21. [Capsule-Network-Tutorial](https://github.com/higgsfield/Capsule-Network-Tutorial) ⭐ 765 | 🐛 14 | 🌐 Jupyter Notebook | 📅 2019-10-04: Pytorch easy-to-follow Capsule Network tutorial.
22. [CIFAR-ZOO](https://github.com/BIGBALLON/CIFAR-ZOO) ⭐ 707 | 🐛 0 | 🌐 Python | 📅 2021-02-20: Pytorch implementation for multiple CNN architectures and improve methods with state-of-the-art results.
23. [minimal-seq2seq](https://github.com/keon/seq2seq) ⭐ 706 | 🐛 0 | 🌐 Python | 📅 2026-05-18: Minimal Seq2Seq model with Attention for Neural Machine Translation in PyTorch
24. [pytorch-for-numpy-users](https://github.com/wkentaro/pytorch-for-numpy-users) ⭐ 706 | 🐛 0 | 🌐 HTML | 📅 2023-02-05
25. [torch\_light](https://github.com/ne7ermore/torch_light) ⭐ 537 | 🐛 10 | 🌐 Python | 📅 2020-11-20: Tutorials and examples include Reinforcement Training, NLP, CV
26. [cifar10-fast](https://github.com/davidcpage/cifar10-fast) ⭐ 537 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2021-12-30:
    Demonstration of training a small ResNet on CIFAR10 to 94% test accuracy in 79 seconds as described in this [blog series](https://www.myrtle.ai/2018/09/24/how_to_train_your_resnet/).
27. [T-SNE in pytorch](https://github.com/cemoody/topicsne) ⭐ 480 | 🐛 5 | 🌐 Python | 📅 2022-11-05: t-SNE experiments in pytorch
28. [tensorly-notebooks](https://github.com/JeanKossaifi/tensorly-notebooks) ⭐ 449 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-02-13: Tensor methods in Python with TensorLy tensorly.github.io/dev
29. [NER-BERT-pytorch](https://github.com/lemonhu/NER-BERT-pytorch) ⭐ 446 | 🐛 19 | 🌐 Python | 📅 2023-03-30: PyTorch solution of named entity recognition task Using Google AI's pre-trained BERT model.
30. [video-caption-pytorch](https://github.com/xiadingZ/video-caption-pytorch) ⭐ 400 | 🐛 25 | 🌐 Python | 📅 2019-08-19: pytorch code for video captioning.
31. [thinking-in-tensors-writing-in-pytorch](https://github.com/stared/thinking-in-tensors-writing-in-pytorch) ⭐ 395 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-01-10: Thinking in tensors, writing in PyTorch (a hands-on deep learning intro).
32. [pytorch\_notebooks - hardmaru](https://github.com/hardmaru/pytorch_notebooks) ⭐ 393 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2018-04-05: Random tutorials created in NumPy and PyTorch.
33. [Kind\_PyTorch\_Tutorial](https://github.com/GunhoChoi/Kind_PyTorch_Tutorial) ⭐ 390 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2017-06-08: Kind PyTorch Tutorial for beginners.
34. [SentimentAnalysis](https://github.com/barissayil/SentimentAnalysis) ⭐ 378 | 🐛 2 | 🌐 Python | 📅 2023-06-12: Sentiment analysis neural network trained by fine tuning BERT on the Stanford Sentiment Treebank, thanks to [Hugging Face](https://huggingface.co/transformers/)'s Transformers library.
35. [convnet](https://github.com/eladhoffer/convNet.pytorch) ⭐ 347 | 🐛 11 | 🌐 Python | 📅 2021-02-04: This is a complete training example for Deep Convolutional Networks on various datasets (ImageNet, Cifar10, Cifar100, MNIST).
36. [pytorch mini tutorials](https://github.com/vinhkhuc/PyTorch-Mini-Tutorials) ⭐ 330 | 🐛 4 | 🌐 Python | 📅 2020-09-16:  Minimal tutorials for PyTorch adapted from Alec Radford's Theano tutorials.
37. [pytorch\_exercises](https://github.com/Kyubyong/pytorch_exercises) ⭐ 315 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2017-09-28: pytorch-exercises
38. [Pytorch\_fine\_tuning\_Tutorial](https://github.com/Spandan-Madan/Pytorch_fine_tuning_Tutorial) ⭐ 290 | 🐛 5 | 🌐 Python | 📅 2018-09-14: A short tutorial on performing fine tuning or transfer learning in PyTorch.
39. [pytorch-REINFORCE](https://github.com/JamesChuanggg/pytorch-REINFORCE) ⭐ 266 | 🐛 5 | 🌐 Python | 📅 2017-04-16: PyTorch implementation of REINFORCE, This repo supports both continuous and discrete environments in OpenAI gym.
40. [pytorch-sync-batchnorm-example](https://github.com/dougsouza/pytorch-sync-batchnorm-example) ⭐ 248 | 🐛 0 | 📅 2019-05-13: How to use Cross Replica / Synchronized Batchnorm in Pytorch.
41. [pytorch-poetry-gen](https://github.com/justdark/pytorch-poetry-gen) ⭐ 238 | 🐛 1 | 🌐 Python | 📅 2017-04-10: a char-RNN based on pytorch.
42. [skip-thoughts](https://github.com/sanyam5/skip-thoughts) ⭐ 223 | 🐛 3 | 🌐 Python | 📅 2018-01-19: An implementation of Skip-Thought Vectors in PyTorch.
43. [AAE\_pytorch](https://github.com/fducau/AAE_pytorch) ⭐ 198 | 🐛 0 | 🌐 Python | 📅 2017-05-18: Adversarial Autoencoders (with Pytorch).
44. [pytorch practice](https://github.com/napsternxg/pytorch-practice) ⭐ 196 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2021-10-28: Some example scripts on pytorch.
45. [mss\_pytorch](https://github.com/Js-Mim/mss_pytorch) ⭐ 171 | 🐛 0 | 🌐 Python | 📅 2018-11-02: Singing Voice Separation via Recurrent Inference and Skip-Filtering Connections - PyTorch Implementation. Demo: js-mim.github.io/mss\_pytorch
46. [deeplearning.ai-pytorch](https://github.com/furkanu/deeplearning.ai-pytorch) ⭐ 158 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2020-12-15: PyTorch Implementations of Coursera's Deep Learning(deeplearning.ai) Specialization.
47. [accelerated\_dl\_pytorch](https://github.com/hpcgarage/accelerated_dl_pytorch) ⭐ 126 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-04-05: Accelerated Deep Learning with PyTorch at Jupyter Day Atlanta II.
48. [pytorch\_tutoria-quick](https://github.com/soravux/pytorch_tutorial) ⭐ 109 | 🐛 0 | 🌐 Python | 📅 2019-09-05: Quick PyTorch introduction and tutorial. Targets computer vision, graphics and machine learning researchers eager to try a new framework.
49. [pytorch-exercises](https://github.com/keon/pytorch-exercises) ⭐ 98 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-03-09: pytorch-exercises collection.
50. [MNIST\_Pytorch\_python\_and\_capi](https://github.com/tobiascz/MNIST_Pytorch_python_and_capi) ⭐ 96 | 🐛 0 | 🌐 Python | 📅 2018-10-11: This is an example of how to train a MNIST network in Python and run it in c++ with pytorch 1.0
51. [pytorch containers](https://github.com/amdegroot/pytorch-containers) ⭐ 88 | 🐛 0 | 🌐 Lua | 📅 2017-04-28: This repository aims to help former Torchies more seamlessly transition to the "Containerless" world of PyTorch by providing a list of PyTorch implementations of Torch Table Layers.
52. [pytorch\_bits](https://github.com/jpeg729/pytorch_bits) ⭐ 79 | 🐛 0 | 🌐 Python | 📅 2018-03-28: time-series prediction related examples.
53. [cats vs dogs](https://github.com/desimone/pytorch-cat-vs-dogs) ⚠️ Archived: Example of network fine-tuning in pytorch for the kaggle competition Dogs vs. Cats Redux: Kernels Edition. Currently #27 (0.05074) on the leaderboard.
54. [pytorch text classification](https://github.com/xiayandi/Pytorch_text_classification) ⭐ 66 | 🐛 1 | 🌐 Python | 📅 2017-02-11: A simple implementation of CNN based text classification in Pytorch
55. [pytorch.rl.learning](https://github.com/moskomule/pytorch.rl.learning) ⚠️ Archived: for learning reinforcement learning using PyTorch.
56. [mri-analysis-pytorch](https://github.com/omarsar/mri-analysis-pytorch) ⭐ 64 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2018-10-16: MRI analysis using PyTorch and MedicalTorch
57. [traffic-sign-detection](https://github.com/soumith/traffic-sign-detection-homework) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2018-10-15: nyu-cv-fall-2017 example
58. [portrain-gan](https://github.com/dribnet/portrain-gan) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2018-11-06: torch code to decode (and almost encode) latents from art-DCGAN's Portrait GAN.
59. [pytorch-intro](https://github.com/joansj/pytorch-intro) ⚠️ Archived: A couple of scripts to illustrate how to do CNNs and RNNs in PyTorch
60. [pytorch-generative-adversarial-networks](https://github.com/mailmahee/pytorch-generative-adversarial-networks) ⭐ 32 | 🐛 1 | 🌐 Python | 📅 2017-03-05: simple generative adversarial network (GAN) using PyTorch.
61. [DeepLearningForNLPInPytorch](https://pytorch.org/tutorials/beginner/deep_learning_nlp_tutorial.html): An IPython Notebook tutorial on deep learning, with an emphasis on Natural Language Processing.
62. [Generative Adversarial Networks (GANs) in 50 lines of code (PyTorch)](https://medium.com/@devnag/generative-adversarial-networks-gans-in-50-lines-of-code-pytorch-e81b79659e3f)
63. [adversarial-autoencoders-with-pytorch](https://blog.paperspace.com/adversarial-autoencoders-with-pytorch/)
64. [transfer learning using pytorch](https://medium.com/@vishnuvig/transfer-learning-using-pytorch-4c3475f4495)
65. [how-to-implement-a-yolo-object-detector-in-pytorch](https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/)
66. [pytorch-for-recommenders-101](http://blog.fastforwardlabs.com/2018/04/10/pytorch-for-recommenders-101.html)
67. [PyTorch Tutorial](http://www.pytorchtutorial.com/): PyTorch Tutorials in Chinese.
68. [Multiplicative LSTM for sequence-based Recommenders](https://florianwilhelm.info/2018/08/multiplicative_LSTM_for_sequence_based_recos/)
69. [Intro to Deep Learning with PyTorch](https://in.udacity.com/course/deep-learning-pytorch--ud188): A free course by Udacity and facebook, with a good intro to PyTorch, and an interview with Soumith Chintala, one of the original authors of PyTorch.
70. [Deep Learning with PyTorch: Zero to GANs](https://jovian.ml/aakashns/collections/deep-learning-with-pytorch): Interactive and coding-focused tutorial series on introduction to Deep Learning with PyTorch ([video](https://www.youtube.com/watch?v=GIsg-ZUy0MY)).
71. [Deep Learning with PyTorch](https://www.manning.com/books/deep-learning-with-pytorch): Deep Learning with PyTorch teaches you how to implement deep learning algorithms with Python and PyTorch, the book includes a case study: building an algorithm capable of detecting malignant lung tumors using CT scans.
72. [Serverless Machine Learning in Action with PyTorch and AWS](https://www.manning.com/books/serverless-machine-learning-in-action): Serverless Machine Learning in Action is a guide to bringing your experimental PyTorch machine learning code to production using serverless capabilities from major cloud providers like AWS, Azure, or GCP.
73. [The Math Behind Artificial Intelligence](https://www.freecodecamp.org/news/the-math-behind-artificial-intelligence-book): A free FreeCodeCamp book teaching the math behind AI in plain English from an engineering point of view. It covers linear algebra, calculus, probability & statistics, and optimization theory with analogies, real-life applications, and Python code examples.

## Paper implementations

1. [pytorch-pretrained-BERT](https://github.com/huggingface/pytorch-pretrained-BERT) ⭐ 164,027 | 🐛 2,378 | 🌐 Python | 📅 2026-08-12: PyTorch version of Google AI's BERT model with script to load Google's pre-trained models
2. [pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) ⭐ 25,218 | 🐛 589 | 🌐 Python | 📅 2025-08-06: PyTorch implementation for both unpaired and paired image-to-image translation.
3. [PyTorch-GAN](https://github.com/eriklindernoren/PyTorch-GAN) ⭐ 17,450 | 🐛 142 | 🌐 Python | 📅 2024-06-18: PyTorch implementations of Generative Adversarial Networks.
4. [grad-cam](https://github.com/jacobgil/pytorch-grad-cam) ⭐ 12,952 | 🐛 163 | 🌐 Python | 📅 2026-07-10: Pytorch implementation of Grad-CAM
5. [FastPhotoStyle](https://github.com/NVIDIA/FastPhotoStyle) ⭐ 11,179 | 🐛 57 | 🌐 Python | 📅 2023-06-07: A Closed-form Solution to Photorealistic Image Stylization
6. [yolov3](https://github.com/ultralytics/yolov3) ⭐ 10,589 | 🐛 4 | 🌐 Python | 📅 2026-08-02: YOLOv3: Training and inference in PyTorch pjreddie.com/darknet/yolo
7. [attention-is-all-you-need-pytorch](https://github.com/jadore801120/attention-is-all-you-need-pytorch) ⭐ 9,781 | 🐛 83 | 🌐 Python | 📅 2024-04-16: A PyTorch implementation of the Transformer model in "Attention is All You Need".<https://github.com/thnkim/OpenFacePytorch> ⭐ 189 | 🐛 5 | 🌐 Python | 📅 2020-02-20
8. [vid2vid](https://github.com/NVIDIA/vid2vid) ⭐ 8,693 | 🐛 110 | 🌐 Python | 📅 2022-05-17: Pytorch implementation of our method for high-resolution (e.g. 2048x1024) photorealistic video-to-video translation.
9. [deep-image-prior](https://github.com/DmitryUlyanov/deep-image-prior) ⭐ 8,086 | 🐛 70 | 🌐 Jupyter Notebook | 📅 2023-04-27: Image restoration with neural networks but without learning.
10. [pulse](https://github.com/adamian98/pulse) ⭐ 8,023 | 🐛 61 | 🌐 Python | 📅 2021-04-30: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models
11. [faster-rcnn.pytorch](https://github.com/jwyang/faster-rcnn.pytorch) ⭐ 7,856 | 🐛 422 | 🌐 Python | 📅 2022-05-20: This project is a faster faster R-CNN implementation, aimed to accelerating the training of faster R-CNN object detection models.
12. [face-alignment](https://github.com/1adrianb/face-alignment) ⭐ 7,536 | 🐛 91 | 🌐 Python | 📅 2026-04-06: Pytorch implementation of the paper "How far are we from solving the 2D & 3D Face Alignment problem? (and a dataset of 230,000 3D facial landmarks)", ICCV 2017
13. [pix2pixHD](https://github.com/NVIDIA/pix2pixHD) ⭐ 6,931 | 🐛 247 | 🌐 Python | 📅 2024-11-04: Synthesizing and manipulating 2048x1024 images with conditional GANs tcwang0509.github.io/pix2pixHD
14. [Deep-Reinforcement-Learning-Algorithms-with-PyTorch](https://github.com/p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch) ⭐ 5,937 | 🐛 48 | 🌐 Python | 📅 2024-07-25: This repository contains PyTorch implementations of deep reinforcement learning algorithms.
15. [Deep-Reinforcement-Learning-Algorithms-with-PyTorch](https://github.com/p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch) ⭐ 5,937 | 🐛 48 | 🌐 Python | 📅 2024-07-25: PyTorch implementations of deep reinforcement learning algorithms and environments.
16. [pygcn](https://github.com/tkipf/pygcn) ⭐ 5,400 | 🐛 58 | 🌐 Python | 📅 2020-09-20: Graph Convolutional Networks in PyTorch.
17. [tacotron2](https://github.com/NVIDIA/tacotron2) ⭐ 5,295 | 🐛 219 | 🌐 Jupyter Notebook | 📅 2024-06-12: Tacotron 2 - PyTorch implementation with faster-than-realtime inference.
18. [StarGAN](https://github.com/yunjey/StarGAN) ⭐ 5,293 | 🐛 67 | 🌐 Python | 📅 2021-01-23: StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Tranlsation.
19. [Single Shot MultiBox Detector](https://github.com/amdegroot/ssd.pytorch) ⭐ 5,220 | 🐛 380 | 🌐 Python | 📅 2021-12-29: A PyTorch Implementation of Single Shot MultiBox Detector.
20. [semantic-segmentation-pytorch](https://github.com/hangzhaomit/semantic-segmentation-pytorch) ⭐ 5,077 | 🐛 81 | 🌐 Python | 📅 2024-01-15: Pytorch implementation for Semantic Segmentation/Scene Parsing on [MIT ADE20K dataset](http://sceneparsing.csail.mit.edu)
21. [TCN](https://github.com/locuslab/TCN) ⭐ 4,544 | 🐛 20 | 🌐 Python | 📅 2022-03-28: Sequence modeling benchmarks and temporal convolutional networks locuslab/TCN
22. [Person-reID\_pytorch](https://github.com/layumi/Person_reID_baseline_pytorch) ⭐ 4,444 | 🐛 172 | 🌐 Python | 📅 2026-07-18: PyTorch for Person re-ID.
23. [3D-ResNets-PyTorch](https://github.com/kenshohara/3D-ResNets-PyTorch) ⭐ 4,037 | 🐛 154 | 🌐 Python | 📅 2021-01-20: 3D ResNets for Action Recognition.
24. [pytorch-a2c-ppo-acktr](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr) ⭐ 3,902 | 🐛 93 | 🌐 Python | 📅 2022-05-29: PyTorch implementation of Advantage Actor Critic (A2C), Proximal Policy Optimization (PPO) and Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation (ACKTR).
25. [pytorch - fid](https://github.com/mseitzer/pytorch-fid) ⭐ 3,851 | 🐛 27 | 🌐 Python | 📅 2024-07-03: A Port of Fréchet Inception Distance (FID score) to PyTorch
26. [Transformer-XL](https://github.com/kimiyoung/transformer-xl) ⭐ 3,714 | 🐛 97 | 🌐 Python | 📅 2022-09-21: Transformer-XL: Attentive Language Models Beyond a Fixed-Length Contexthttps\://github.com/kimiyoung/transformer-xl
27. [3DDFA](https://github.com/cleardusk/3DDFA) ⭐ 3,676 | 🐛 65 | 🌐 Python | 📅 2022-05-14: The pytorch improved re-implementation of TPAMI 2017 paper: Face Alignment in Full Pose Range: A 3D Total Solution.
28. [FlowNet 2.0](https://github.com/NVIDIA/flownet2-pytorch) ⭐ 3,289 | 🐛 167 | 🌐 Python | 📅 2026-03-30: FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks
29. [WassersteinGAN](https://github.com/martinarjovsky/WassersteinGAN) ⭐ 3,244 | 🐛 28 | 🌐 Python | 📅 2018-12-26: wassersteinGAN in pytorch.
30. [loss-landscape](https://github.com/tomgoldstein/loss-landscape) ⭐ 3,196 | 🐛 30 | 🌐 Python | 📅 2022-04-05: loss-landscape Code for visualizing the loss landscape of neural nets.
31. [BigGAN-PyTorch](https://github.com/ajbrock/BigGAN-PyTorch) ⭐ 2,924 | 🐛 49 | 🌐 Python | 📅 2023-07-19: The author's officially unofficial PyTorch BigGAN implementation.
32. [XLM](https://github.com/facebookresearch/XLM) ⚠️ Archived: PyTorch original implementation of Cross-lingual Language Model Pretraining.
33. [Detectron.pytorch](https://github.com/roytseng-tw/Detectron.pytorch) ⚠️ Archived: A pytorch implementation of Detectron. Both training from scratch and inferring directly from pretrained Detectron weights are available.
34. [ENAS-pytorch](https://github.com/carpedm20/ENAS-pytorch) ⭐ 2,719 | 🐛 40 | 🌐 Python | 📅 2023-07-06: PyTorch implementation of "Efficient Neural Architecture Search via Parameters Sharing".
35. **[pytorch-playground](https://github.com/aaron-xichen/pytorch-playground) ⭐ 2,717 | 🐛 11 | 🌐 Python | 📅 2022-11-22: Base pretrained models and datasets in pytorch (MNIST, SVHN, CIFAR10, CIFAR100, STL10, AlexNet, VGG16, VGG19, ResNet, Inception, SqueezeNet)**.
36. [DeblurGAN](https://github.com/KupynOrest/DeblurGAN) ⭐ 2,639 | 🐛 148 | 🌐 Python | 📅 2019-12-25: Pytorch implementation of the paper DeblurGAN: Blind Motion Deblurring Using Conditional Adversarial Networks.
37. [pytorch-generative-model-collections](https://github.com/znxlwm/pytorch-generative-model-collections) ⭐ 2,627 | 🐛 27 | 🌐 Python | 📅 2020-04-12:  Collection of generative models in Pytorch version.
38. [EDSR-PyTorch](https://github.com/thstkdgus35/EDSR-PyTorch) ⭐ 2,627 | 🐛 142 | 🌐 Python | 📅 2023-01-03: PyTorch version of the paper 'Enhanced Deep Residual Networks for Single Image Super-Resolution' (CVPRW 2017)
39. [pointnet.pytorch](https://github.com/fxia22/pointnet.pytorch) ⭐ 2,353 | 🐛 60 | 🌐 Python | 📅 2023-03-23: pytorch implementation for "PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation" <https://arxiv.org/abs/1612.00593>
40. [waveglow](https://github.com/NVIDIA/waveglow) ⭐ 2,340 | 🐛 79 | 🌐 Python | 📅 2023-10-19: A Flow-based Generative Network for Speech Synthesis.
41. [deepspeech2](https://github.com/SeanNaren/deepspeech.pytorch) ⭐ 2,136 | 🐛 5 | 🌐 Python | 📅 2022-12-13: Implementation of DeepSpeech2 using Baidu Warp-CTC. Creates a network based on the DeepSpeech2 architecture, trained with the CTC activation function.
42. [UNIT](https://github.com/mingyuliutw/UNIT) ⭐ 2,027 | 🐛 5 | 🌐 Python | 📅 2021-09-02: PyTorch Implementation of our Coupled VAE-GAN algorithm for Unsupervised Image-to-Image Translation
43. [PyKEEN](https://github.com/pykeen/pykeen) ⭐ 2,023 | 🐛 128 | 🌐 Python | 📅 2026-08-09: A Python library for learning and evaluating knowledge graph embeddings.
44. [deepvoice3\_pytorch](https://github.com/r9y9/deepvoice3_pytorch) ⭐ 1,975 | 🐛 47 | 🌐 Python | 📅 2023-12-19: PyTorch implementation of convolutional networks-based text-to-speech synthesis models
45. [NVIDIA/semantic-segmentation](https://github.com/NVIDIA/semantic-segmentation) ⭐ 1,827 | 🐛 89 | 🌐 Python | 📅 2021-07-26: A PyTorch Implementation of [Improving Semantic Segmentation via Video Propagation and Label Relaxation](https://arxiv.org/abs/1812.01593), In CVPR2019.
46. [pytorch-faster-rcnn](https://github.com/ruotianluo/pytorch-faster-rcnn) ⭐ 1,811 | 🐛 79 | 🌐 Jupyter Notebook | 📅 2020-11-12: A pytorch implementation of faster RCNN detection framework based on Xinlei Chen's tf-faster-rcnn.
47. [pytorch-fcn](https://github.com/wkentaro/pytorch-fcn) ⚠️ Archived: PyTorch implementation of Fully Convolutional Networks.
48. [faster rcnn](https://github.com/longcw/faster_rcnn_pytorch) ⭐ 1,776 | 🐛 71 | 🌐 Python | 📅 2021-09-25: This is a PyTorch implementation of Faster RCNN. This project is mainly based on py-faster-rcnn and TFFRCNN.For details about R-CNN please refer to the paper Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks by Shaoqing Ren, Kaiming He, Ross Girshick, Jian Sun.
49. [poincare-embeddings](https://github.com/facebookresearch/poincare-embeddings) ⚠️ Archived: PyTorch implementation of the NIPS-17 paper "Poincaré Embeddings for Learning Hierarchical Representations".
50. [Rainbow](https://github.com/Kaixhin/Rainbow) ⭐ 1,671 | 🐛 9 | 🌐 Python | 📅 2022-01-13: Rainbow: Combining Improvements in Deep Reinforcement Learning
51. [deep-head-pose](https://github.com/natanielruiz/deep-head-pose) ⭐ 1,665 | 🐛 57 | 🌐 Python | 📅 2023-05-23: Deep Learning Head Pose Estimation using PyTorch.
52. [YOLO2](https://github.com/longcw/yolo2-pytorch) ⭐ 1,560 | 🐛 87 | 🌐 Python | 📅 2021-09-29: YOLOv2 in PyTorch.
53. [wgan-gp](https://github.com/caogang/wgan-gp) ⭐ 1,547 | 🐛 32 | 🌐 Python | 📅 2023-07-18: A pytorch implementation of Paper "Improved Training of Wasserstein GANs".
54. [efficient\_densenet\_pytorch](https://github.com/gpleiss/efficient_densenet_pytorch) ⭐ 1,535 | 🐛 12 | 🌐 Python | 📅 2023-06-01: A memory-efficient implementation of DenseNets
55. [pytorch-openai-transformer-lm](https://github.com/huggingface/pytorch-openai-transformer-lm) ⭐ 1,522 | 🐛 24 | 🌐 Python | 📅 2021-08-09: This is a PyTorch implementation of the TensorFlow code provided with OpenAI's paper "Improving Language Understanding by Generative Pre-Training" by Alec Radford, Karthik Narasimhan, Tim Salimans and Ilya Sutskever.
56. [neuraltalk2-pytorch](https://github.com/ruotianluo/neuraltalk2.pytorch) ⭐ 1,477 | 🐛 99 | 🌐 Python | 📅 2023-10-05: image captioning model in pytorch(finetunable cnn in branch with\_finetune)
57. [attention-transfer](https://github.com/szagoruyko/attention-transfer) ⭐ 1,463 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2018-07-11: Attention transfer in pytorch, read the paper [here](https://arxiv.org/abs/1612.03928).
58. [end-to-end-negotiator](https://github.com/facebookresearch/end-to-end-negotiator) ⚠️ Archived: Deal or No Deal? End-to-End Learning for Negotiation Dialogues
59. [Realtime\_Multi-Person\_Pose\_Estimation](https://github.com/tensorboy/pytorch_Realtime_Multi-Person_Pose_Estimation) ⭐ 1,371 | 🐛 62 | 🌐 Python | 📅 2023-02-07: This is a pytorch version of Realtime\_Multi-Person\_Pose\_Estimation, origin code is [here](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation) ⭐ 5,123 | 🐛 107 | 🌐 Jupyter Notebook | 📅 2020-03-21 .
60. [inplace\_abn](https://github.com/mapillary/inplace_abn) ⭐ 1,333 | 🐛 63 | 🌐 Python | 📅 2026-07-25: In-Place Activated BatchNorm for Memory-Optimized Training of DNNs
61. [NVlabs/DG-Net](https://github.com/NVlabs/DG-Net) ⭐ 1,298 | 🐛 48 | 🌐 Python | 📅 2023-07-09: A PyTorch implementation of "Joint Discriminative and Generative Learning for Person Re-identification" (CVPR19 Oral).
62. [CapsGNN](https://github.com/benedekrozemberczki/CapsGNN) ⭐ 1,278 | 🐛 4 | 🌐 Python | 📅 2023-03-18: Capsule Graph Neural Network. (ICLR 2019).
63. [AnimeGAN](https://github.com/jayleicn/animeGAN) ⭐ 1,277 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2022-08-24: A simple PyTorch Implementation of Generative Adversarial Networks, focusing on anime face drawing.
64. [pytorch-qrnn](https://github.com/salesforce/pytorch-qrnn) ⚠️ Archived: PyTorch implementation of the Quasi-Recurrent Neural Network - up to 16 times faster than NVIDIA's cuDNN LSTM
65. [voicefilter](https://github.com/mindslab-ai/voicefilter) ⭐ 1,214 | 🐛 13 | 🌐 Python | 📅 2024-07-25: Unofficial PyTorch implementation of Google AI's VoiceFilter system <http://swpark.me/voicefilter>.
66. [pytorch-pose](https://github.com/bearpaw/pytorch-pose) ⭐ 1,121 | 🐛 32 | 🌐 Python | 📅 2021-12-20: A PyTorch toolkit for 2D Human Pose Estimation.
67. [DiscoGAN](https://github.com/carpedm20/DiscoGAN-pytorch) ⭐ 1,095 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2018-03-26: PyTorch implementation of "Learning to Discover Cross-Domain Relations with Generative Adversarial Networks"
68. [Prototypical-Networks-for-Few-shot-Learning-PyTorch](https://github.com/orobix/Prototypical-Networks-for-Few-shot-Learning-PyTorch) ⭐ 1,078 | 🐛 9 | 🌐 Python | 📅 2022-04-05: Implementation of Prototypical Networks for Few Shot Learning (arxiv.org/abs/1703.05175) in Pytorch
69. [tsn-pytorch](https://github.com/yjxiong/tsn-pytorch) ⭐ 1,076 | 🐛 44 | 🌐 Python | 📅 2019-06-21: Temporal Segment Networks (TSN) in PyTorch.
70. [graphsage-simple](https://github.com/williamleif/graphsage-simple) ⭐ 1,051 | 🐛 20 | 🌐 Python | 📅 2020-05-11: Simple reference implementation of GraphSAGE.
71. [Cnn-text classification](https://github.com/Shawn1993/cnn-text-classification-pytorch) ⭐ 1,043 | 🐛 0 | 🌐 Python | 📅 2026-03-23: This is the implementation of Kim's Convolutional Neural Networks for Sentence Classification paper in PyTorch.
72. [SfmLearner-Pytorch ](https://github.com/ClementPinard/SfmLearner-Pytorch) ⭐ 1,031 | 🐛 8 | 🌐 Python | 📅 2026-04-15: Pytorch version of SfmLearner from Tinghui Zhou et al.
73. [gpt-2-Pytorch](https://github.com/graykode/gpt-2-Pytorch) ⭐ 1,012 | 🐛 18 | 🌐 Python | 📅 2019-07-08: Simple Text-Generator with OpenAI gpt-2 Pytorch Implementation
74. [PyTorch-Style-Transfer](https://github.com/zhanghang1989/PyTorch-Style-Transfer) ⭐ 1,009 | 🐛 26 | 🌐 Jupyter Notebook | 📅 2022-05-12: PyTorch Implementation of Multi-style Generative Network for Real-time Transfer
75. [self-critical.pytorch](https://github.com/ruotianluo/self-critical.pytorch) ⭐ 1,003 | 🐛 89 | 🌐 Python | 📅 2023-10-05: Unofficial pytorch implementation for Self-critical Sequence Training for Image Captioning.
76. [pytorch-retinanet](https://github.com/kuangliu/pytorch-retinanet) ⭐ 997 | 🐛 51 | 🌐 Python | 📅 2019-03-17: RetinaNet in PyTorch
77. [Mask-RCNN](https://github.com/wannabeOG/Mask-RCNN) ⭐ 987 | 🐛 17 | 🌐 Python | 📅 2019-11-05: A PyTorch implementation of the architecture of Mask RCNN, serves as an introduction to working with PyTorch
78. [torchMoji](https://github.com/huggingface/torchMoji) ⭐ 921 | 🐛 21 | 🌐 Python | 📅 2024-02-12: A pyTorch implementation of the DeepMoji model: state-of-the-art deep learning model for analyzing sentiment, emotion, sarcasm etc.
79. [GAN\_stability](https://github.com/LMescheder/GAN_stability) ⭐ 921 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2019-08-27: Code for paper "Which Training Methods for GANs do actually Converge? (ICML 2018)"
80. [pytorch-deform-conv](https://github.com/oeway/pytorch-deform-conv) ⚠️ Archived: PyTorch implementation of Deformable Convolution.
81. [flownet](https://github.com/ClementPinard/FlowNetPytorch) ⭐ 900 | 🐛 7 | 🌐 Python | 📅 2026-04-15: Pytorch implementation of FlowNet by Dosovitskiy et al.
82. [breast\_cancer\_classifier](https://github.com/nyukat/breast_cancer_classifier) ⭐ 890 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2023-12-14: Deep Neural Networks Improve Radiologists' Performance in Breast Cancer Screening arxiv.org/abs/1903.08297
83. [pytorch-pruning](https://github.com/jacobgil/pytorch-pruning) ⭐ 885 | 🐛 31 | 🌐 Python | 📅 2019-07-12: PyTorch Implementation of \[1611.06440] Pruning Convolutional Neural Networks for Resource Efficient Inference
84. [neural-style-pt](https://github.com/ProGamerGov/neural-style-pt) ⭐ 856 | 🐛 25 | 🌐 Python | 📅 2022-10-15: A PyTorch implementation of Justin Johnson's Neural-style.
85. [FaceBoxes.PyTorch](https://github.com/zisianw/FaceBoxes.PyTorch) ⭐ 850 | 🐛 18 | 🌐 Python | 📅 2024-12-11: A PyTorch Implementation of FaceBoxes.
86. [LM-LSTM-CRF](https://github.com/LiyuanLucasLiu/LM-LSTM-CRF) ⭐ 848 | 🐛 18 | 🌐 Python | 📅 2022-06-22: Empower Sequence Labeling with Task-Aware Language Model <http://arxiv.org/abs/1709.04109>
87. [stackGAN-v2](https://github.com/hanzhanggit/StackGAN-v2) ⭐ 847 | 🐛 35 | 🌐 Python | 📅 2020-01-13: Pytorch implementation for reproducing StackGAN\_v2 results in the paper StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks by Han Zhang\*, Tao Xu\*, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas.
88. [DEXTR-PyTorch](https://github.com/scaelles/DEXTR-PyTorch) ⭐ 846 | 🐛 3 | 🌐 Python | 📅 2020-09-04: Deep Extreme Cut <http://www.vision.ee.ethz.ch/~cvlsegmentation/dextr>
89. [densenet](https://github.com/bamos/densenet.pytorch) ⭐ 838 | 🐛 7 | 🌐 Python | 📅 2018-08-16: This is a PyTorch implementation of the DenseNet-BC architecture as described in the paper Densely Connected Convolutional Networks by G. Huang, Z. Liu, K. Weinberger, and L. van der Maaten. This implementation gets a CIFAR-10+ error rate of 4.77 with a 100-layer DenseNet-BC with a growth rate of 12. Their official implementation and links to many other third-party implementations are available in the liuzhuang13/DenseNet repo on GitHub.
90. [relational-networks](https://github.com/kimhc6028/relational-networks) ⭐ 816 | 🐛 9 | 🌐 Python | 📅 2022-12-06: Pytorch implementation of "A simple neural network module for relational reasoning" (Relational Networks) <https://arxiv.org/pdf/1706.01427.pdf>
91. [SimGNN](https://github.com/benedekrozemberczki/SimGNN) ⭐ 815 | 🐛 9 | 🌐 Python | 📅 2023-01-12: SimGNN: A Neural Network Approach to Fast Graph Similarity Computation.
92. [ClusterGCN](https://github.com/benedekrozemberczki/ClusterGCN) ⭐ 804 | 🐛 4 | 🌐 Python | 📅 2022-11-06: A PyTorch implementation of "Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks" (KDD 2019).
93. [pytorch-rl](https://github.com/jingweiz/pytorch-rl) ⭐ 802 | 🐛 6 | 🌐 Python | 📅 2020-07-16: Deep Reinforcement Learning with pytorch & visdom
94. [qp solver](https://github.com/locuslab/qpth) ⭐ 800 | 🐛 17 | 🌐 Python | 📅 2024-09-03: A fast and differentiable QP solver for PyTorch. Crafted by Brandon Amos and J. Zico Kolter.
95. [official DiscoGAN implementation](https://github.com/SKTBrain/DiscoGAN) ⭐ 777 | 🐛 21 | 🌐 Python | 📅 2021-03-11: Official implementation of "Learning to Discover Cross-Domain Relations with Generative Adversarial Networks".
96. [brain-segmentation-pytorch](https://github.com/mateuszbuda/brain-segmentation-pytorch) ⭐ 775 | 🐛 23 | 🌐 Python | 📅 2023-03-24: U-Net implementation in PyTorch for FLAIR abnormality segmentation in brain MRI.
97. [bottom-up-attention-vqa](https://github.com/hengyuan-hu/bottom-up-attention-vqa) ⭐ 768 | 🐛 19 | 🌐 Python | 📅 2024-03-10: vqa, bottom-up-attention, pytorch
98. [FaderNetworks](https://github.com/facebookresearch/FaderNetworks) ⚠️ Archived: Fader Networks: Manipulating Images by Sliding Attributes - NIPS 2017
99. [NCRF](https://github.com/baidu-research/NCRF) ⭐ 759 | 🐛 4 | 🌐 Python | 📅 2023-10-03: Cancer metastasis detection with neural conditional random field (NCRF)
100. [vnet.pytorch](https://github.com/mattmacy/vnet.pytorch) ⭐ 756 | 🐛 26 | 🌐 Python | 📅 2018-07-06: A Pytorch implementation for V-Net: Fully Convolutional Neural Networks for Volumetric Medical Image Segmentation.
101. [seq2seq](https://github.com/MaximumEntropy/Seq2Seq-PyTorch) ⭐ 740 | 🐛 6 | 🌐 Python | 📅 2022-03-27: This repository contains implementations of Sequence to Sequence (Seq2Seq) models in PyTorch
102. [Random-Erasing](https://github.com/zhunzhong07/Random-Erasing) ⭐ 735 | 🐛 10 | 🌐 Python | 📅 2023-11-08: This code has the source code for the paper "Random Erasing Data Augmentation".
103. [vqa.pytorch](https://github.com/Cadene/vqa.pytorch) ⭐ 733 | 🐛 19 | 🌐 Python | 📅 2019-12-11: Visual Question Answering in Pytorch
104. [sphereface\_pytorch](https://github.com/clcarwin/sphereface_pytorch) ⭐ 715 | 🐛 35 | 🌐 Python | 📅 2022-02-01: A PyTorch Implementation of SphereFace.
105. [ConvE](https://github.com/TimDettmers/ConvE) ⭐ 692 | 🐛 24 | 🌐 Python | 📅 2024-03-29: Convolutional 2D Knowledge Graph Embeddings
106. [CondenseNet](https://github.com/ShichenLiu/CondenseNet) ⭐ 690 | 🐛 11 | 🌐 Python | 📅 2019-11-11: CondenseNet: An Efficient DenseNet using Learned Group Convolutions.
107. [RandWireNN](https://github.com/seungwonpark/RandWireNN) ⭐ 684 | 🐛 3 | 🌐 Python | 📅 2019-06-26: Implementation of: "Exploring Randomly Wired Neural Networks for Image Recognition".
108. [pytorch-capsule](https://github.com/timomernick/pytorch-capsule) ⭐ 629 | 🐛 7 | 🌐 Python | 📅 2018-04-09: Pytorch implementation of Hinton's Dynamic Routing Between Capsules.
109. [neural-combinatorial-rl-pytorch](https://github.com/pemami4911/neural-combinatorial-rl-pytorch) ⭐ 612 | 🐛 11 | 🌐 Python | 📅 2018-05-29:  PyTorch implementation of Neural Combinatorial Optimization with Reinforcement Learning.
110. [pytorch-pose-hg-3d](https://github.com/xingyizhou/pytorch-pose-hg-3d) ⭐ 612 | 🐛 36 | 🌐 Python | 📅 2023-06-21: PyTorch implementation for 3D human pose estimation
111. [pytorch-ntm](https://github.com/loudinthecloud/pytorch-ntm) ⭐ 610 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2018-06-26: pytorch ntm implementation.
112. [GraphWaveletNeuralNetwork](https://github.com/benedekrozemberczki/GraphWaveletNeuralNetwork) ⭐ 607 | 🐛 2 | 🌐 Python | 📅 2023-03-18: This is a Pytorch implementation of Graph Wavelet Neural Network. ICLR 2019.
113. [pytorch-deeplab-resnet](https://github.com/isht7/pytorch-deeplab-resnet) ⭐ 601 | 🐛 14 | 🌐 Python | 📅 2023-09-05: pytorch-deeplab-resnet-model.
114. [pytorch-made](https://github.com/karpathy/pytorch-made) ⭐ 594 | 🐛 2 | 🌐 Python | 📅 2018-12-08: MADE (Masked Autoencoder Density Estimation) implementation in PyTorch
115. [pspnet-pytorch](https://github.com/Lextal/pspnet-pytorch) ⭐ 590 | 🐛 17 | 🌐 Python | 📅 2017-10-06: PyTorch implementation of PSPNet segmentation network
116. [pytorch-flows](https://github.com/ikostrikov/pytorch-flows) ⭐ 589 | 🐛 5 | 🌐 Python | 📅 2021-05-13: PyTorch implementations of algorithms for density estimation
117. [optnet](https://github.com/locuslab/optnet) ⭐ 588 | 🐛 3 | 🌐 Python | 📅 2020-03-26: This repository is by Brandon Amos and J. Zico Kolter and contains the PyTorch source code to reproduce the experiments in our paper OptNet: Differentiable Optimization as a Layer in Neural Networks.
118. [Neural-IMage-Assessment](https://github.com/kentsyx/Neural-IMage-Assessment) ⭐ 585 | 🐛 24 | 🌐 Python | 📅 2021-11-10: A PyTorch Implementation of Neural IMage Assessment.
119. [PyTorch-progressive\_growing\_of\_gans](https://github.com/github-pengge/PyTorch-progressive_growing_of_gans) ⭐ 582 | 🐛 29 | 🌐 Python | 📅 2018-02-04: PyTorch implementation of Progressive Growing of GANs for Improved Quality, Stability, and Variation.
120. [pytorch-maml](https://github.com/katerakelly/pytorch-maml) ⭐ 567 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2018-10-04: PyTorch implementation of MAML: arxiv.org/abs/1703.03400
121. [rl\_a3c\_pytorch](https://github.com/dgriff777/rl_a3c_pytorch) ⭐ 563 | 🐛 13 | 🌐 Python | 📅 2023-04-18: Reinforcement learning with implementation of A3C LSTM for Atari 2600.
122. [treelstm.pytorch](https://github.com/dasguptar/treelstm.pytorch) ⭐ 551 | 🐛 17 | 🌐 Python | 📅 2019-09-30: Tree LSTM implementation in PyTorch.
123. [ban-vqa](https://github.com/jnhwkim/ban-vqa) ⚠️ Archived: Bilinear attention networks for visual question answering.
124. [T2F](https://github.com/akanimax/T2F) ⭐ 546 | 🐛 18 | 🌐 Python | 📅 2022-05-14: Text-to-Face generation using Deep Learning. This project combines two of the recent architectures StackGAN and ProGAN for synthesizing faces from textual descriptions.
125. [glow-pytorch](https://github.com/rosinality/glow-pytorch) ⭐ 544 | 🐛 33 | 🌐 Python | 📅 2021-11-20: PyTorch implementation of Glow, Generative Flow with Invertible 1x1 Convolutions (arxiv.org/abs/1807.03039)
126. [honk](https://github.com/castorini/honk) ⭐ 526 | 🐛 7 | 🌐 Python | 📅 2023-05-22: PyTorch reimplementation of Google's TensorFlow CNNs for keyword spotting.
127. [vsepp](https://github.com/fartashf/vsepp) ⭐ 523 | 🐛 0 | 🌐 Python | 📅 2021-12-08: Code for the paper "VSE++: Improved Visual Semantic Embeddings"
128. [pytorch-coviar](https://github.com/chaoyuaw/pytorch-coviar) ⭐ 523 | 🐛 56 | 🌐 Python | 📅 2018-07-06: Compressed Video Action Recognition
129. [ResNeXt.pytorch](https://github.com/prlz77/ResNeXt.pytorch) ⭐ 518 | 🐛 7 | 🌐 Python | 📅 2020-08-01: Reproduces ResNet-V3 (Aggregated Residual Transformations for Deep Neural Networks) with pytorch.
130. [seq2seq.pytorch](https://github.com/eladhoffer/seq2seq.pytorch) ⭐ 518 | 🐛 9 | 🌐 Python | 📅 2019-11-12: Sequence-to-Sequence learning using PyTorch
131. [/pytorch-SRResNet](https://github.com/twtygqyy/pytorch-SRResNet) ⭐ 509 | 🐛 25 | 🌐 Python | 📅 2018-03-26: pytorch implementation for Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network arXiv:1609.04802v2
132. [generative-models](https://github.com/shayneobrien/generative-models) ⭐ 503 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2018-11-19: Annotated, understandable, and visually interpretable PyTorch implementations of: VAE, BIRVAE, NSGAN, MMGAN, WGAN, WGANGP, LSGAN, DRAGAN, BEGAN, RaGAN, InfoGAN, fGAN, FisherGAN.
133. [attn2d](https://github.com/elbayadm/attn2d) ⭐ 496 | 🐛 3 | 🌐 Python | 📅 2021-05-08: Pervasive Attention: 2D Convolutional Networks for Sequence-to-Sequence Prediction
134. [CapsNet-pytorch](https://github.com/adambielski/CapsNet-pytorch) ⭐ 494 | 🐛 5 | 🌐 Python | 📅 2021-04-13: PyTorch implementation of NIPS 2017 paper Dynamic Routing Between Capsules.
135. [Structured-Self-Attention](https://github.com/kaushalshetty/Structured-Self-Attention) ⭐ 492 | 🐛 2 | 🌐 Python | 📅 2019-09-22: Implementation for the paper A Structured Self-Attentive Sentence Embedding, which is published in ICLR 2017: arxiv.org/abs/1703.03130 .
136. [SMASH](https://github.com/ajbrock/SMASH) ⭐ 491 | 🐛 4 | 🌐 Python | 📅 2017-08-19: An experimental technique for efficiently exploring neural architectures.
137. [STEAL](https://github.com/nv-tlabs/STEAL) ⭐ 481 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2023-10-23: STEAL - Learning Semantic Boundaries from Noisy Annotations nv-tlabs.github.io/STEAL
138. [trellisnet](https://github.com/locuslab/trellisnet) ⭐ 471 | 🐛 1 | 🌐 Python | 📅 2019-08-20: Trellis Networks for Sequence Modeling
139. [ggnn.pytorch](https://github.com/JamesChuanggg/ggnn.pytorch) ⭐ 469 | 🐛 2 | 🌐 Python | 📅 2019-07-31: A PyTorch Implementation of Gated Graph Sequence Neural Networks (GGNN).
140. [pytorch-trpo(Hessian-vector product version)](https://github.com/ikostrikov/pytorch-trpo) ⭐ 448 | 🐛 7 | 🌐 Python | 📅 2018-09-13: This is a PyTorch implementation of "Trust Region Policy Optimization (TRPO)" with exact Hessian-vector product instead of finite differences approximation.
141. [pix2pix-pytorch](https://github.com/mrzhu-cool/pix2pix-pytorch) ⭐ 445 | 🐛 10 | 🌐 Python | 📅 2018-12-22: PyTorch implementation of "Image-to-Image Translation Using Conditional Adversarial Networks".
142. [yolo2-pytorch](https://github.com/ruiminshen/yolo2-pytorch) ⭐ 443 | 🐛 12 | 🌐 Python | 📅 2018-05-12: The YOLOv2 is one of the most popular one-stage object detector. This project adopts PyTorch as the developing framework to increase productivity, and utilize ONNX to convert models into Caffe 2 to benifit engineering deployment.
143. [mnist-svhn-transfer](https://github.com/yunjey/mnist-svhn-transfer) ⭐ 438 | 🐛 8 | 🌐 Python | 📅 2017-05-27: PyTorch Implementation of CycleGAN and SGAN for Domain Transfer (Minimal).
144. [Shufflenet-v2-Pytorch](https://github.com/ericsun99/Shufflenet-v2-Pytorch) ⭐ 435 | 🐛 13 | 🌐 Python | 📅 2019-04-09: This is a Pytorch implementation of faceplusplus's ShuffleNet-v2.
145. [PytorchNeuralStyleTransfer](https://github.com/leongatys/PytorchNeuralStyleTransfer) ⭐ 432 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2021-02-05: Implementation of Neural Style Transfer in Pytorch.
146. [pytorch-dqn](https://github.com/transedward/pytorch-dqn) ⭐ 429 | 🐛 10 | 🌐 Python | 📅 2017-11-01: Deep Q-Learning Network in pytorch.
147. [fast-neural-style](https://github.com/darkstar112358/fast-neural-style) ⭐ 428 | 🐛 5 | 🌐 Python | 📅 2024-07-25: pytorch implementation of fast-neural-style, The model uses the method described in [Perceptual Losses for Real-Time Style Transfer and Super-Resolution](https://arxiv.org/abs/1603.08155) along with Instance Normalization.
148. [densebody\_pytorch](https://github.com/Lotayou/densebody_pytorch) ⭐ 413 | 🐛 13 | 🌐 Python | 📅 2019-08-26: PyTorch implementation of CloudWalk's recent paper DenseBody.
149. [deformable-convolution-pytorch](https://github.com/1zb/deformable-convolution-pytorch) ⭐ 409 | 🐛 20 | 🌐 Cuda | 📅 2019-02-17: PyTorch implementation of Deformable Convolution.
150. [GradientEpisodicMemory](https://github.com/facebookresearch/GradientEpisodicMemory) ⚠️ Archived: Continuum Learning with GEM: Gradient Episodic Memory. <https://arxiv.org/abs/1706.08840>
151. [NGCN](https://github.com/benedekrozemberczki/MixHop-and-N-GCN) ⭐ 406 | 🐛 1 | 🌐 Python | 📅 2022-11-06: A Higher-Order Graph Convolutional Layer. NeurIPS 2018.
152. [MixHop](https://github.com/benedekrozemberczki/MixHop-and-N-GCN) ⭐ 406 | 🐛 1 | 🌐 Python | 📅 2022-11-06: MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing. ICML 2019.
153. [CoordConv-pytorch](https://github.com/mkocabas/CoordConv-pytorch) ⭐ 403 | 🐛 5 | 🌐 Python | 📅 2018-07-20: Pytorch implementation of CoordConv introduced in 'An intriguing failing of convolutional neural networks and the CoordConv solution' paper. (arxiv.org/pdf/1807.03247.pdf)
154. [deepfloat](https://github.com/facebookresearch/deepfloat) ⚠️ Archived: This repository contains the SystemVerilog RTL, C++, HLS (Intel FPGA OpenCL to wrap RTL code) and Python needed to reproduce the numerical results in "Rethinking floating point for deep learning"
155. [DrQA](https://github.com/hitvoice/DrQA) ⭐ 400 | 🐛 9 | 🌐 Python | 📅 2022-03-26: A pytorch implementation of Reading Wikipedia to Answer Open-Domain Questions.
156. [ARAE](https://github.com/jakezhaojb/ARAE) ⭐ 399 | 🐛 18 | 🌐 Python | 📅 2020-04-11: Code for the paper "Adversarially Regularized Autoencoders for Generating Discrete Structures" by Zhao, Kim, Zhang, Rush and LeCun.
157. [Seg-Uncertainty](https://github.com/layumi/Seg-Uncertainty) ⭐ 397 | 🐛 9 | 🌐 Python | 📅 2025-10-24: Unsupervised Scene Adaptation with Memory Regularization in vivo, In IJCAI 2020.
158. [pytorch-i-revnet](https://github.com/jhjacobsen/pytorch-i-revnet) ⭐ 396 | 🐛 3 | 🌐 Python | 📅 2021-02-16: Pytorch implementation of i-RevNets.
159. [piwise](https://github.com/bodokaiser/piwise) ⭐ 387 | 🐛 17 | 🌐 Python | 📅 2018-12-26: Pixel-wise segmentation on VOC2012 dataset using pytorch.
160. [context\_encoder\_pytorch](https://github.com/BoyuanJiang/context_encoder_pytorch) ⭐ 376 | 🐛 17 | 🌐 Python | 📅 2019-12-20: PyTorch Implement of Context Encoders
161. [APPNP](https://github.com/benedekrozemberczki/APPNP) ⭐ 374 | 🐛 1 | 🌐 Python | 📅 2022-11-06: Combining Neural Networks with Personalized PageRank for Classification on Graphs. ICLR 2019.
162. [TuckER](https://github.com/ibalazevic/TuckER) ⭐ 368 | 🐛 2 | 🌐 Python | 📅 2023-11-16: TuckER: Tensor Factorization for Knowledge Graph Completion.
163. [R2Plus1D-PyTorch](https://github.com/irhumshafkat/R2Plus1D-PyTorch) ⚠️ Archived: PyTorch implementation of the R2Plus1D convolution based ResNet architecture described in the paper "A Closer Look at Spatiotemporal Convolutions for Action Recognition"
164. [pytorch\_RVAE](https://github.com/analvikingur/pytorch_RVAE) ⭐ 358 | 🐛 12 | 🌐 Python | 📅 2017-03-15: Recurrent Variational Autoencoder that generates sequential data implemented in pytorch.
165. [Learning to Communicate with Deep Multi-Agent Reinforcement Learning](https://github.com/minqi/learning-to-communicate-pytorch) ⭐ 357 | 🐛 2 | 🌐 Python | 📅 2019-04-01: pytorch implementation of  Learning to Communicate with Deep Multi-Agent Reinforcement Learning paper.
166. [pytorch-es](https://github.com/atgambardella/pytorch-es) ⭐ 351 | 🐛 5 | 🌐 Python | 📅 2017-09-11: This is a PyTorch implementation of [Evolution Strategies](https://arxiv.org/abs/1703.03864) .
167. [Neural-IMage-Assessment 2](https://github.com/truskovskiyk/nima.pytorch) ⭐ 351 | 🐛 20 | 🌐 Python | 📅 2022-06-21: A PyTorch Implementation of Neural IMage Assessment.
168. [dnc](https://github.com/ixaxaar/pytorch-dnc) ⭐ 350 | 🐛 7 | 🌐 Python | 📅 2026-07-28: Differentiable Neural Computers, for Pytorch
169. [tbd-nets](https://github.com/davidmascharka/tbd-nets) ⭐ 347 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2021-12-07: PyTorch implementation of "Transparency by Design: Closing the Gap Between Performance and Interpretability in Visual Reasoning" arxiv.org/abs/1803.05268
170. [WideResNets](https://github.com/xternalz/WideResNet-pytorch) ⭐ 346 | 🐛 2 | 🌐 Python | 📅 2021-04-29: WideResNets for CIFAR10/100 implemented in PyTorch. This implementation requires less GPU memory than what is required by the official Torch implementation: <https://github.com/szagoruyko/wide-residual-networks> ⭐ 1,315 | 🐛 24 | 🌐 Lua | 📅 2019-08-20 .
171. [QANet-pytorch](https://github.com/hengruo/QANet-pytorch) ⭐ 343 | 🐛 6 | 🌐 Python | 📅 2026-07-28: an implementation of QANet with PyTorch (EM/F1 = 70.5/77.2 after 20 epoches for about 20 hours on one 1080Ti card.)
172. [nmp\_qc](https://github.com/priba/nmp_qc) ⭐ 341 | 🐛 2 | 🌐 Python | 📅 2020-05-05: Neural Message Passing for Computer Vision
173. [pytorch-explain-black-box](https://github.com/jacobgil/pytorch-explain-black-box) ⭐ 335 | 🐛 5 | 🌐 Python | 📅 2021-11-30: PyTorch implementation of Interpretable Explanations of Black Boxes by Meaningful Perturbation
174. [AttentionWalk](https://github.com/benedekrozemberczki/AttentionWalk) ⭐ 326 | 🐛 0 | 🌐 Python | 📅 2022-11-06: This is a Pytorch implementation of Watch Your Step: Learning Node Embeddings via Graph Attention. NIPS 2018.
175. [generative-query-network-pytorch](https://github.com/wohlert/generative-query-network-pytorch) ⭐ 322 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2019-06-24: Generative Query Network (GQN) in PyTorch as described in "Neural Scene Representation and Rendering"
176. [prog\_gans\_pytorch\_inference](https://github.com/ptrblck/prog_gans_pytorch_inference) ⭐ 321 | 🐛 0 | 🌐 Python | 📅 2017-11-04: PyTorch inference for "Progressive Growing of GANs" with CelebA snapshot.
177. [PNASNet.pytorch](https://github.com/chenxi116/PNASNet.pytorch) ⭐ 321 | 🐛 3 | 🌐 Python | 📅 2022-08-04: PyTorch implementation of PNASNet-5 on ImageNet.
178. [Pytorch-NCE](https://github.com/Stonesjtu/Pytorch-NCE) ⭐ 319 | 🐛 3 | 🌐 Python | 📅 2019-11-06: The Noise Contrastive Estimation for softmax output written in Pytorch
179. [pytorch-value-iteration-networks](https://github.com/kentsommer/pytorch-value-iteration-networks) ⭐ 318 | 🐛 1 | 🌐 Python | 📅 2020-10-02: Pytorch implementation of Value Iteration Networks (NIPS 2016 best paper)
180. [PyTorchWavelets](https://github.com/tomrunia/PyTorchWavelets) ⭐ 318 | 🐛 5 | 🌐 Python | 📅 2022-02-03: PyTorch implementation of the wavelet analysis found in Torrence and Compo (1998)
181. [Learning to learn by gradient descent by gradient descent](https://github.com/ikostrikov/pytorch-meta-optimizer) ⭐ 315 | 🐛 6 | 🌐 Python | 📅 2018-08-27: PyTorch implementation of Learning to learn by gradient descent by gradient descent.
182. [EfficientNets-PyTorch](https://github.com/zsef123/EfficientNets-PyTorch) ⭐ 314 | 🐛 5 | 🌐 Python | 📅 2019-12-18: A PyTorch implementation of EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks.
183. [Face\_Attention\_Network](https://github.com/rainofmine/Face_Attention_Network) ⭐ 313 | 🐛 13 | 🌐 Python | 📅 2019-01-12: Pytorch implementation of face attention network as described in Face Attention Network: An Effective Face Detector for the Occluded Faces.
184. [Continuous Deep Q-Learning with Model-based Acceleration ](https://github.com/ikostrikov/pytorch-naf) ⭐ 311 | 🐛 7 | 🌐 Python | 📅 2021-02-16: Reimplementation of Continuous Deep Q-Learning with Model-based Acceleration.
185. [tacotron\_pytorch](https://github.com/r9y9/tacotron_pytorch) ⭐ 309 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2019-07-12:  PyTorch implementation of Tacotron speech synthesis model.
186. [simple-effective-text-matching-pytorch](https://github.com/alibaba-edu/simple-effective-text-matching-pytorch) ⭐ 305 | 🐛 5 | 🌐 Python | 📅 2022-08-24: A pytorch implementation of the ACL2019 paper "Simple and Effective Text Matching with Richer Alignment Features".
187. [RetinaNet](https://github.com/c0nn3r/RetinaNet) ⚠️ Archived: An implementation of RetinaNet in PyTorch.
188. [pytorch-sgns](https://github.com/theeluwin/pytorch-sgns) ⭐ 300 | 🐛 5 | 🌐 Python | 📅 2021-03-21: Skipgram Negative Sampling in PyTorch.
189. [universal-triggers](https://github.com/Eric-Wallace/universal-triggers) ⭐ 300 | 🐛 3 | 🌐 Python | 📅 2024-07-25: Universal Adversarial Triggers for Attacking and Analyzing NLP (EMNLP 2019)
190. [pyscatwave](https://github.com/edouardoyallon/pyscatwave) ⭐ 295 | 🐛 1 | 🌐 Python | 📅 2020-02-22: Fast Scattering Transform with CuPy/PyTorch,read the paper [here](https://arxiv.org/abs/1703.08961)
191. [samplernn-pytorch](https://github.com/deepsound-project/samplernn-pytorch) ⭐ 294 | 🐛 23 | 🌐 Python | 📅 2023-04-07: PyTorch implementation of SampleRNN: An Unconditional End-to-End Neural Audio Generation Model.
192. [ClariNet](https://github.com/ksw0306/ClariNet) ⭐ 293 | 🐛 8 | 🌐 Python | 📅 2019-08-05: A Pytorch Implementation of ClariNet arxiv.org/abs/1807.07281
193. [VRNN](https://github.com/emited/VariationalRecurrentNeuralNetwork) ⭐ 292 | 🐛 7 | 🌐 Python | 📅 2021-12-13: Pytorch implementation of the Variational RNN (VRNN), from A Recurrent Latent Variable Model for Sequential Data.
194. [graph\_convnets\_pytorch](https://github.com/xbresson/graph_convnets_pytorch) ⭐ 290 | 🐛 4 | 🌐 HTML | 📅 2017-10-15: PyTorch implementation of graph ConvNets, NIPS’16
195. [AGE](https://github.com/DmitryUlyanov/AGE) ⭐ 287 | 🐛 6 | 🌐 Python | 📅 2018-06-28: Code for paper "Adversarial Generator-Encoder Networks" by Dmitry Ulyanov, Andrea Vedaldi and Victor Lempitsky which can be found [here](http://sites.skoltech.ru/app/data/uploads/sites/25/2017/04/AGE.pdf)
196. [YellowFin\_Pytorch](https://github.com/JianGoForIt/YellowFin_Pytorch) ⭐ 286 | 🐛 7 | 🌐 Python | 📅 2019-03-24: auto-tuning momentum SGD optimizer
197. [pytorch-dnc](https://github.com/jingweiz/pytorch-dnc) ⭐ 279 | 🐛 1 | 🌐 Python | 📅 2018-02-20: Neural Turing Machine (NTM) & Differentiable Neural Computer (DNC) with pytorch & visdom.
198. [SGCN](https://github.com/benedekrozemberczki/SGCN) ⭐ 277 | 🐛 1 | 🌐 Python | 📅 2023-03-18: This is a Pytorch implementation of Signed Graph Convolutional Network. ICDM 2018.
199. [GAM](https://github.com/benedekrozemberczki/GAM) ⭐ 276 | 🐛 1 | 🌐 Python | 📅 2022-11-06: This is a Pytorch implementation of Graph Classification using Structural Attention. KDD 2018.
200. [nonauto-nmt](https://github.com/salesforce/nonauto-nmt) ⚠️ Archived: PyTorch Implementation of "Non-Autoregressive Neural Machine Translation"
201. [PyramidNet-PyTorch](https://github.com/dyhan0920/PyramidNet-PyTorch) ⭐ 270 | 🐛 0 | 🌐 Python | 📅 2020-07-05: A PyTorch implementation for PyramidNets (Deep Pyramidal Residual Networks, arxiv.org/abs/1610.02915)
202. [FewShotLearning](https://github.com/gitabcworld/FewShotLearning) ⭐ 265 | 🐛 9 | 🌐 Python | 📅 2017-09-22: Pytorch implementation of the paper "Optimization as a Model for Few-Shot Learning"
203. [Character CNN](https://github.com/ahmedbesbes/character-based-cnn) ⭐ 262 | 🐛 8 | 🌐 Python | 📅 2021-04-28: PyTorch implementation of the Character-level Convolutional Networks for Text Classification paper.
204. [ewc.pytorch](https://github.com/moskomule/ewc.pytorch) ⚠️ Archived: An implementation of Elastic Weight Consolidation (EWC), proposed in James Kirkpatrick et al. Overcoming catastrophic forgetting in neural networks 2016(10.1073/pnas.1611835114).
205. [BEGAN-pytorch](https://github.com/carpedm20/BEGAN-pytorch) ⭐ 258 | 🐛 6 | 🌐 Python | 📅 2017-04-07: PyTorch implementation of [BEGAN](https://arxiv.org/abs/1703.10717): Boundary Equilibrium Generative Adversarial Networks.
206. [pytorch\_compact\_bilinear\_pooling v1](https://github.com/gdlg/pytorch_compact_bilinear_pooling) ⭐ 254 | 🐛 6 | 🌐 Python | 📅 2022-07-06: This repository has a pure Python implementation of Compact Bilinear Pooling and Count Sketch for PyTorch.
207. [LearningToCompare-Pytorch](https://github.com/dragen1860/LearningToCompare-Pytorch) ⭐ 251 | 🐛 2 | 🌐 Python | 📅 2018-02-15: Pytorch Implementation for Paper: Learning to Compare: Relation Network for Few-Shot Learning.
208. [relational-rnn-pytorch](https://github.com/L0SG/relational-rnn-pytorch) ⭐ 246 | 🐛 1 | 🌐 Python | 📅 2018-12-27: An implementation of DeepMind's Relational Recurrent Neural Networks in PyTorch.
209. [packnet](https://github.com/arunmallya/packnet) ⭐ 244 | 🐛 3 | 🌐 Python | 📅 2018-10-07: Code for PackNet: Adding Multiple Tasks to a Single Network by Iterative Pruning arxiv.org/abs/1711.05769
210. [pytorch-transformer](https://github.com/leviswind/pytorch-transformer) ⭐ 240 | 🐛 7 | 🌐 Python | 📅 2021-06-16: pytorch implementation of Attention is all you need.
211. [DeepCORAL](https://github.com/SSARCandy/DeepCORAL) ⭐ 237 | 🐛 6 | 🌐 Python | 📅 2021-04-22: A PyTorch implementation of 'Deep CORAL: Correlation Alignment for Deep Domain Adaptation.', ECCV 2016
212. [DeepRL-Grounding](https://github.com/devendrachaplot/DeepRL-Grounding) ⭐ 237 | 🐛 2 | 🌐 Python | 📅 2018-04-16: This is a PyTorch implementation of the AAAI-18 paper Gated-Attention Architectures for Task-Oriented Language Grounding
213. [SFD\_pytorch](https://github.com/clcarwin/SFD_pytorch) ⭐ 232 | 🐛 13 | 🌐 Python | 📅 2019-10-28: A PyTorch Implementation of Single Shot Scale-invariant Face Detector.
214. [e2e-model-learning](https://github.com/locuslab/e2e-model-learning) ⭐ 225 | 🐛 2 | 🌐 Python | 📅 2020-11-29: Task-based end-to-end model learning.
215. [deep\_image\_prior](https://github.com/atiyo/deep_image_prior) ⭐ 224 | 🐛 0 | 🌐 Python | 📅 2020-02-11: An implementation of image reconstruction methods from Deep Image Prior (Ulyanov et al., 2017) in PyTorch.
216. [HCN-pytorch](https://github.com/huguyuehuhu/HCN-pytorch) ⭐ 224 | 🐛 14 | 🌐 Python | 📅 2022-11-22: A pytorch reimplementation of { Co-occurrence Feature Learning from Skeleton Data for Action Recognition and Detection with Hierarchical Aggregation }.
217. [VIN\_PyTorch\_Visdom](https://github.com/zuoxingdong/VIN_PyTorch_Visdom) ⭐ 223 | 🐛 3 | 🌐 Python | 📅 2017-03-29: PyTorch implementation of Value Iteration Networks (VIN): Clean, Simple and Modular. Visualization in Visdom.
218. [DiffAI](https://github.com/eth-sri/diffai) ⭐ 221 | 🐛 2 | 🌐 Python | 📅 2024-07-25: A provable defense against adversarial examples and library for building compatible PyTorch models.
219. [ORN](https://github.com/ZhouYanzhao/ORN) ⭐ 216 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2022-07-17: A PyTorch implementation of the paper "Oriented Response Networks" in CVPR 2017.
220. [AccSGD](https://github.com/rahulkidambi/AccSGD) ⭐ 216 | 🐛 1 | 🌐 Python | 📅 2018-03-10: Implements pytorch code for the Accelerated SGD algorithm.
221. [adversarial-patch](https://github.com/jhayes14/adversarial-patch) ⭐ 215 | 🐛 3 | 🌐 Python | 📅 2022-03-09: PyTorch implementation of adversarial patch.
222. [DCC](https://github.com/shahsohil/DCC) ⭐ 214 | 🐛 8 | 🌐 Python | 📅 2021-07-14: This repository contains the source code and data for reproducing results of Deep Continuous Clustering paper.
223. [Splitter](https://github.com/benedekrozemberczki/Splitter) ⭐ 214 | 🐛 1 | 🌐 Python | 📅 2023-06-06: Splitter: Learning Node Representations that Capture Multiple Social Contexts. (WWW 2019).
224. [FreezeOut](https://github.com/ajbrock/FreezeOut) ⭐ 213 | 🐛 7 | 🌐 Python | 📅 2018-08-15: Accelerate Neural Net Training by Progressively Freezing Layers.
225. [pt-dilate-rnn](https://github.com/zalandoresearch/pt-dilate-rnn) ⭐ 213 | 🐛 2 | 🌐 Python | 📅 2019-06-24: Dilated RNNs in pytorch.
226. [SEAL-CI](https://github.com/benedekrozemberczki/SEAL-CI) ⭐ 212 | 🐛 0 | 🌐 Python | 📅 2022-11-06 Semi-Supervised Graph Classification: A Hierarchical Graph Perspective. (WWW 2019).
227. [DGC-Net](https://github.com/AaltoVision/DGC-Net) ⭐ 206 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2021-10-12: A PyTorch implementation of "DGC-Net: Dense Geometric Correspondence Network".
228. [torch\_waveglow](https://github.com/npuichigo/waveglow) ⭐ 205 | 🐛 2 | 🌐 Python | 📅 2018-11-06: A PyTorch implementation of the WaveGlow: A Flow-based Generative Network for Speech Synthesis.
229. [pytorch-zssr](https://github.com/jacobgil/pytorch-zssr) ⭐ 203 | 🐛 6 | 🌐 Python | 📅 2018-01-10: PyTorch implementation of 1712.06087 "Zero-Shot" Super-Resolution using Deep Internal Learning
230. [odin-pytorch](https://github.com/ShiyuLiang/odin-pytorch) ⭐ 200 | 🐛 4 | 🌐 Python | 📅 2017-06-28: Principled Detection of Out-of-Distribution Examples in Neural Networks.
231. [transducer](https://github.com/awni/transducer) ⭐ 200 | 🐛 4 | 🌐 C++ | 📅 2022-09-20: A Fast Sequence Transducer Implementation with PyTorch Bindings.
232. [SVHNClassifier](https://github.com/potterhsu/SVHNClassifier-PyTorch) ⭐ 199 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2021-04-26: A PyTorch implementation of [Multi-digit Number Recognition from Street View Imagery using Deep Convolutional Neural Networks](https://arxiv.org/pdf/1312.6082.pdf).
233. [deep-forecast-pytorch](https://github.com/Wizaron/deep-forecast-pytorch) ⭐ 196 | 🐛 0 | 🌐 Python | 📅 2018-01-14: Wind Speed Prediction using LSTMs in PyTorch (arxiv.org/pdf/1707.08110.pdf)
234. [DRRN-pytorch](https://github.com/jt827859032/DRRN-pytorch) ⭐ 195 | 🐛 16 | 🌐 Python | 📅 2018-06-20: An implementation of Deep Recursive Residual Network for Super Resolution (DRRN), CVPR 2017
235. [skip-gram-pytorch](https://github.com/fanglanting/skip-gram-pytorch) ⭐ 191 | 🐛 4 | 🌐 Python | 📅 2017-10-23: A complete pytorch implementation of skipgram model (with subsampling and negative sampling). The embedding result is tested with Spearman's rank correlation.
236. [Pytorch-Sketch-RNN](https://github.com/alexis-jacq/Pytorch-Sketch-RNN) ⭐ 190 | 🐛 7 | 🌐 Python | 📅 2019-03-20: a pytorch implementation of arxiv.org/abs/1704.03477
237. [integrated-gradient-pytorch](https://github.com/TianhongDai/integrated-gradient-pytorch) ⭐ 190 | 🐛 2 | 🌐 Python | 📅 2022-03-25: This is the pytorch implementation of the paper - Axiomatic Attribution for Deep Networks.
238. [OpenFacePytorch](https://github.com/thnkim/OpenFacePytorch) ⭐ 189 | 🐛 5 | 🌐 Python | 📅 2020-02-20: PyTorch module to use OpenFace's nn4.small2.v1.t7 model
239. [CompactBilinearPooling-Pytorch v2](https://github.com/DeepInsight-PCALab/CompactBilinearPooling-Pytorch) ⭐ 187 | 🐛 4 | 🌐 Python | 📅 2021-08-13: (Yang Gao, et al.) A Pytorch Implementation for Compact Bilinear Pooling.
240. [distance-encoding](https://github.com/snap-stanford/distance-encoding) ⭐ 187 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2021-03-20: Distance-Encoding - Design Provably More PowerfulGNNs for Structural Representation Learning.
241. [Deep-Image-Analogy-PyTorch](https://github.com/Ben-Louis/Deep-Image-Analogy-PyTorch) ⭐ 186 | 🐛 4 | 🌐 Python | 📅 2021-12-11: A python implementation of Deep-Image-Analogy based on pytorch.
242. [Pytorch-DPPO](https://github.com/alexis-jacq/Pytorch-DPPO) ⭐ 184 | 🐛 5 | 🌐 Python | 📅 2018-03-25: Pytorch implementation of Distributed Proximal Policy Optimization: arxiv.org/abs/1707.02286
243. [convnet-aig](https://github.com/andreasveit/convnet-aig) ⭐ 184 | 🐛 7 | 🌐 Python | 📅 2018-11-15: PyTorch implementation for Convolutional Networks with Adaptive Inference Graphs.
244. [piggyback](https://github.com/arunmallya/piggyback) ⭐ 183 | 🐛 2 | 🌐 Python | 📅 2019-05-02: Code for Piggyback: Adapting a Single Network to Multiple Tasks by Learning to Mask Weights arxiv.org/abs/1801.06519
245. [GAN-weight-norm](https://github.com/stormraiser/GAN-weight-norm) ⭐ 181 | 🐛 3 | 🌐 Lua | 📅 2018-01-15: Code for "On the Effects of Batch and Weight Normalization in Generative Adversarial Networks"
246. [Semantic Search](https://github.com/kuutsav/information-retrieval) ⚠️ Archived: Latest in the field of neural information retrieval / semantic search.
247. [fmpytorch](https://github.com/jmhessel/fmpytorch) ⭐ 173 | 🐛 0 | 🌐 Python | 📅 2018-03-12: A PyTorch implementation of a Factorization Machine module in cython.
248. [pytorch-sift](https://github.com/ducha-aiki/pytorch-sift) ⭐ 173 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-08-22: PyTorch implementation of SIFT descriptor.
249. [pytorch-smoothgrad](https://github.com/pkdn/pytorch-smoothgrad) ⭐ 169 | 🐛 3 | 🌐 Python | 📅 2021-04-04: SmoothGrad implementation in PyTorch
250. [pytorch-retraining](https://github.com/ahirner/pytorch-retraining) ⭐ 168 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2020-09-20: Transfer Learning Shootout for PyTorch's model zoo (torchvision)
251. [visual-interaction-networks-pytorch](https://github.com/Mrgemy95/visual-interaction-networks-pytorch) ⭐ 165 | 🐛 2 | 🌐 Python | 📅 2018-02-02: This's an implementation of deepmind Visual Interaction Networks paper using pytorch
252. [vqa-winner-cvprw-2017](https://github.com/markdtw/vqa-winner-cvprw-2017) ⭐ 163 | 🐛 4 | 🌐 Python | 📅 2019-02-08: Pytorch Implementation of winner from VQA Chllange Workshop in CVPR'17.
253. [pytorch-pose-estimation](https://github.com/DavexPro/pytorch-pose-estimation) ⭐ 159 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2017-12-26: PyTorch Implementation of Realtime Multi-Person Pose Estimation project.
254. [FCN-pytorch-easiest](https://github.com/yunlongdong/FCN-pytorch-easiest) ⭐ 159 | 🐛 6 | 🌐 Python | 📅 2018-12-23: trying to be the most easiest and just get-to-use pytorch implementation of FCN (Fully Convolotional Networks)
255. [pytorch-seq2seq-intent-parsing](https://github.com/spro/pytorch-seq2seq-intent-parsing) ⭐ 156 | 🐛 5 | 🌐 Python | 📅 2017-06-08: Intent parsing and slot filling in PyTorch with seq2seq + attention
256. [bigBatch](https://github.com/eladhoffer/bigBatch) ⭐ 148 | 🐛 3 | 🌐 Python | 📅 2017-05-25: Code used to generate the results appearing in "Train longer, generalize better: closing the generalization gap in large batch training of neural networks"
257. [Aspect-level-sentiment](https://github.com/ruidan/Aspect-level-sentiment) ⭐ 148 | 🐛 3 | 🌐 Python | 📅 2018-06-22: Code and dataset for ACL2018 paper "Exploiting Document Knowledge for Aspect-level Sentiment Classification"
258. [StackNN](https://github.com/viking-sudo-rm/StackNN) ⭐ 145 | 🐛 1 | 🌐 Python | 📅 2019-10-07: A PyTorch implementation of differentiable stacks for use in neural networks.
259. [Semantic Image Synthesis via Adversarial Learning](https://github.com/woozzu/dong_iccv_2017) ⭐ 141 | 🐛 8 | 🌐 Python | 📅 2017-08-24: A PyTorch implementation of the paper "Semantic Image Synthesis via Adversarial Learning" in ICCV 2017.
260. [deep-auto-punctuation](https://github.com/episodeyang/deep-auto-punctuation) ⭐ 139 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2020-11-15: a pytorch implementation of auto-punctuation learned character by character.
261. [pytorch-prunes](https://github.com/BayesWatch/pytorch-prunes) ⭐ 139 | 🐛 1 | 🌐 Python | 📅 2019-08-28: Pruning neural networks: is it time to nip it in the bud?
262. [interaction\_network\_pytorch](https://github.com/higgsfield/interaction_network_pytorch) ⭐ 138 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2017-12-27: Pytorch Implementation of Interaction Networks for Learning about Objects, Relations and Physics.
263. [neural style transfer](https://github.com/alexis-jacq/Pytorch-Tutorials) ⭐ 136 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2018-11-05: An introduction to PyTorch through the Neural-Style algorithm (<https://arxiv.org/abs/1508.06576>) developed by Leon A. Gatys, Alexander S. Ecker and Matthias Bethge.
264. [bandit-nmt](https://github.com/khanhptnk/bandit-nmt) ⭐ 134 | 🐛 0 | 🌐 Python | 📅 2018-03-11: This is code repo for our EMNLP 2017 paper "Reinforcement Learning for Bandit Neural Machine Translation with Simulated Human Feedback", which implements the A2C algorithm on top of a neural encoder-decoder model and benchmarks the combination under simulated noisy rewards.
265. [radio-transformer-networks](https://github.com/gram-ai/radio-transformer-networks) ⭐ 132 | 🐛 1 | 🌐 Python | 📅 2017-11-05: A PyTorch implementation of Radio Transformer Networks from the paper "An Introduction to Deep Learning for the Physical Layer". arxiv.org/abs/1702.00832
266. [doomnet](https://github.com/akolishchak/doom-net-pytorch) ⭐ 131 | 🐛 0 | 🌐 Python | 📅 2022-03-09: PyTorch's version of Doom-net implementing some RL models in ViZDoom environment.
267. [famos](https://github.com/zalandoresearch/famos) ⭐ 130 | 🐛 1 | 🌐 Python | 📅 2019-02-21:
     Pytorch implementation of the paper "Copy the Old or Paint Anew? An Adversarial Framework for (non-) Parametric Image Stylization" available at <http://arxiv.org/abs/1811.09236>.
268. [captionGen](https://github.com/eladhoffer/captionGen) ⭐ 127 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2017-03-08: Generate captions for an image using PyTorch.
269. [binary-wide-resnet](https://github.com/szagoruyko/binary-wide-resnet) ⭐ 126 | 🐛 2 | 🌐 Python | 📅 2018-09-06: PyTorch implementation of Wide Residual Networks with 1-bit weights by McDonnel (ICLR 2018)
270. [mixup\_pytorch](https://github.com/leehomyc/mixup_pytorch) ⭐ 124 | 🐛 2 | 🌐 Python | 📅 2018-01-08: A PyTorch implementation of the paper Mixup: Beyond Empirical Risk Minimization in PyTorch.
271. [pytorch\_NEG\_loss](https://github.com/analvikingur/pytorch_NEG_loss) ⭐ 123 | 🐛 1 | 🌐 Python | 📅 2017-07-07: NEG loss implemented in pytorch.
272. [DepthNet](https://github.com/ClementPinard/DepthNet) ⭐ 123 | 🐛 1 | 🌐 Python | 📅 2019-07-24: PyTorch DepthNet Training on Still Box dataset.
273. [PyTorch\_GBW\_LM](https://github.com/rdspring1/PyTorch_GBW_LM) ⭐ 123 | 🐛 2 | 🌐 Python | 📅 2019-08-22: PyTorch Language Model for Google Billion Word Dataset.
274. [NoisyNaturalGradient](https://github.com/wlwkgus/NoisyNaturalGradient) ⭐ 122 | 🐛 3 | 🌐 Python | 📅 2018-09-01: Pytorch Implementation of paper "Noisy Natural Gradient as Variational Inference".
275. [minimal\_glo](https://github.com/tneumann/minimal_glo) ⭐ 121 | 🐛 1 | 🌐 Python | 📅 2018-01-19: Minimal PyTorch implementation of Generative Latent Optimization from the paper "Optimizing the Latent Space of Generative Networks"
276. [SRDenseNet-pytorch](https://github.com/wxywhu/SRDenseNet-pytorch) ⭐ 121 | 🐛 9 | 🌐 Python | 📅 2018-10-20: SRDenseNet-pytorch（ICCV\_2017）
277. [dni](https://github.com/andrewliao11/dni.pytorch) ⭐ 119 | 🐛 3 | 🌐 Python | 📅 2017-10-19: Implement Decoupled Neural Interfaces using Synthetic Gradients in Pytorch
278. [pytorch\_image\_classifier](https://github.com/jinfagang/pytorch_image_classifier) ⭐ 116 | 🐛 4 | 🌐 Python | 📅 2020-10-01: Minimal But Practical Image Classifier Pipline Using Pytorch, Finetune on ResNet18, Got 99% Accuracy on Own Small Datasets.
279. [A3C-PyTorch](https://github.com/onlytailei/A3C-PyTorch) ⭐ 113 | 🐛 1 | 🌐 Python | 📅 2017-04-03:PyTorch implementation of Advantage async actor-critic Algorithms (A3C) in PyTorch
280. [EigenDamage-Pytorch](https://github.com/alecwangcq/EigenDamage-Pytorch) ⭐ 113 | 🐛 1 | 🌐 Python | 📅 2020-03-03: Official implementation of the ICML'19 paper "EigenDamage: Structured Pruning in the Kronecker-Factored Eigenbasis".
281. [meProp](https://github.com/jklj077/meProp) ⭐ 111 | 🐛 3 | 🌐 C# | 📅 2022-03-29: Codes for "meProp: Sparsified Back Propagation for Accelerated Deep Learning with Reduced Overfitting".
282. [back2future.pytorch](https://github.com/anuragranj/back2future.pytorch) ⭐ 111 | 🐛 2 | 🌐 Python | 📅 2019-11-07: This is a Pytorch implementation of
     Janai, J., Güney, F., Ranjan, A., Black, M. and Geiger, A., Unsupervised Learning of Multi-Frame Optical Flow with Occlusions. ECCV 2018.
283. [nmn-pytorch](https://github.com/HarshTrivedi/nmn-pytorch) ⭐ 107 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-12-16: Neural Module Network for VQA in Pytorch.
284. [NVIDIA/unsupervised-video-interpolation](https://github.com/NVIDIA/unsupervised-video-interpolation) ⭐ 107 | 🐛 7 | 🌐 Python | 📅 2020-01-31: A PyTorch Implementation of [Unsupervised Video Interpolation Using Cycle Consistency](https://arxiv.org/abs/1906.05928), In ICCV 2019.
285. [lang-emerge-parlai](https://github.com/karandesai-96/lang-emerge-parlai) ⭐ 104 | 🐛 0 | 🌐 Python | 📅 2019-04-02: Implementation of EMNLP 2017 Paper "Natural Language Does Not Emerge 'Naturally' in Multi-Agent Dialog" using PyTorch and ParlAI
286. [deep-dream-in-pytorch](https://github.com/duc0/deep-dream-in-pytorch) ⭐ 102 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-12-21: Pytorch implementation of the DeepDream computer vision algorithm.
287. [LOLA\_DiCE](https://github.com/alexis-jacq/LOLA_DiCE) ⭐ 98 | 🐛 4 | 🌐 Python | 📅 2018-08-21: Pytorch implementation of LOLA (arxiv.org/abs/1709.04326) using DiCE (arxiv.org/abs/1802.05098)
288. [quantile-regression-dqn-pytorch](https://github.com/ars-ashuha/quantile-regression-dqn-pytorch) ⭐ 97 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2020-09-03: Quantile Regression DQN a Minimal Working Example
289. [biogans](https://github.com/aosokin/biogans) ⭐ 96 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-11-27:  Implementation supporting the ICCV 2017 paper "GANs for Biological Image Synthesis".
290. [Categorical DQN](https://github.com/floringogianu/categorical-dqn) ⭐ 95 | 🐛 0 | 🌐 Python | 📅 2018-04-07: A PyTorch Implementation of Categorical DQN from [A Distributional Perspective on Reinforcement Learning](https://arxiv.org/abs/1707.06887).
291. [molencoder](https://github.com/cxhernandez/molencoder) ⭐ 93 | 🐛 4 | 🌐 Python | 📅 2026-01-16: Molecular AutoEncoder in PyTorch
292. [vae\_vpflows](https://github.com/jmtomczak/vae_vpflows) ⭐ 92 | 🐛 1 | 🌐 Python | 📅 2017-06-14: Code in PyTorch for the convex combination linear IAF and the Householder Flow, J.M. Tomczak & M. Welling <https://jmtomczak.github.io/deebmed.html>
293. [vae\_vpflows](https://github.com/jmtomczak/vae_vpflows) ⭐ 92 | 🐛 1 | 🌐 Python | 📅 2017-06-14:Code in PyTorch for the convex combination linear IAF and the Householder Flow, J.M. Tomczak & M. Welling jmtomczak.github.io/deebmed.html
294. [pytorch-NeuCom](https://github.com/ypxie/pytorch-NeuCom) ⭐ 91 | 🐛 3 | 🌐 Python | 📅 2017-12-04: Pytorch implementation of DeepMind's differentiable neural computer paper.
295. [sqeezenet](https://github.com/gsp-27/pytorch_Squeezenet) ⭐ 91 | 🐛 1 | 🌐 Python | 📅 2020-05-18: Implementation of Squeezenet in pytorch, #### pretrained models on CIFAR10 data to come Plan to train the model on cifar 10 and add block connections too.
296. [Visual-Feature-Attribution-Using-Wasserstein-GANs-Pytorch](https://github.com/orobix/Visual-Feature-Attribution-Using-Wasserstein-GANs-Pytorch) ⭐ 91 | 🐛 2 | 🌐 Python | 📅 2023-05-31: Implementation of Visual Feature Attribution using Wasserstein GANs (arxiv.org/abs/1711.08998) in PyTorch.
297. [ppo\_pytorch\_cpp](https://github.com/mhubii/ppo_pytorch_cpp) ⭐ 90 | 🐛 1 | 🌐 C++ | 📅 2022-09-01: This is an implementation of the proximal policy optimization algorithm for the C++ API of Pytorch.
298. [translagent](https://github.com/facebookresearch/translagent) ⚠️ Archived: Code for Emergent Translation in Multi-Agent Communication.
299. [Fast Neural Style for Image Style Transform by Pytorch](https://github.com/bengxy/FastNeuralStyle) ⭐ 81 | 🐛 1 | 🌐 Python | 📅 2022-01-24: Fast Neural Style for Image Style Transform by Pytorch .
300. [FFTNet](https://github.com/mozilla/FFTNet) ⭐ 81 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2018-09-28: Unofficial Implementation of FFTNet vocode paper.
301. [scalingscattering](https://github.com/edouardoyallon/scalingscattering) ⭐ 80 | 🐛 3 | 🌐 Python | 📅 2017-10-19: Scaling The Scattering Transform : Deep Hybrid Networks.
302. [PyTorch-value-iteration-networks](https://github.com/onlytailei/PyTorch-value-iteration-networks) ⭐ 80 | 🐛 0 | 🌐 Python | 📅 2017-03-13: PyTorch implementation of the Value Iteration Networks (NIPS '16) paper
303. [pytorch\_TDNN](https://github.com/analvikingur/pytorch_TDNN) ⭐ 80 | 🐛 1 | 🌐 Python | 📅 2017-03-27: Time Delayed NN implemented in pytorch.
304. [pytorch\_Highway](https://github.com/analvikingur/pytorch_Highway) ⭐ 79 | 🐛 1 | 🌐 Python | 📅 2017-03-27: Highway network implemented in pytorch.
305. [shampoo.pytorch](https://github.com/moskomule/shampoo.pytorch) ⚠️ Archived: An implementation of shampoo.
306. [EPSR](https://github.com/subeeshvasu/2018_subeesh_epsr_eccvw) ⭐ 79 | 🐛 0 | 🌐 Python | 📅 2020-07-14: Pytorch implementation of [Analyzing Perception-Distortion Tradeoff using Enhanced Perceptual Super-resolution Network](https://arxiv.org/pdf/1811.00344.pdf). This work has won the first place in PIRM2018-SR competition (region 1) held as part of the ECCV 2018.
307. [MalConv-Pytorch](https://github.com/Alexander-H-Liu/MalConv-Pytorch) ⭐ 72 | 🐛 9 | 🌐 Python | 📅 2022-02-01: Pytorch implementation of MalConv.
308. [SINE](https://github.com/benedekrozemberczki/SINE) ⭐ 71 | 🐛 0 | 🌐 Python | 📅 2023-03-18: This is a Pytorch implementation of SINE: Scalable Incomplete Network Embedding. ICDM 2018.
309. [nninit](https://github.com/alykhantejani/nninit) ⭐ 70 | 🐛 0 | 🌐 Python | 📅 2017-03-02: Weight initialization schemes for PyTorch nn.Modules. This is a port of the popular nninit for Torch7 by @kaixhin.
310. [forward-thinking-pytorch](https://github.com/kimhc6028/forward-thinking-pytorch) ⭐ 65 | 🐛 0 | 🌐 Python | 📅 2017-06-14: Pytorch implementation of "Forward Thinking: Building and Training Neural Networks One Layer at a Time" <https://arxiv.org/pdf/1706.02480.pdf>
311. [PhotographicImageSynthesiswithCascadedRefinementNetworks-Pytorch](https://github.com/Blade6570/PhotographicImageSynthesiswithCascadedRefinementNetworks-Pytorch) ⭐ 63 | 🐛 1 | 🌐 Python | 📅 2018-02-14: Photographic Image Synthesis with Cascaded Refinement Networks - Pytorch Implementation
312. [pytorch\_hmax](https://github.com/wmvanvliet/pytorch_hmax) ⭐ 62 | 🐛 0 | 🌐 Python | 📅 2023-05-26: Implementation of the HMAX model of vision in PyTorch.
313. [Adaptive-segmentation-mask-attack (ASMA)](https://github.com/utkuozbulak/adaptive-segmentation-mask-attack) ⭐ 60 | 🐛 0 | 🌐 Python | 📅 2020-07-06: A pytorch implementation of the MICCAI2019 paper "Impact of Adversarial Examples on Deep Learning Models for Biomedical Image Segmentation".
314. [flow](https://github.com/emited/flow) ⭐ 59 | 🐛 3 | 🌐 Python | 📅 2019-04-25: Pytorch implementation of ICLR 2018 paper Deep Learning for Physical Processes: Integrating Prior Scientific Knowledge.
315. [Pathfinder Discovery Networks](https://github.com/benedekrozemberczki/PDN) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2025-12-28: Pathfinder Discovery Networks for Neural Message Passing.
316. [binary-stochastic-neurons](https://github.com/Wizaron/binary-stochastic-neurons) ⭐ 57 | 🐛 0 | 🌐 Python | 📅 2018-01-06: Binary Stochastic Neurons in PyTorch.
317. [pnn.pytorch](https://github.com/michaelklachko/pnn.pytorch) ⭐ 57 | 🐛 0 | 🌐 Python | 📅 2018-10-08: PyTorch implementation of CVPR'18 - Perturbative Neural Networks <http://xujuefei.com/pnn.html>.
318. [pytorch\_highway\_networks](https://github.com/c0nn3r/pytorch_highway_networks) ⚠️ Archived: Highway networks implemented in PyTorch.
319. [google\_evolution](https://github.com/neuralix/google_evolution) ⭐ 52 | 🐛 0 | 🌐 Python | 📅 2017-03-23: This implements one of result networks from Large-scale evolution of image classifiers by Esteban Real, et. al.
320. [cat-net](https://github.com/utiasSTARS/cat-net) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2019-09-27:  Canonical Appearance Transformations
321. [fluidnet\_cxx](https://github.com/jolibrain/fluidnet_cxx) ⭐ 52 | 🐛 1 | 🌐 C++ | 📅 2019-06-17: FluidNet re-written with ATen tensor lib.
322. [Deep-Leafsnap](https://github.com/sujithv28/Deep-Leafsnap) ⭐ 50 | 🐛 3 | 🌐 Python | 📅 2017-11-05: LeafSnap replicated using deep neural networks to test accuracy compared to traditional computer vision methods.
323. [psmm](https://github.com/elanmart/psmm) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2018-04-26: imlementation of the the Pointer Sentinel Mixture Model, as described in the paper by Stephen Merity et al.
324. [bytenet](https://github.com/kefirski/bytenet) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2017-12-19: Pytorch implementation of bytenet from "Neural Machine Translation in Linear Time" paper
325. [reseg-pytorch](https://github.com/Wizaron/reseg-pytorch) ⭐ 46 | 🐛 1 | 🌐 Python | 📅 2018-01-17: PyTorch Implementation of ReSeg (arxiv.org/pdf/1511.07053.pdf)
326. [pyTorch\_NCE](https://github.com/demelin/pyTorch_NCE) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2019-08-13: An implementation of the Noise Contrastive Estimation algorithm for pyTorch. Working, yet not very efficient.
327. [e2c-pytorch](https://github.com/ethanluoyc/e2c-pytorch) ⭐ 43 | 🐛 1 | 🌐 Python | 📅 2017-07-05: Embed to Control implementation in PyTorch.
328. [proxprop](https://github.com/tfrerix/proxprop) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2019-03-17: Proximal Backpropagation - a neural network training algorithm that takes implicit instead of explicit gradient steps.
329. [AVO-pytorch](https://github.com/artix41/AVO-pytorch) ⭐ 42 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-08-07: Implementation of Adversarial Variational Optimization in PyTorch.
330. [associative\_compression\_networks](https://github.com/jalexvig/associative_compression_networks) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2018-07-25: Associative Compression Networks for Representation Learning.
331. [MagNet](https://github.com/matthew-hirn/magnet) ⭐ 40 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-01-08: Official implementation of the NeurIPS2021 paper "MagNet: A Neural Network for Directed Graphs".
332. [Asynchronous Advantage Actor-Critic in PyTorch](https://github.com/rarilurelo/pytorch_a3c) ⭐ 38 | 🐛 3 | 🌐 Python | 📅 2017-03-06: This is PyTorch implementation of A3C as described in Asynchronous Methods for Deep Reinforcement Learning. Since PyTorch has a easy method to control shared memory within multiprocess, we can easily implement asynchronous method like A3C.
333. [AEGeAN](https://github.com/tymokvo/AEGeAN) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2024-03-20: Deeper DCGAN with AE stabilization
334. [eve.pytorch](https://github.com/moskomule/eve.pytorch) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2021-11-01: An implementation of Eve Optimizer, proposed in Imploving Stochastic Gradient Descent with Feedback, Koushik and Hayashi, 2016.
335. [zalando-pytorch](https://github.com/baldassarreFe/zalando-pytorch) ⭐ 31 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-09-28: Various experiments on the [Fashion-MNIST](zalandoresearch/fashion-mnist) dataset from Zalando.
336. [OrthNet](https://github.com/Orcuslc/OrthNet) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2018-04-27: TensorFlow and PyTorch layers for generating Orthogonal Polynomials.
337. [poisson-convolution-sum](https://github.com/cranmer/poisson-convolution-sum) ⭐ 27 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-08-22: Implements an infinite sum of poisson-weighted convolutions
338. [lgamma](https://github.com/rachtsingh/lgamma) ⭐ 25 | 🐛 2 | 🌐 C | 📅 2017-07-08: Implementations of polygamma, lgamma, and beta functions for PyTorch
339. [SSSNET](https://github.com/SherylHYX/SSSNET_Signed_Clustering) ⭐ 24 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-10-13: Official implementation of the SDM2022 paper "SSSNET: Semi-Supervised Signed Network Clustering".
340. [SDPoint](https://github.com/xternalz/SDPoint) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2019-11-05: Implementation of "Stochastic Downsampling for Cost-Adjustable Inference and Improved Regularization in Convolutional Networks", published in CVPR 2018.
341. [Zero-shot Intent CapsNet](https://github.com/joel-huang/zeroshot-capsnet-pytorch) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2019-04-16: GPU-accelerated PyTorch implementation of "Zero-shot User Intent Detection via Capsule Neural Networks".
342. [FreeGrad](https://github.com/tbox98/FreeGrad) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-11-30 - PyTorch library for custom backward passes, straight-through estimators and gradient transforms.
343. [pytorch-nec](https://github.com/mjacar/pytorch-nec) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2024-01-12: PyTorch Implementation of Neural Episodic Control (NEC)
344. [pytorch-yolo2](https://github.com/marvis/pytorch-yolo2): pytorch-yolo2
345. [pytorch-trpo](https://github.com/mjacar/pytorch-trpo): PyTorch Implementation of Trust Region Policy Optimization (TRPO)
346. [mask\_rcnn\_pytorch](https://github.com/felixgwu/mask_rcnn_pytorch): Mask RCNN in PyTorch.
347. [NALU-pytorch](https://github.com/kevinzakka/NALU-pytorch): Basic pytorch implementation of NAC/NALU from Neural Arithmetic Logic Units arxiv.org/pdf/1808.00508.pdf

## Talks & conferences

1. [PyTorch Conference 2018](https://developers.facebook.com/videos/2018/pytorch-developer-conference/): First PyTorch developer conference at 2018.

## Pytorch elsewhere

1. **[the-incredible-pytorch](https://github.com/ritchieng/the-incredible-pytorch) ⭐ 12,617 | 🐛 3 | 📅 2026-07-22**: The Incredible PyTorch: a curated list of tutorials, papers, projects, communities and more relating to PyTorch.
2. [pytorch notebook: docker-stack](https://hub.docker.com/r/escong/pytorch-notebook/): A project similar to [Jupyter Notebook Scientific Python Stack](https://github.com/jupyter/docker-stacks/tree/master/scipy-notebook) ⭐ 8,452 | 🐛 8 | 🌐 Python | 📅 2026-08-09
3. [generative models](https://github.com/wiseodd/generative-models) ⭐ 7,495 | 🐛 24 | 🌐 Python | 📅 2024-03-24: Collection of generative models, e.g. GAN, VAE in Tensorflow, Keras, and Pytorch. <http://wiseodd.github.io>
4. [tch-rs](https://github.com/LaurentMazare/tch-rs) ⭐ 5,473 | 🐛 245 | 🌐 Rust | 📅 2026-07-17: Rust bindings for PyTorch.
5. [pytorch-template](https://github.com/victoresque/pytorch-template) ⭐ 5,116 | 🐛 24 | 🌐 Python | 📅 2024-06-04: PyTorch template project
6. [deep-person-reid](https://github.com/KaiyangZhou/deep-person-reid) ⭐ 4,892 | 🐛 164 | 🌐 Python | 📅 2026-01-09: Pytorch implementation of deep person re-identification approaches.
7. [AlphaZero\_Gomoku](https://github.com/junxiaosong/AlphaZero_Gomoku) ⭐ 3,623 | 🐛 80 | 🌐 Python | 📅 2024-04-24: An implementation of the AlphaZero algorithm for Gomoku (also called Gobang or Five in a Row)
8. [ML Workspace](https://github.com/ml-tooling/ml-workspace) ⭐ 3,542 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-07-26: All-in-one web IDE for machine learning and data science. Combines Jupyter, VS Code, PyTorch, and many other tools/libraries into one Docker image.
9. [DoodleMaster](https://github.com/karanchahal/DoodleMaster) ⭐ 2,408 | 🐛 2 | 🌐 JavaScript | 📅 2019-10-31: "Don't code your UI, Draw it !"
10. [PyTorch Style Guide](https://github.com/IgorSusmelj/pytorch-styleguide) ⭐ 2,017 | 🐛 9 | 🌐 Python | 📅 2021-12-28 Style guide for PyTorch code. Consistent and good code style helps collaboration and prevents errors!
11. [hasktorch](https://github.com/hasktorch/hasktorch) ⭐ 1,210 | 🐛 88 | 🌐 Haskell | 📅 2026-07-28: Tensors and neural networks in Haskell
12. [pytorch\_misc](https://github.com/ptrblck/pytorch_misc) ⭐ 571 | 🐛 8 | 🌐 Python | 📅 2021-02-19: Code snippets created for the PyTorch discussion board.
13. [pytorch-tvmisc](https://github.com/t-vi/pytorch-tvmisc) ⭐ 477 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2022-03-20: Totally Versatile Miscellanea for Pytorch
14. [nimtorch](https://github.com/fragcolor-xyz/nimtorch) ⭐ 473 | 🐛 10 | 🌐 Nim | 📅 2019-06-08: PyTorch - Python + Nim
15. [ocaml-torch](https://github.com/LaurentMazare/ocaml-torch) ⭐ 444 | 🐛 11 | 🌐 OCaml | 📅 2024-10-17: OCaml bindings for PyTorch.
16. [pytorch-scripts](https://github.com/peterjc123/pytorch-scripts) ⚠️ Archived: A few Windows specific scripts for PyTorch.
17. [Amazon\_Forest\_Computer\_Vision](https://github.com/mratsim/Amazon_Forest_Computer_Vision) ⭐ 370 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-11-08: Satellite Image tagging code using PyTorch / Keras with lots of PyTorch tricks. kaggle competition.
18. [awesome-pytorch-scholarship](https://github.com/arnas/awesome-pytorch-scholarship) ⚠️ Archived: A list of awesome PyTorch scholarship articles, guides, blogs, courses and other resources.
19. [pytorch-saltnet](https://github.com/tugstugi/pytorch-saltnet) ⭐ 281 | 🐛 2 | 🌐 Python | 📅 2018-10-29: Kaggle | 9th place single model solution for TGS Salt Identification Challenge.
20. [MentisOculi](https://github.com/mmirman/MentisOculi) ⭐ 245 | 🐛 1 | 🌐 Python | 📅 2020-06-05: A raytracer written in PyTorch (raynet?)
21. [pytorch\_chatbot](https://github.com/jinfagang/pytorch_chatbot) ⭐ 226 | 🐛 3 | 🌐 Python | 📅 2019-06-10: A Marvelous ChatBot implemented using PyTorch.
22. [pytorch-cpp-inference](https://github.com/Wizaron/pytorch-cpp-inference) ⭐ 226 | 🐛 1 | 🌐 C++ | 📅 2020-01-15: Serving PyTorch 1.0 Models as a Web Server in C++.
23. [drawlikebobross](https://github.com/kendricktan/drawlikebobross) ⭐ 115 | 🐛 1 | 🌐 Python | 📅 2017-04-05: Draw like Bob Ross using the power of Neural Networks (With PyTorch)!
24. [extension-script](https://github.com/pytorch/extension-script) ⚠️ Archived: Example repository for custom C++/CUDA operators for TorchScript.
25. [Deep Learning With Pytorch TextBook](https://www.packtpub.com/big-data-and-business-intelligence/deep-learning-pytorch) A practical guide to build neural network models in text and vision using PyTorch. [Purchase on Amazon ](https://www.amazon.in/Deep-Learning-PyTorch-practical-approach/dp/1788624335/ref=tmm_pap_swatch_0?_encoding=UTF8\&qid=1523853954\&sr=8-1)     [github code repo](https://github.com/svishnu88/DLwithPyTorch) ⭐ 91 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2019-06-09
26. [pytorch-inference](https://github.com/zccyman/pytorch-inference) ⭐ 89 | 🐛 2 | 🌐 C++ | 📅 2019-01-17: PyTorch 1.0 inference in C++ on Windows10 platforms.
27. [pytorch-a3c-mujoco](https://github.com/andrewliao11/pytorch-a3c-mujoco) ⭐ 73 | 🐛 1 | 🌐 Python | 📅 2017-11-02: Implement A3C for Mujoco gym envs.
28. [compare-tensorflow-pytorch](https://github.com/jalola/compare-tensorflow-pytorch) ⭐ 72 | 🐛 0 | 🌐 Python | 📅 2018-05-09: Compare outputs between layers written in Tensorflow and layers written in Pytorch.
29. [malmo-challenge](https://github.com/Kaixhin/malmo-challenge) ⭐ 64 | 🐛 0 | 🌐 Python | 📅 2017-05-22: Malmo Collaborative AI Challenge - Team Pig Catcher
30. [derplearning](https://github.com/John-Ellis/derplearning) ⭐ 42 | 🐛 3 | 🌐 Python | 📅 2025-01-06: Self Driving RC Car Code.
31. [sketchnet](https://github.com/jtoy/sketchnet) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2017-09-09: A model that takes an image and generates Processing source code to regenerate that image
32. [TorchSharp](https://github.com/interesaaat/TorchSharp) ⭐ 17 | 🐛 4 | 🌐 C# | 📅 2019-10-26: .NET bindings for the Pytorch engine
33. [pytorch vs tensorflow](https://www.reddit.com/r/MachineLearning/comments/5w3q74/d_so_pytorch_vs_tensorflow_whats_the_verdict_on/): an informative thread on reddit.
34. [Pytorch discussion forum](https://discuss.pytorch.org/)
35. [PyTorch in 5 Minutes](https://www.youtube.com/watch?v=nbJ-2G2GXL0\&list=WL\&index=9).
36. [Deep-Learning-Boot-Camp](https://github.com/QuantScientist/Deep-Learning-Boot-Camp): A nonprofit community run, 5-day Deep Learning Bootcamp <http://deep-ml.com>.
37. [pytorch-cv](https://github.com/youansheng/pytorch-cv): Repo for Object Detection, Segmentation & Pose Estimation.
38. [Deep Learning With Pytorch](https://www.manning.com/books/deep-learning-with-pytorch) Deep Learning with PyTorch teaches you how to implement deep learning algorithms with Python and PyTorch.

##### Feedback: If you have any ideas or you want any other content to be added to this list, feel free to contribute.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._

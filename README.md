# awesome-neat-rnn
This is a precise to-read list for recurrent neural network (RNN). 

Omit the long author lists; start with year, followed by title, jounral, and link. Newer papers go first. There are additional resources such as codes, interesting blog posts, cool articles, etc.

Creator: [Johnny Ho] (https://github.com/johnny5550822)

# Contributions
This repository originally is decided for to keep track of what I come across about recurrent neural network. But, I guess I will get more benifit (as well as you) if I publicize it . I hope everyone can contribue to it and make it better! So, please submit pull requests! For any questions, contact me (johnny5550822@g.ucla.edu)

# Additional resources
This repository is created in order to follow preciseness and neatness. There is another repository that also provide excellent (with full author lists, etc) sources for recurrent neural network, please visit [awesome-rnn] (https://github.com/kjw0612/awesome-rnn). 

# Table of Content
- [Software Package] (#software-package)
- [Sample Codes] (#sample-codes)
- [Blogs] (#blogs)
- [Review] (#review) 
- [Tutorial] (#tutorial)
- [Language modeling] (#language-modeling)
- [Translation](#translation)
- [Image Generation](#image-generation)
- [Hand-writing](#hand-writing)
- [Text Generation](#text-generation)
- [Questions and Answers] (#questions-and-answers)
- [Cell Type](#cell-type)
- [Other](#other)

## Software Package
+ python, [[neon](https://github.com/NervanaSystems/neon)]
+ python, [[chainer](https://github.com/pfnet/chainer)]
+ torch, [[oxnn](https://github.com/tkocisky/oxnn)]
+ torch, [[Element-research](https://github.com/Element-Research/rnn)]
+ Deep Learning in general
  + torch, [[dp](https://github.com/nicholas-leonard/dp)], a torch deep learning library. I think the example folder is the most useful, for example, CNN implementation there

## Sample Codes
+ torch, [[char-rnn](https://github.com/karpathy/char-rnn)]
+ torch, [[learning_to_execute](https://github.com/wojciechz/learning_to_execute)]
+ torch, [[Oxford practical 6](https://github.com/oxford-cs-ml-2015/practical6)]
+ torch, [[Spatial Transformer Layer](https://github.com/moodstocks/gtsrb.torch)]
+ Deep Learing in general
  + torch, [[torch7 official tutorials](https://github.com/torch/tutorials)]
  + torch, [[torch7 official demos](https://github.com/torch/demos)], have a lot of good examples
  + torch, [[UCLA IPAM course on torch7](http://code.madbits.com/wiki/doku.php?id=start)]
  + torch, [[A simplified example on CNN](https://github.com/hpenedones/luacnn)]
  + torch, [[Kaggle CIFAR-10](https://github.com/nagadomi/kaggle-cifar10-torch7/)], codes for Kaggle CIFAR-10 competition (CNN)
+ Lua In general
  + Lua, [[Learn Lua in 15 Minutes](http://tylerneylon.com/a/learn-lua/)]
+ GitXiv, summary of recent published git repositoris for research algorithm [[link](http://gitxiv.com/)]

## Blogs
+ torch7 blogs (some cool explanation and codes), [[blog](http://torch.ch/blog/index.html)]
+ Up-to-date DL news from notey [[blog](http://www.notey.com/blogs/deep-learning)]
+ What does DL think about your selfie? [[blog](http://karpathy.github.io/2015/10/25/selfie/)]
+ The Unreasonable Effectiveness of Recurrent Neural Networks. [[blog](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)]

## Review
+ 2015 Deep Learning, Nature [[paper](http://www.nature.com/nature/journal/v521/n7553/full/nature14539.html)]

## Tutorial
+ 2015, Recurrent Neural Networks Tutorial [[link](http://www.wildml.com/2015/09/recurrent-neural-networks-tutorial-part-1-introduction-to-rnns/)]
+ 2015, understanding LSTM [[links](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)]
+ 2003 A tutorial on training recurrent neural networks, covering BPPT, RTRL, EKF and the "echo state network" approach [[link](http://minds.jacobs-university.de/sites/default/files/uploads/papers/ESNTutorialRev.pdf)]

## Language Modeling
+ 2015 Teaching Machines to Read and Comprehend, NIPS [[paper](http://arxiv.org/pdf/1506.03340v1.pdf)]
+ 2015 Character-Aware Neural Language Models, arXiv [[paper](http://arxiv.org/pdf/1508.06615v2.pdf)]

## Translation
+ 2014 Sequence to Sequence Learning with Neural Networks, NIPS [[paper](http://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks)]
+ 2014 On the Properties of Neural Machine Translation: Encoder–Decoder Approaches, arXiv [[paper](http://arxiv.org/abs/1409.1259)]
+ 2014 Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation, arXiv [[paper](http://arxiv.org/abs/1406.1078)]
+ 2013 Recurrent Continuous Translation Models, EMNLP [[paper](http://nal.co/papers/KalchbrennerBlunsom_EMNLP13)]

## Image Generation
+ 2015 DRAW: A Recurrent Neural Network For Image Generation, arXiv [[paper](http://arxiv.org/abs/1502.04623]
+ 2015 Unveiling the Dreams of Word Embeddings: Towards Language-Driven Image Generation, arXiv [[paper](http://arxiv.org/abs/1506.03500)]
+ 2015 Generative Image Modeling Using Spatial LSTMs, arXiv [[paper](http://arxiv.org/abs/1506.03478)]
+ 2014 Recurrent Models of Visual Attention, arXiv [[paper](http://arxiv.org/abs/1406.6247)]

## Hand-writing
+ 2013 Generating Sequences With Recurrent Neural Networks, arXiv [[paper](http://arxiv.org/abs/1308.0850)]
+ 2007 Offline Handwriting Recognition with Multidimensional Recurrent Neural Networks, NIPS [[paper](http://papers.nips.cc/paper/3449-offline-handwriting-recognition-with-multidimensional-recurrent-neural-networks)]

## Text Generation
+ 2011 Generating Text with Recurrent Neural Networks, ICML [[paper](http://machinelearning.wustl.edu/mlpapers/paper_files/ICML2011Sutskever_524.pdf)]

## Questions and Answers
+ 2015 Ask Your Neurons: A Neural-based Approach to Answering Questions about Images [[paper](http://arxiv.org/pdf/1505.01121.pdf)]
+ 2015 VQA: Visual Question Answering [[paper](http://arxiv.org/pdf/1505.00468.pdf)]
+ 2015 Exploring Models and Data for Image Question Answering [[paper](http://arxiv.org/pdf/1505.02074.pdf)]
+ 2015 Are you talking to a machine? Dataset and methods for multilingual image question answering [[paper](http://arxiv.org/pdf/1505.05612.pdf)]
+ 2015 Teaching Machines to read and comprehand [[paper](http://arxiv.org/pdf/1506.03340.pdf)]
+ 2015 Ask me anything: dynamic memory networks for natural language processing [[paper](http://arxiv.org/pdf/1506.07285.pdf)]

## Cell Type
+ 2014 Empirical Evaluation of Gated Recurrent Neural Networks on Sequence Modeling, arXiv [[paper](http://arxiv.org/abs/1412.3555)]
+ 1997 Long Short-Term Memory, Neural Computation [[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6795963)]

## Other
+ Hyperparameters Optimization
  + 2015 Gradient-based Hyperparameter Optimization through Reversible Learning, Arxiv [[paper](http://arxiv.org/abs/1502.03492)] 
+ CNN: something cool and worth to share here
  + 2015 Spatial Transformer Networks, NIPS [[paper](http://arxiv.org/pdf/1506.02025.pdf)]
  + 2015 Human-level control through deep reinforcement learning, Nature [[paper](http://www.nature.com/nature/journal/v518/n7540/full/nature14236.html)]
+ 2007 Multi-Dimensional Recurrent Neural Networks [[paper](http://people.idsia.ch/~juergen/icann_2007.pdf)]






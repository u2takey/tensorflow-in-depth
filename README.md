# tensorflow-in-depth
和 [awesome-tensorflow](https://github.com/jtoy/awesome-tensorflow) 不同, [tensorflow-in-depth](https://github.com/u2takey/tensorflow-in-depth) 偏向于收集那些关注`tensorflow`以及类似的机器学习/深度学习框架底层实现原理、架构的资料，而不是关注`如何使用`的资料。

## 目录

<!-- MarkdownTOC depth=4 -->
- [Tutorials](#github-tutorials)
- [Models/Projects](#github-projects)
- [Videos/Course](#video)
- [Papers](#papers)
- [Blog/Slides](#blogs)
- [Community](#community)
- [Books](#books)
<!-- /MarkdownTOC -->


<a name="github-tutorials" />

## Tutorials

* [TensorLayer](http://tensorlayer.readthedocs.io/en/latest/user/tutorial.html) - Modular implementation for TensorFlow's official tutorials. ([CN](https://tensorlayercn.readthedocs.io/zh/latest/user/tutorial.html)).
* [Tensorflow Architecture](https://www.tensorflow.org/extend/architecture) 官网Tensorflow架构介绍，需要拓展Tensorflow API或者优化Tensorflow性能的人可以阅读这篇文档.
* [MPI Tutorial](http://mpitutorial.com/) MPI相关的Tutorial.

<a name="github-projects" />

## Models/Projects

* [TensorFlow White Paper Notes](https://github.com/samjabrahams/tensorflow-white-paper-notes) - Annotated notes and summaries of the TensorFlow white paper, along with SVG figures and links to documentation
* [Deep-Q learning Pong with TensorFlow and PyGame](http://www.danielslater.net/2016/03/deep-q-learning-pong-with-tensorflow.html)
* [GoogleNet Convolutional Neural Network Groups Movie Scenes By Setting](https://github.com/agermanidis/thingscoop) - Search, filter, and describe videos based on objects, places, and other things that appear in them
* [Neural machine translation between the writings of Shakespeare and modern English using TensorFlow](https://github.com/tokestermw/tensorflow-shakespeare) - This performs a monolingual translation, going from modern English to Shakespeare and vice-versa.



<a name="video" />

## Videos/Course
* [TensorFlow on YouTube](https://www.youtube.com/tensorflow) - TensorFlow在YouTube的主页，里面如[TensorFlow Dev Summit 2018](https://www.youtube.com/playlist?list=PLQY2H8rRoyvxjVx3zfw4vA4cvlKogyLNN)，[Coding TensorFlow](https://www.youtube.com/playlist?list=PLQY2H8rRoyvwLbzbnKJ59NkZvQAW9wLbx) 值得关注.
* [Designing and Building Applications for Extreme Scale Systems](http://wgropp.cs.illinois.edu/courses/cs598-s16/) - 大规模系统高性能计算的一个课程，介绍了许多重要的概念.

<a name="papers" />

## Papers

* [TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems](http://download.tensorflow.org/paper/whitepaper2015.pdf) - This paper describes the TensorFlow interface and an implementation of that interface that we have built at Google
* [TF.Learn: TensorFlow's High-level Module for Distributed Machine Learning](https://arxiv.org/abs/1612.04251)
* [Comparative Study of Deep Learning Software Frameworks](http://arxiv.org/abs/1511.06435) - The study is performed on several types of deep learning architectures and we evaluate the performance of the above frameworks when employed on a single machine for both (multi-threaded) CPU and GPU (Nvidia Titan X) settings
* [Distributed TensorFlow with MPI](http://arxiv.org/abs/1603.02339) - In this paper, we extend recently proposed Google TensorFlow for execution on large scale clusters using Message Passing Interface (MPI)
* [Globally Normalized Transition-Based Neural Networks](http://arxiv.org/abs/1603.06042) - This paper describes the models behind [SyntaxNet](https://github.com/tensorflow/models/tree/master/syntaxnet).
* [TensorFlow: A system for large-scale machine learning](https://arxiv.org/abs/1605.08695) - This paper describes the TensorFlow dataflow model in contrast to existing systems and demonstrate the compelling performance
* [TensorLayer: A Versatile Library for Efficient Deep Learning Development](https://arxiv.org/abs/1707.08551) - This paper describes a versatile Python library that aims at helping researchers and engineers efficiently develop deep learning systems. (Winner of The Best Open Source Software Award of ACM MM 2017)
* [Scaling Distributed Machine Learning with the Parameter Server](https://www.cs.cmu.edu/~dga/papers/osdi14-paper-li_mu.pdf) - How parameter server works, proposed a parameter server framework for distributed machine learning problems.

<a name="blogs" />

## Blog/Slides

* [图解tensorflow源码](http://www.cnblogs.com/yao62995/p/5773578.html) - TensorFlow图解分析, 导读源码和架构.
* [Tensorflow源码解析](http://gonewithgt.github.io/2017/04/20/Tensorflow%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90/) - 先介绍了TensorFlow的核心概念和基本概述, 然后从源码剖析了TensorFlow的一些模块.
* [TensorFlow - Not Just For Deep Learning](http://terrytangyuan.github.io/2016/08/06/tensorflow-not-just-deep-learning/) 来自[YuanTang的博客](https://terrytangyuan.github.io/), YuanTang是tensorflow、MXNet、XGBoost等项目的committer.
* [How Does The TensorFlow Work](https://www.letslearnai.com/2018/02/02/how-does-the-machine-learning-library-tensorflow-work.html) - TensorFlow如何运作？
* [A tour through the TensorFlow codebase](http://public.kevinrobinsonblog.com/docs/A%20tour%20through%20the%20TensorFlow%20codebase%20-%20v4.pdf) - TensorFlow源码概览.
* [An Introduction to TensorFlow architecture](https://www.slideshare.net/ManiGoswami/into-to-tensorflow-architecture-v2) - tensorflow架构原理简介
* [Autodiff Workshop](https://autodiff-workshop.github.io/) - 2017年的Workshop, gradient-based machine learning技术，有不少slides值得看.

<a name="community" />

## Community

* [Stack Overflow](http://stackoverflow.com/questions/tagged/tensorflow)
* [@TensorFlow on Twitter](https://twitter.com/tensorflow)
* [Reddit](https://www.reddit.com/r/tensorflow)
* [Mailing List](https://groups.google.com/a/tensorflow.org/forum/#!forum/discuss)

<a name="books" />

## Books

* [深入理解TensorFlow 架构设计与实现原理](https://www.amazon.cn/dp/B07CLVXGLH/ref=sr_1_8?s=books&ie=UTF8&qid=1528080417&sr=1-8&keywords=tensorflow) - 前面主要是应用和算法，第四部门核心揭秘篇讲了tensorflow的设计和原理




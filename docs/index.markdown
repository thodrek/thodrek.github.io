---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
list_title: "News"
---
<img style="float: right; padding-left:20px; padding-bottom:20px; width:150px;" src="/assets/photo.jpg">

I am a researcher at Apple. Before that I co-founded Inductiv (acquired by Apple), a company that developed AI solutions for identifying and correcting errors in data. I was also a Professor of Computer Science at ETH Zürich and the University of Wisconsin-Madison. 

My research focuses on scalable machine learning algorithms and systems over relational data. Specifically, it explores the fundamental connections between data preparation, data integration, and knowledge management with statistical machine learning and probabilistic inference:

* <b>Software 2.0 for Data Quality:</b> We are exploring the fundamental connections between data cleaning and machine learning. The [HoloClean](http://www.holoclean.io) project introduced Machine Learning to the problem of data cleaning: We showed how to model data cleaning as statistical learning problem, how attention-based mechanisms and self-supervised learning can automate data cleaning and introduced multiple theoretical results on how to deal with noisy/dirty data. More recently we are exploring the synergies between data cleaning and machine learning deployments in the [Picket](https://arxiv.org/abs/2006.04730) project. This [talk](https://www.youtube.com/watch?v=_2upFBZsMN4) at the Stanford MLsys Seminar provides an overview.

* <b>Neural Relational Engines over Billion-scale Data:</b> We are developing a new paradigm of systems to make the use of <b>deep learning models over billion-scale structured data easier, faster, and cheaper</b>. We have started with the [Marius](https://marius-project.org) project that focuses on a key bottleneck in the development of machine learning systems over large-scale graph data: data movement during training. Marius addresses this bottleneck with a novel data flow architecture that maximizes resource utilization of the entire memory hierarchy (including disk, CPU, and GPU memory). Marius is under active development and available as an [open-source project](https://github.com/marius-team/marius). You can learn more about Marius from our recent [OSDI`21](https://www.youtube.com/watch?v=XP9kUuipK1A&t=17s) and [MLOpsWorld](/assets/marius_mlops.pdf) talks.

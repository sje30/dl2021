# Deep learning 2021 module


# Main text

[Artificial Intelligence Engines](http://jim-stone.staff.shef.ac.uk/AIEngines/index.html)

# Assignments

One assignment to be set for end of term, due in at start of Lent Term.

# Planned timetable

This course will be online, with combination of pre-recorded material
(some from 2020, some new for 2021) and live lectures.  Live lectures
will be twice a week, listed below, on teams.  Live lectures on Wednesdays will be
used to review past week's topics and highlight coming week's
material (recorded).  Fridays lectures will be Q&A sessions of
material presented (and will not be recorded).

## Panopto

Lecture videos are found on [panopto](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx?folderID=9b86eca2-9001-47e0-91c1-adb00100d53f).

[live lectures](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx?folderID=d799435f-d2d9-4d3c-b847-addb013e03e4)\
[pre-recorded lectures](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx?folderID=1f01e085-4e06-439b-a0a6-addb013e09e2)

## DL Live Lecture 1 (week one)
<2021-11-10 Wed 09:00-10:00>

[L1](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=36c25a8b-c308-42bf-9121-addf014795d1): [Overview of course](slides/intro.pdf)

[P2](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=784d3c12-4666-4115-aae7-addb013e475d): [Introductory neuroscience.  Simple models.](slides/neuro101.pdf)

[P3](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=539606db-72be-44bf-94ab-addb013e47e8): [Perceptron.](slides/perceptron.pdf)

[L is a live lecture; P is a recorded lecture; both to be found on Panopto;
live lectures uploaded after the lecture.]

## DL Live Lecture 2
<2021-11-12 Fri 09:00-10:00>  Topics covered: transfer functions,
gradient descent.

## DL Live Lecture 3 (week two)
<2021-11-17 Wed 09:00-10:00>

[L2](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=4b71ae01-e4eb-4a21-9beb-ade3012a56c7): Code run throughs.
Recap of perceptron rule.  [code/perceptron](code/perceptron).

[P4](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=bc780ebb-7102-4f34-b5a2-ac690168b6b2): [Backprop](slides/backprop.pdf)

[P5](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=173a5547-880b-4455-9d10-ac6a01572081):
Backprop applications -- slides as before.

[P6a](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=2c6d0cd4-edc9-4980-9c31-ac63015ec99b): Back prop derivation (part one).  [backprop.pdf](backprop.pdf)
<br>
[P6b](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=1f579de0-8eb8-428a-a626-ac630166eed8): Back prop derivation (part two).  [backprop.pdf](backprop.pdf)

## DL Live Lecture 4
<2021-11-19 Fri 09:00-10:00>

Short announcement by Soo.  Discussion: alternative error functions /
maximisation functions (e.g. L2 regulariser, merit function).
Notation for backprop.  Feature selection via circular weights.

Discussion of assignment: two smaller ones, or one big one?  Answer on
Wed.

## DL Live Lecture 5 (week three)
<2021-11-24 Wed 09:00-10:00>

L3: overview of topics this week\
Dimensionality reduction\
Tips and tricks / recent advances\
Convolutional networks, images\
[XOR in R](code/mlp/xor.R)\
[MNIST in Keras](code/mlp/mnist_bp.Rmd) -- on [subliminal](https://subliminal.maths.cam.ac.uk).\
[A primer on deep learning in genomics](https://www.nature.com/articles/s41588-018-0295-5)
[colab](https://colab.research.google.com/drive/17E4h5aAOioh5DiTo7MZg4hpL6Z_0FyWr)



[P7a](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=2f07a702-bd3c-4d62-8afe-ac6f00e2240f): [dimensionality reduction slides](slides/dimred.pdf)
<br>
[P7b](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=6425e749-9b69-457f-b385-ac6300bc69e8): [Sammon mapping -- gradient descent](https://paperpile.com/app/p/f5e39a89-9dfd-0df1-a507-c1fc70b25f1a)
<br>
[P7c](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=0cab1524-c331-41c8-9706-ac6f00ef133e): [Colah's blog post on dimensionality reduction](https://colah.github.io/posts/2014-10-Visualizing-MNIST/)



[P8a](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=7f0af10b-c3c9-41ad-80d5-ac740158bd37): [Tips and tricks / recent advances](slides/tips.pdf)
<br>
[P8b](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=a665da6f-da9e-4d2f-9c64-ac74016cf442):
Finite differences and automatic differentiation.  [code sample](code/autograd/finite_diff.R)

[P9](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=c1b761a6-72eb-4072-bfc4-ac770156dc0d): [Convolutional neural networks (CNNs), images](slides/images.pdf)

## DL Live Lecture 6
<2021-11-26 Fri 09:00-10:00>

Backpropagation questions on theory and applications.

## DL Live Lecture 7 (week four)
<2021-12-01 Wed 09:00-10:00>


- Questions on last weeks material.

- Summary of topics for this week.

- Future directions (not covered here): GPT3 / Transformers, Graph
  neural networks [1](https://distill.pub/2021/gnn-intro/) [2](https://distill.pub/2021/understanding-gnns/)
  

### Concerns


- reproducibility  concerns [1](https://paperpile.com/app/p/62f647f8-4270-0c0e-951c-26edb825af9c)
  
- Interpretability problems of networks.

- Ethics: structural biases in decisions / training data

- e.g. [Concerns over face
  recognition](https://www.nist.gov/news-events/news/2019/12/nist-study-evaluates-effects-race-age-sex-face-recognition-software)
  biasing different races.

- "Deep fakes".

- Environmental impact (energy) [1](https://www.forbes.com/sites/robtoews/2020/06/17/deep-learnings-climate-change-problem/)

- Resources for companies (large scale training)

[P10](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=450ef521-a3a2-4d60-bb67-ac79015c17ec): [Hopfield networks](slides/hopfield.pdf)\
[supplementary Hopfield](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=0b8a9360-4a1f-436b-90c1-ac6300c76f02)

[P11](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=7d8dbcbc-59f8-446f-9626-ac7a01508a95): [Boltzmann machines / RBMs / GANs](slides/rbm.pdf)

[P12](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=33d5cb6b-019d-42c8-b447-ac7a0156a5d8): [Sequences](slides/sequences.pdf)

[P13](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=e01f1ee3-89e5-46f2-a491-ac7f00d20300): [Reinforcement learning](slides/rl.pdf)

[P14](https://cambridgelectures.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=51b89dcc-d3cf-4288-8203-ac7f015353da): [Unsupervised learning](slides/unsup.pdf)


## DL Live Lecture 8
<2021-12-03 Fri 09:00-10:00>

Discussion of work and assignment 1.


## Assignment one


---
theme: unicorn
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
download: true
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
css: unocss
title: Machine Learning | Marie Behzadi
layout: intro
introImage: "/static/img/marie.jpg"
---

# Different Types of Learning

#### Machine Learning Techniques to solve problems

By Marie Behzadi <mariebehzadi@gmail.com>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-center
image: '/static/img/what-is-data.jpg'
imageWidth: '750'
imageHeight: '950'
---

---

# What is Machine Learning?

- Machine learning is a large field of study that overlaps with and inherits ideas from many related fields such as artificial intelligence.
- The focus of the field is learning, that is, acquiring skills or knowledge from experience. Most commonly, this means synthesizing useful concepts from historical data.
- There are many different types of learning that you may encounter as a practitioner in the field of machine learning: from whole fields of study to specific techniques.

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

---

# Types of Learning

<br>

| <h4>Learning Problems</h4> | <h4>Hybrid Learning Problems </h4> |  <h4>Statistical Inference</h4> |  <h4>Learning Techniques</h4> |
|----------------|--------------|--------------|--------------|
| 1. Supervised Learning | 4. Semi-Supervised Learning  | 7. Inductive Learning | 10. Multi-Task Learning
| 2. Unsupervised Learning | 5. Self-Supervised Learning | 8. Deductive Inference | 11. Active Learning
| 3. Reinforcement Learning | 6. Multi-Instance Learning | 9. Transductive Learning | 12. Online Learning
|  |  |  | 13. Transfer Learning
|  |  |  | 14. Ensemble Learning


---

# 1. Supervised Learning
### Category: Learning Problems

<br>

Supervised learning describes a class of problem that involves using a model to learn a mapping between input examples and the target variable.

There are two main types of supervised learning problems:

- **Classification:** Supervised learning problem that involves predicting a class label.
- **Regression:** Supervised learning problem that involves predicting a numerical label.

<br> 

Both classification and regression problems may have one or more input variables and input variables may be any data type, such as numerical or categorical.

---
layout: image-center
image: '/static/img/supervised-dataset.png'
imageWidth: '750'
imageHeight: '950'
---

## Dataset Example

---
layout: image-center
image: '/static/img/supervised-algorithms.png'
imageWidth: '800'
imageHeight: '950'
---

## Dataset Example

---
layout: image-center
image: '/static/img/classification.vs.regression.png'
---

## Classification vs Regression

---

# 2. Unsupervised Learning
### Category: Learning Problems

<br>

Unsupervised learning describes a class of problems that involves using a model to describe or extract relationships in data.

Compared to supervised learning, unsupervised learning operates upon only the input data without outputs or target variables. As such, unsupervised learning does not have a teacher correcting the model, as in the case of supervised learning.

There are many types of unsupervised learning, although there are two main problems that are often encountered by a practitioner: 

- **Clustering:** Unsupervised learning problem that involves finding groups in data.
- **Density Estimation:** Unsupervised learning problem that involves summarizing the distribution of data.


<br> 

Additional unsupervised methods may also be used, such as visualization that involves graphing or plotting data in different ways and projection methods that involves reducing the dimensionality of the data.

- **Visualization:** Unsupervised learning problem that involves creating plots of data.
- **Projection:** Unsupervised learning problem that involves creating lower-dimensional representations of data.

---
layout: image-center
image: '/static/img/unsupervised-algorithms.png'
---

## Unsupervised Learning

---
layout: image-center
image: '/static/img/unsupervised-clustering.jpeg'
---

## Clustering and Density Estimation


---

# 3. Reinforcement Learning
### Category: Learning Problems

<br>

Reinforcement learning describes a class of problems where an agent operates in an environment and must learn to operate using feedback.

Reinforcement learning is learning what to do — how to map situations to actions—so as to maximize a numerical reward signal. The learner is not told which actions to take, but instead must discover which actions yield the most reward by trying them.

The use of an environment means that there is no fixed training dataset, rather a goal or set of goals that an agent is required to achieve, actions they may perform, and feedback about performance toward the goal.

---
layout: image-center
image: '/static/img/reinforcement-learning.png'
imageWidth: '800'
imageHeight: '950'
---

---
layout: image-center
image: '/static/img/reinforcement-learning-cycle.png'
imageWidth: '700'
imageHeight: '950'
---
## Reinforcement Learning Cycle

---

# 4. Semi-Supervised Learning
### Category: Hybrid Learning Problems

<br>

Semi-supervised learning is supervised learning where the training data contains very few labeled examples and a large number of unlabeled examples.

The goal of a semi-supervised learning model is to make effective use of all of the available data, not just the labelled data like in supervised learning.

Many problems from the fields of computer vision (image data), natural language processing (text data), and automatic speech recognition (audio data) fall into this category and cannot be easily addressed using standard supervised learning methods.

### Labeled Data + Unlabeled Data
### Supervised + Unsupervised

---
layout: image-center
image: '/static/img/semi-supervised-learning.jpeg'
imageWidth: '800'
imageHeight: '950'
---

---
layout: image-center
image: '/static/img/pseudo-labelling.gif'
imageWidth: '500'
imageHeight: '500'
---
## Pseudo Labelling

Pseudo labelling is the process of using the labelled data model to predict labels for unlabelled data.

---
layout: image-center
image: '/static/img/pseudo-labelling.png'
imageWidth: '500'
imageHeight: '500'
---
## Pseudo Labelling

Pseudo labelling is the process of using the labelled data model to predict labels for unlabelled data.
---

# 5. Self-Supervised Learning
### Category: Hybrid Learning Problems

<br>

Self-supervised learning refers to an unsupervised learning problem that is framed as a supervised learning problem in order to apply supervised learning algorithms to solve it.

The self-supervised learning framework requires only unlabeled data in order to formulate a pretext learning task such as predicting context or image rotation, for which a target objective can be computed without supervision.

---
layout: image-center
image: '/static/img/self-supervised-learning.png'
imageWidth: '900'
imageHeight: '950'
---

## Self Supervised Learning

---
layout: image-center
image: '/static/img/self-supervised-learning.png'
imageWidth: '900'
imageHeight: '950'
---

## Self Supervised Learning

---

# 6. Multi-Instance Learning
### Category: Hybrid Learning Problems

<br>

Multi-instance learning is a supervised learning problem where individual examples are unlabeled; instead, bags or groups of samples are labeled.

In multi-instance learning, an entire collection of examples is labeled as containing or not containing an example of a class, but the individual members of the collection are not labeled.

Modeling involves using knowledge that one or some of the instances in a bag are associated with a target label, and to predict the label for new bags in the future given their composition of multiple unlabeled examples.

---
layout: image-center
image: '/static/img/multiple-instance-learning.png'
imageWidth: '700'
imageHeight: '950'
---

## Multiple-Instance Learning

---
layout: image-center
image: '/static/img/multi-instance-example-1.png'
imageWidth: '700'
imageHeight: '950'
---

## MIL: Example #1
#### Binary Classification

The goal of the MIL is to predict the labels of new, unseen bags. 

---
layout: image-center
image: '/static/img/multi-instance-example-2.png'
imageWidth: '700'
imageHeight: '950'
---

## Example #2

---

# 7. Inductive Learning
### Category: Statistical Inference

<br>

Inductive learning, also known as discovery learning, is a process where the learner discovers rules by observing examples.

Inductive learning involves using evidence to determine the outcome.

Inductive reasoning refers to using specific cases to determine general outcomes, e.g. specific to general.

Most machine learning models learn using a type of inductive inference or inductive reasoning where general rules (the model) are learned from specific historical examples (the data).

This can be very **complex** depending on the data.

it is an effective method used in ML and used in various fields of ML like facial recognition technology, disease cure, and diagnosis, etc. It uses a **bottom-up approach**.

The results are not certain, it can range from **strong to weak**.
---

# 8. Deductive Learning
### Category: Statistical Inference

<br>

Deduction or deductive inference refers to using general rules to determine specific outcomes.

Deduction is the reverse of induction. If induction is going from the specific to the general, deduction is going from the general to the specific.

Deduction is a top-down type of reasoning that seeks for all premises to be met before determining the conclusion, whereas induction is a bottom-up type of reasoning that uses available data as evidence for an outcome.

Deductive learning uses the already available facts and information in order to give a valid conclusion. It uses a **top-down approach**.

The one major thing to note is that in deductive learning, the results are certain i.e, it is either **yes or no**. 

If induction is going from the specific to the general, deduction is going from the general to the specific.

---
layout: image-center
image: '/static/img/inductive-vs-deductive.png'
imageWidth: '700'
imageHeight: '950'
---
## Inductive vs Deductive
#### inductive: From observation to conclusion.
In my opinion, Inductive Learning is similar to data-driven learning. Most of popular ML algorithms are belong to this.

#### deductive: From conclusion to observation.
In my opinion, it is similar to expert systems. We give rules (conclusion) , and then get the answer ( observation)

---

# 9. Transductive Learning
### Category: Statistical Inference

<br>

Transduction or transductive learning is used in the field of statistical learning theory to refer to predicting specific examples given specific examples from a domain.

- **Induction**, deriving the function from the given data. 
- **Deduction**, deriving the values of the given function for points of interest. 
- **Transduction**, deriving the values of the unknown function for points of interest from the given data.

<br>

We can contrast these three types of inference in the context of machine learning.


- **Induction:** Learning a general model from specific examples.
- **Deduction:** Using a model to make predictions.
- **Transduction:** Using specific examples to make predictions.

---
layout: image-center
image: '/static/img/relationship.png'
imageWidth: '700'
imageHeight: '950'
---
## Relationship of Induction and Deduction and Transduction
---

# 10. Multi-Task Learning
### Category: Learning Techniques

<br>

Multi-task learning is a type of supervised learning that involves fitting a model on one dataset that addresses multiple related problems.

It involves devising a model that can be trained on multiple related tasks in such a way that the performance of the model is improved by training across the tasks as compared to being trained on any single task.

Multi-task learning can be a useful approach to problem-solving when there is an abundance of input data labeled for one task that can be shared with another task with much less labeled data.

For example, it is common for a multi-task learning problem to involve the same input patterns that may be used for multiple different outputs or supervised learning problems. In this setup, each output may be predicted by a different part of the model, allowing the core of the model to generalize across each task for the same inputs.

---

# 11. Active Learning
### Category: Learning Techniques

<br>

Active learning is a technique where the model is able to query a human user operator during the learning process in order to resolve ambiguity during the learning process.

The learner adaptively or interactively collects training examples, typically by querying an oracle to request labels for new points.

Active learning is a type of supervised learning and seeks to achieve the same or better performance of so-called “passive” supervised learning, although by being more efficient about what data is collected or used by the model.

It is not unreasonable to view active learning as an approach to solving semi-supervised learning problems, or an alternative paradigm for the same types of problems.

**Note**: Of course, we human experts tell all of the label, it make nonsense for the algorithm to learn, i.e., algorithm just ask a small part of the unlabeled data, Under this timely small help, active learning algorithm will get a big boost.

---

# 12. Online Learning
### Category: Learning Techniques

<br>

Online learning involves using the data available and updating the model directly before a prediction is required or after the last observation was made.

Traditionally machine learning is performed offline, which means we have a batch of data, and we optimize an equation […] However, if we have streaming data, we need to perform online learning, so we can update our estimates as each new data point arrives rather than waiting until “the end” (which may never occur).

Generally, online learning seeks to minimize “regret,” which is how well the model performed compared to how well it might have performed if all the available information was available as a batch.

---

# 13. Transfer Learning
### Category: Learning Techniques

<br>

Transfer learning is a type of learning where a model is first trained on one task, then some or all of the model is used as the starting point for a related task.

In transfer learning, the learner must perform two or more different tasks, but we assume that many of the factors that explain the variations in P1 are relevant to the variations that need to be captured for learning P2.

If there is significantly more data in the first setting (sampled from P1), then that may help to learn representations that are useful to quickly generalize from only very few examples drawn from P2. Many visual categories share low-level notions of edges and visual shapes, the effects of geometric changes, changes in lighting, etc.

transfer learning is particularly useful with models that are incrementally trained and an existing model can be used as a starting point for continued training, such as deep learning networks.

---

# 14. Ensemble Learning
### Category: Learning Techniques

<br>

Ensemble learning is an approach where two or more models are fit on the same data and the predictions from each model are combined.

The objective of ensemble learning is to achieve better performance with the ensemble of models as compared to any individual model. This involves both deciding how to create models used in the ensemble and how to best combine the predictions from the ensemble members.

Ensemble learning is a useful approach for improving the predictive skill on a problem domain and to reduce the variance of stochastic learning algorithms, such as artificial neural networks.
---

# Further Reading

<br>

- Pattern Recognition and Machine Learning, 2006.
- Deep Learning, 2016.
- Reinforcement Learning: An Introduction, 2nd edition, 2018.
- Data Mining: Practical Machine Learning Tools and Techniques, 4th edition, 2016.
- The Elements of Statistical Learning: Data Mining, Inference, and Prediction, 2nd edition, 2016.
- Machine Learning: A Probabilistic Perspective, 2012.
- Machine Learning, 1997.
- The Nature of Statistical Learning Theory, 1995.
- Foundations of Machine Learning, 2nd edition, 2018.
- Artificial Intelligence: A Modern Approach, 3rd edition, 2015.

---

# Thank You

Marie Behzadi

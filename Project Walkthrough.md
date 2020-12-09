# Deep Learning Project Walkthrough
Hello and welcome to the Monash DeepNeuron project walkthrough!
You've gone through our training program and now a deep learning challenge to push your skills to the next level!
What better way is there to familiarise yourself with working on a project than doing projects?

This documents the start of your project journey, and is broken down into four stages:
1. Choosing a Project
2. Getting Started
3. Development/Creation
4. Showcase

At every stage, we will provide you with plenty of resources and support.
Although there are no explicit instructions/requirements here (this whole process is quite flexible), this page will provide a general map of how you could go about your project.
Working on this project should be a fun and enjoyable start for everyone here at Monash DeepNeuron!

## Choosing a project
MNist, ImageNet and other staple datasets provided a fine starting point to introduce the concepts and practical details on deep learning.
Here though we'll push you one large step further.
You will find a dataset of your own, and attempt to go about using the previous techniques you've been taught (along with any you research) to try and solve this problem.
To aid everyone out with this challenging task we provide you with two resources:
1. Description of various common types of deep learning projects
2. Description of data sources, with an emphasis on their realistic applicability


We also provide a few "default" options for those who rather pick from a small number of basic examples.
No matter your project choice, we highly recommend **working together in small teams** during for your project!

### Domains
Although in our training program we have only shown examples of image classification, there are a large number of tasks which deep learning can help with.


The recommendation for new beginners (i.e. first-ever DL project) is to stick with classification, labelling or regression problems.
For people with the previous experience, we suggest attempting a slightly more challenging project (like text classification, or 2d image segmentation).
Projects which involve generation (i.e. using generative adversarial networks) are only recommended for those with some prior relevant training or experience.

#### Computer Vision
* Classification/Labelling/Regression - Most basic type of task where you categorise something based on its class or value
* Segmentation - Next step up from classification, now though we want to find precisely where something is present
* Object Detection - Identifying what is present
* Generation - Getting a model to recreate something (like faces)

#### Natural Language Processing
* Classification - Categorise text based on its class or value (like classifying the mood/sentiment behind a tweet)
* Generation - Getting a model to recreate text (there are a broad range of subcategories here)

#### Reinforcement Learning
* Playing video games - Get an agent to play a game (like OpenAI's cartpole or pong)

### Sources
#### Competitions
There are a very large number of current and passed deep learning competitions, and you don't need to compete to get the data!
The most popular one is Kaggle, which has a very wide range of open-source data source.
Often competitions also provide extra reference implementations of the winner's finalised code.

*Disclaimer: Kaggle and other competitive projects are often shunned because of their heavy abstraction (i.e. the data has been modified to remain) and a large focus on raw performance (often accuracy of F1 scores), instead of usefulness*

#### Datset Search Engines
Just like you use Google to answer your questions, several search engines exist which can list out relevant datasets.
The best example is [Google's](https://datasetsearch.research.google.com) (although others like [Visual Data](https://www.visualdata.io/discovery) exist).

#### Example Datasets
Feel free to either base your project of one of the recommended datasets below.
Otherwise, find one yourself!

Here are a few interesting ones we've found (from a variety of sources):
* [Correctly/incorrectly worn masks](https://github.com/cabani/MaskedFace-Net)
* [Lego minifigures](https://www.kaggle.com/ihelon/lego-minifigures-classification)
* [Tagged products](https://products-10k.github.io/)
* [Direction faces are gazing](https://ait.ethz.ch/projects/2020/ETH-XGaze/)
* [Labelled images of galaxies](https://data.galaxyzoo.org/)
* [Cultural heritage photos](https://datahub.ckan.io/fr/dataset/architectural-heritage-elements-image-dataset)
* [Fish image with species labels](https://swfscdata.nmfs.noaa.gov/labeled-fishes-in-the-wild/)
* [Snake images with species labels](https://www.aicrowd.com/challenges/snake-species-identification-challenge)
* [Material images](http://opensurfaces.cs.cornell.edu/)
* [Book covers with genre](https://github.com/uchidalab/book-dataset)
* [Food](https://www.aicrowd.com/challenges/food-recognition-challenge)

## Getting Started
Before starting on any project you need to do a few things:
* Background research - has anyone explained how to go about a similar project?
* Consider the use-case - where/how *could* the project be useful (in theory, makes for an intriguing project)

In general, before we start on a project it is a good idea to get a rough gauge on the techniques other people have successfully used.
This informs us of what we are capable off and so what we can aim to do.

## Development/Creation
The steps you require for a data science project vary a lot.
That being said, it is still important to think to break any project down into several smaller (achievable) steps.

Here are a few basic ones:
* Create or join a Git repository - used to track your project's progress
* Load data - use PyTorch/PyTorch Lightning
* Get basic model working - use PyTorch/PyTorch Lightning
* Connect to Weights and Biases - gives a visual overview on how your model is doing
* Run tests/experiments - test out what techniques/models work (basic -> advanced)

## Showcase
Once we create an amazing machine learning model it is important to consider your progress and where you can use it along with the results themselves.
This is perhaps the most enjoyable stage, as we've finished with the grunt work (a.k.a. research and development) and can move onto reflecting on how we've gone, what worked and what we can do going forwards.
This is the perfect opportunity to let your Git repository shine, as you can create a nice introductory page for any onlookers (maybe other MDN members?) interested in what you have done.
Think of it as a page describing to the past you:
* What the overarching goal was/why it is important
* The process of creating the model
* Graphs and visuals showing the results
* Description of what has been achieved
* Advice for future research/application

If you want to go even further feel free to create a website/app for it.

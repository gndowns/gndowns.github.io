---
layout: post
title: "Paper Accepted to CVPR 2019"
author: "Gabriel Downs"
categories: posts
image: scene_symmetry.png
---

In 2018 I worked as a Computer Vision Researcher under
[Professor Kaleem Siddiqi](http://www.cim.mcgill.ca/~siddiqi/) and
[Morteza Rezanejad](http://www.cim.mcgill.ca/~morteza/) in the
[Shape Analysis Group](http://www.cim.mcgill.ca/~shape/?page=main) at the
McGill Centre For Intelligent Machines.
Our project combined research in human and computer vision to study the role of
contour geometry in scene categorization. 
By leveraging ideas from human psychology and perception such as symmetry and
gestalt grouping we were able to enhance performance of
state-of-the-art computer vision models for classifying line drawings of scenes.

The paper I collaborated on for the project has now been accepted to
[CVPR 2019](http://cvpr2019.thecvf.com/)!
You can find our paper on [arxiv](https://arxiv.org/abs/1811.10524) or on the
official
[CVPR site](http://openaccess.thecvf.com/content_CVPR_2019/html/Rezanejad_Scene_Categorization_From_Contours_Medial_Axis_Based_Salience_Measures_CVPR_2019_paper.html).
This was, as far as we know, the first study of classification of line drawings
of scenes by Convolutional Neural Networks (CNNs)

The code we wrote for generating line drawings of scenes is available on
[GitHub](https://github.com/mrezanejad/AOFSkeletons). I wrote the command line
interface and documentation for the repo. The matlab code and algorithms were
developed by Morteza Rezanejad and Professor Kaleem Siddiqi. 

You can also find all of the code for the machine learning experiments used in
the paper on my
[GitHub](https://github.com/gndowns/SceneSymmetryCNNs).
I wrote all of the experiments using Keras and TensorFlow.

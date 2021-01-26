---
layout: post
title:  "Technique of Copy-Move Forgery Detection"
date:   2018-02-02 17:10:06 +0100
categories: kth eit computer-vision
---
# Technique of Copy-Move Forgery Detection
* Sep 2017 - Feb 2018  
* _KTH, EIT Digital Media Technology_  
* Authors:
    * Andrea Leopardi
    * Yi Li

## Abstract
Nowadays, an important channel of news is represented by social media, in particular by the format of pictures. Since false or corrupted information leads people to misunderstand facts or events and instigate towards unfounded opinions, being able to prove the authenticity of news is important for the sustainable development of our societies. Detecting fake news is therefore as important as difficult in our days because many are the pictures spread and shared on the web, but many are also the techniques available to tamper and alter them. Copy-Move forgery is a very common technique of image manipulation that consists in copying and moving a part of a picture to hide and corrupt a part of its content in such a way that is often difficult to detect by human eyes. The method here presented aims to detect cases of Copy-Move forgery, starting from two techniques well known in literature; it firstly splits the image into regions, in a way they can be successively compared with operations of feature extraction and matching. Then, an affinity transformation is applied to every pair of suspected regions to increase their similarity if they were truly Copy-Moved, or otherwise to intensify their differences; results are iteratively improved by an Expectation Maximization process. Because of this optimization, the methods are able to cover cases of Copy-Moved regions affected by spatial distortions that the techniques earlier introduced do not consider. Moreover, this method achieves a high level of accuracy both for correct detection as well as rejection cases.

## Random pics from the project
![copy-move](/assets/img/2018-02-02-Copy-Move-Forgery-Detection/cm-forg-det.png)

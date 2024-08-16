---
layout: page
title: VideoASL
description: ASL recognition from video
img: assets/img/videoasl/asl vid.gif
importance: 3
category: fun
---

## Overview

VideoASL aims to improve isolated sign language recognition
(ISLR) from video. Using a two-pronged approach, the proposed model uses video features in conjunction
hand landmark locations to recognize large-scale American Sign Language (ASL). We
aim to address challenges in dictionary retrieval, which are essential tools for language
learners and users. Potential applications include live sign transcription, as well as
creating a reliable ASL-to-English dictionary. It is currently a working paper.

### Dataset

We use the ASL Citizen dataset. This dataset represents the first large-scale, con-
tinuous ASL dataset, emphasizing conversational ASL within a diverse range of contexts. It contains
84,000 video recordings of over 2700 ASL signs.

### Model Architecture

![VideoASL model architecture](assets/img/videoasl/arch.png)

Our feature extractor is a video classification model VideoMAE (Masked Auto-encoding). The landmark detector is Mediapipe's pose landmark detector.

### Results

Coming soon!

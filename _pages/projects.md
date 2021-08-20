---
title:  "Projects"
layout: splash
permalink: /projects/
author_profile: true
comments: true

feature_row_ml_projects:
  - image_path: /assets/images/projects/doc-classifier.png
    alt: "Image"
    title: "Document Classification"
    excerpt: "Trained a document classifier having 7 classes to provide 99.99% accuracy on the test data set."

  - image_path: /assets/images/projects/object-detection.png
    alt: "Image"
    title: "Object Detection"
    excerpt: "Trained a object detection model using ssd-inception-v2-coco and faster-rcnn-resnet50-coco to identify different elements of a document."

  - image_path: /assets/images/projects/email-classifier.png
    alt: "Image"
    title: "Spam or Ham - Email Classifier"
    excerpt: "Trained a light-weight email classifier using Batch Gradient Descent for regularized Logistic Regression."

  - image_path: /assets/images/projects/context-search.png
    alt: "Image"
    title: "Context-based Search"
    excerpt: "Built a pipeline to find paragraphs from a document related to a user query using the BERT and GloVe embeddings after accounting for the trade-off between time and accuracy of these models."

  - image_path: /assets/images/projects/topic-modeling.png
    alt: "Image"
    title: "Topic Modeling"
    excerpt: "Built a flow for getting the topics about which the document speaks. This has helped the business folks in clustering documents by topics."

  - image_path: /assets/images/projects/summary.png
    alt: "Image"
    title: "Summarization"
    excerpt: "Built a extractive summarization pipeline for getting a summary of a document in a few sentences."
    
  - image_path: /assets/images/projects/fabric.jpeg
    alt: "Image"
    title: "Color Classification using RGB Camera"
    excerpt: "Designed a fully-automated user-friendly suite that captures an image using a RGB camera and after accounting for color temperature and lighting conditions classifies the input fabric based on its color. (Paper presented in an IEEE Conference)"
    url: "https://ieeexplore.ieee.org/document/8524580"
    btn_class: "btn--inverse"
    btn_label: "Read more"

  - image_path: /assets/images/projects/kv-pair-extraction.png
    alt: "Image"
    title: "Key-Value pair extraction from a document"
    excerpt: "Trained a NER model for getting 95%+ accuracy on extracting key-value pairs from a document."

  - image_path: /assets/images/projects/selectable-pdf.png
    alt: "Image"
    title: "Converting a Scanned PDF into a text-selectable PDF"
    excerpt: "Being able to search text in a PDF is a feature that almost everyone uses on a daily-basis in any industry. Converted scanned images / PDFs into a text-selectable PDFs by adding a searchable layer on top of the input documents."

feature_row_eni_projects:
  - image_path: /assets/images/projects/eprom.jpg
    alt: "Image"
    title: "Designing an EPROM Programmer"
    excerpt: "The project was aimed to check whether the memory locations of an EPROM are empty, and if found empty, store the data entered by the user using the hex keypad at a specific memory location."

  - image_path: /assets/images/projects/phone.jpeg
    alt: "Image"
    title: "Designing a sequential circuit to control a phone answering machine"
    excerpt: "The sequential circuit was designed to manage the incoming calls on a phone using the Moore Model."

  - image_path: /assets/images/projects/wind-energy.jpeg
    alt: "Image"
    title: "Doubly Fed Induction Generator (DFIG) based Wind Energy Integrated Power System"
    excerpt: "Studied the structure of wind turbines, types of commercial wind turbines, mathematical model for doubly fed induction generator wind energy conversion systems and performed the load flow analysis and initialization."    
---
<center><h1 id="Machine_Learning"> Machine Learning </h1></center>
<br>
{% include feature_row id="feature_row_ml_projects" %}

<center><h1 id="Electronics"> Electronics </h1></center>
<br>
{% include feature_row id="feature_row_eni_projects" %}
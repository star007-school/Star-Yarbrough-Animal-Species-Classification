# Animal Species Classification
**Student:** Star Yarbrough
**Course:** ITAI 1378 - Computer Vision and AI
**Project Tier:** Tier 1 Computer Vision Project

## Problem Statement
Identifying animal species from images can be time-consuming and often requires expert knowledge. Automaating species classification can assist wildlife researchers and biodiversity monitoring efforts by speeding up the identification process.

## Solution Overview
This project proposes an image classification system that predicts the species of an animal from an input image and outputs the predicted species along with a confidence score. 

## Technical Approach
- **Technique:** Image Classification
- **Model:** ResNet-50 (pre-trained)
- **Framework:** PyTorch 
- **Method:** Transfer learning to fine-tune the model on an animal species dataset

## Dataset Plan
- **Source:** iNaturalist  2021 Dataset
- **Size:** 10,000+ labeled images (subset will be used for Tier 1)
- **Labels:** Animal species categories
- **Link:** https://github.com/visipedia/inat_comp
- **Preparation:** Resize images, normalize pixel values, and split into training and testing set. Transfer learning will be applied.

## Success Metrics
- **PrimarybMetric:** Classification accuracy &ge; 80%
- **Secondary Metric:** Inference time < 1 second per image

## Week-by-week Plan
- **Week 10:** Dataset selection and environment setup
- **Week 11:** Model configuration and baseline training
- **Week 12:** Evaluation and performance improvements
- **Week 13:** Output generation and testing
- **Week 14:** Documentation and final adjustments
- **Week 15:** Presentation

## Resources Needed
- Google Colab (free GPU)
- PyTorch
- Public wildlife dataset
- Estimated Cost: $0

## Risk & Mitigation
- **Risk:** Dataset complexity
  - *Mitigation:* Limit number of species/classes
- **Risk:** Low accuracy
  - *Mitigation:* Apply data augmentation or adjust model selection

## AI Usage Log
AI tools were used to assist with brainstorming project structure, refining documentation language, and clarifying technical planning decisions. 
All implementation adn final decisions were made by myself, the project author. 

This section will be updated as development continues.

## Current Status 
- [x] Repository created
- [x] Dataset accquired
- [ ] Model training started
- [ ] Demo created
- [ ] Final Presentation ready

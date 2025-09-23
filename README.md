# SmartWaste-AI  

Final project for the Building AI course  

## Summary  
SmartWaste is an AI system that uses computer vision to automatically identify household waste (plastic, paper, glass, organic, etc.) and guide users to dispose of them correctly. Building AI course project.  

## Background  
Waste mismanagement is a global issue:  
* Millions of tons of recyclables end up in landfills.  
* Many people are unsure which bin to use.  
* My motivation comes from daily confusion in recycling practices in my city.  

## How is it used?  
* A user places an item under a camera.  
* The AI classifies the item in real-time.  
* It gives a clear instruction: *“Put this in the paper bin.”*  

## Data sources and AI methods  
* Dataset: [TrashNet](https://github.com/garythung/trashnet)  
* AI method: CNNs (image classification)  
* Tools: Python, TensorFlow/Keras  

## Challenges  
* Ambiguous items (e.g., greasy pizza boxes).  
* Different recycling rules by region.  
* Requires diverse training data.  

## What next?  
* Build a mobile app.  
* Collaborate with municipalities.  
* Add gamification.  

## Acknowledgments  
* Inspired by open source projects like TrashNet.  
* [TrashNet dataset by Gary Thung](https://github.com/garythung/trashnet) (MIT License).  

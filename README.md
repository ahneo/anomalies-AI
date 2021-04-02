<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Anomalies AI

Final project for the Building AI course

## Summary

My idea for this project is about the use of AI methods that can identify anomalies in scanned images of vehicles and cargos for illegal smuggling of contraband goods such as drugs, arms and explosives across borders.


## Background

The land border between Singapore and Malaysia is one of the busiest in the the world, with a few hundred thousand people and vehicles crossing everyday. One of the key challenges faced is the illegal smuggling of contraband goods. In 2019, 92,000 contraband cases were detected and that averaged to about 252 cases of illegal smuggling everyday. With a shrinking workforce and smugglers finding new ways to evade the border security checks, it has become a real daily challenge for the Singapore border security authority. To overcome these challenges, they work with international partners and benchmark themselves against the best technology available to keep Singapore's borders safe.

## How is it used?

Our solution will detect and display any anomalies from the scanned images of vehicles and cargos. The solution will be integrated with the Singapore border security authority systems. Upon the generation of the scanned images of the vehicles and goods in the Singapore border security authority systems, the scanned images will be feeded to our solution and the results will be feeded back to the systems via integrated API services. The enforcement officers will have the scanned images and anomalies displayed side by side under the same systems and interfaces.

## Data sources and AI methods
The data sources will be the repository of scanned images collected by the Singapore border security authority systems. They will be used for training and testing a neural network to identify the anomalies. 

The process will be to generate a training and testing datasets from the scanned images, create the anomalies classifier, train and test the model, continue to work with the Singapore border security authority to iteriate and finetune the classifier.

## Challenges

The solution does not solve the broader aspect of the challenges such as profiling, identify relationships and patterns based on attributes such as the driver, vehicle, goods, origin and destination address in order to deduce a high or low risk profile. This area can potentially be expanded in future using other AI methods.

One of the potential limitations could be the current scanning technology. Or in other words, the project might be further enhanced with an upgrade to the current scanning technology that can generate more subtleties in scanned images which then might aid in improving the accurancy of the anomalies classifier.


## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
The project can grow beyond vehicles to freight cargo by sea or air. What we need is to work with the relevant maritime, port and aviation authorities 


## Acknowledgments

* https://www.elementsofai.com/
* https://www.straitstimes.com/singapore/tech-boost-for-singapores-border-security
* https://www.ica.gov.sg/docs/default-source/ica/stats/annual-stats-report/ica-annual-statistics-2020.pdf
* https://www.ica.gov.sg/news-and-publications/media-releases/media-release/more-than-3-000-cartons-of-duty-unpaid-cigarettes-found-hidden-in-prime-mover-and-bus-at-tuas-checkpoint
* https://www.ica.gov.sg/news-and-publications/media-releases/media-release/more-than-11180-cartons-of-duty-unpaid-cigarettes-detected-at-pasir-panjang-scanning-station

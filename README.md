<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Anomalies AI

Final project for the Building AI course

## Summary

This project is about the use of AI methods that can identify anomalies in scanned images of vehicles and cargos for illegal smuggling of contraband goods such as drugs, arms and explosives into the country.


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?




## Data sources and AI methods
The data sources will be the repository of scanned images collected by the ICA. They will be used for training and testing a neural network to identify the anomalies. 

The process will be to generate a training and testing datasets from the scanned images, create the anomalies classifier, train and test the model, continue to iteriate and finetune the classifier.

## Challenges

The project does not solve the broader aspect of the problem such as profiling and identify relationships and patterns so that based on the driver, vehicle, goods, origin addresss and destination address, we might be able to deduce a high or low risk profile. This area can be expanded in future using other AI methods.

One of the potential limitations could be the current scanning technology. Or in other words, the project might be further enhanced with an upgrade to the current scanning technology that can generate more subtleties in scanned images which then might aid in improving the accurancy of the anomalies classifier.


## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 
The project can grow beyond vehicles to freight cargo by sea or air. What we need is to work with the relevant maritime, port and aviation authorities 


## Acknowledgments

* https://www.elementsofai.com/
* https://www.ica.gov.sg/docs/default-source/ica/stats/annual-stats-report/ica-annual-statistics-2020.pdf
* https://www.ica.gov.sg/news-and-publications/media-releases/media-release/more-than-3-000-cartons-of-duty-unpaid-cigarettes-found-hidden-in-prime-mover-and-bus-at-tuas-checkpoint
* https://www.ica.gov.sg/news-and-publications/media-releases/media-release/more-than-11180-cartons-of-duty-unpaid-cigarettes-detected-at-pasir-panjang-scanning-station

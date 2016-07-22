# EAS213_2016
July 21st/22nd	Developing a classifier:
===================================
* Review of image as array
* Filtering data via Boolean masking

Developing a classifier
* Computing statistics on selected regions
* Using statistics to build an NDVI classifier
* Creating classifiers for water, building, clouds
Training a classifier:
* Comparing class statistics
* Updating classification rules based on findings.

Homework: Submit an ipython notebook where you:
================================================
1. Find a region of interest (land, water, buildings)
2. Explain why you chose that region (in a comment or markdown text)
3. Compute the pdfs of he RGB values of that region
4. Develop a mask (which is a classification rule) based on those pdfs
5. Explain the criteria choices (why you use certain thresholds, why a certain combination)
4. Apply that mask to the data
5. Visualize the two classes (data in mask, data not in mask)
7. Explain the visual differences between the two classes
6. Compute the pdfs of the classes. 
6. Explain how the classes differ based on the pdfs
7. Explain whether this was a good classifier or not, with a justification based on the graphs and othe explainations.

The grade will be almost completely dependent on the explainations.


July 25th: Testing a classifier
===============================
* Factoring out classifier rules into function
* Applying to a new image
* Evaluating the results – confusion matrix, etc
* Updating the classifier

July 26th: Expanding a classifier
=================================
* Incorporating Temperature & Optical Depth
* Adding classes & subclassing 
* Comparing classes over time
Homework: Write a 1-2 page report (with graphs) summarizing:
* How the classes have been improved
* Why the classification is reliable

July 28th: Project: Build Your Own Classifier
==================================================
Develop a classifier for at least 1 surface type or weather phenomena not covered in class. The project must
* Explain the reasoning for the classification criteria
* Describe the training & testing of the classifier
* Evaluate the skill of the classifier 
*	Compare the class to:
  *	Non-classifier data
  *	Data in at least one complementary but opposing class (so NDVI vs. water)

Extra Credit: Repeat the project with a 2nd surface type/weather phenomena. You may compare this class to the 1st class you built for the project. 

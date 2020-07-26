# About the Project

## Overview
An UiPath based RPA project for solving the RPA listed at http://www.rpachallenge.com/. The challenge here is that the order of the HTML components i.e., 
the Labels and Text Fields are jumbled at each submission. And there are a total of 10 levels to pass to successfully complete the RPA challenge. To add to this, the values that are to be put in the text boxes would have to be fetched from an excel file.

Project was Inspired by https://www.udemy.com/course/complete-uipath-rpa-developer-course/, by Leon Petrou. Highly recommend this UI Path course in Udemy to everyone.

![](Automation%20Challenge%20Successful.png)

## Sample Automation In Action
Providing some levels to give an idea about the challenge.

### Level 1
![](Automation%20In%20Progress.png)

### Level 4
![](Automation%20In%20Progress2.png)

### Level 7
![](Automation%20In%20Progress3.png)

## Key Considerations
Since the position of the UI elements is going to change, we have to click on the box relative to the corresponding UI element. This is
achieved using 'Anchor Base' UI Path activity to identify the Anchor along with a 'Type Into' activity to type into the text field.

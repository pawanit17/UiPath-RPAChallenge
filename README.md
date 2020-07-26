# Overview
An UiPath based RPA project for solving the RPA listed at http://www.rpachallenge.com/. The challenge here is that the order of the HTML components i.e., 
the Labels and Text Fields are jumbled at each submission. And there are a total of 10 levels to pass to successfully complete the RPA challenge.

![](Automation%20Challenge%20Successful.png)

Sample Automation In Action
![](Automation%20In%20Progress.png)

Key Considerations: Since the position of the UI elements is going to change, we have to click on the box relative to the corresponding UI element. This is
achieved using 'Anchor Base' UI Path activity to identify the Anchor along with a 'Type Into' activity to type into the text field.

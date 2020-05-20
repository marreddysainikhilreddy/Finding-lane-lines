# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I added a guassian blur and then canny edge detection and after canny edge detection i found the region of intrest and then i have used hough transform to get the markings of the lane lines and then plotted them on the image of a road.

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by slopes of the lines.

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text][image1]


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when there are so many parameters to compute. 

Another shortcoming could be the processing speed of the image


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to make the detection even more better by using advanced algorithms

Another potential improvement could be to study the lane lines better.

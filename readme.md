# Autodigitizer
In essence this program should read an image (some graphically represented data) and out the raw data.

## Current state
At the genesis of this project, I thought that the problem is quite straightforward. However, as I devled deeper into I realized there are many issues that I don't have the knowledge to resolve yet. To name some of them:
* Because my approach is fully image processing based, program is highly susceptible to noise, and reads some noise as data points.
* Identifying text on the image is also highly dependent on the resolution of the image.
* There is no 'depth' information in the image. If there is overlaying data of two different colors, for example, there is no way for this program to know, since it will read only the 'top' color.
* and many more that will come up as I continue embarking on this project.

Due to these issues, I am taking a break from this project for now, instead I will on some other project ideas of mine.

## Possible approach
One possible way of doing this can be done using deep learning. Dataset can be generated using Python's matplotlib module. This will be one of my new approaches when I will return to this project.

## If you want to help/colaborate
Please feel free to reach out, I will be happy to work with you!

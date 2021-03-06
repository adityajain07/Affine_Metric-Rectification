# Affine and Metric Rectification
The input is a projectively distorted image 'floor.jpg', consider central distorted white square- its sides are no longer parallel and also the adjacent sides are no longer orthogonal. The goal is to first rectify the distorted image upto affine level (i.e make the sides parallel) and then finally rectify it to metric level(i.e make the adjacent sides orthogonal).

![AltText](https://github.com/adityajain07/Affine_Metric-Rectification/blob/master/floor.jpg)


## Affine Rectification
Affine rectification removes projective distortion in the image i.e. makes the sides parallel which are parallel in the original image. When the image window of 'floor.jpg' pops up when you run the code, select any two pair of parallel lines which are not pointing in the same direction. This can be done by selecting points (in order) like in the below image (but not limited to):  <br/>

![AltText](https://github.com/adityajain07/Affine_Metric-Rectification/blob/master/Points_Affine.png)  <br/>





Below is the image after applying affine rectification:
![Affine Rectification](https://github.com/adityajain07/Affine_Metric-Rectification/blob/master/AffineRectifiedImage.jpg)


## Metric Rectification
Metric Rectification removes affine distortion in the image i.e. makes the adjacent sides orthogonal. In the affinely rectified image obtained above, select two pairs of orthogonal lines (Note: The two pair of orthogonal lines should be non-parallel). The lines can be selected by choosing  points (but not limited to): <br/>



![AltText](https://github.com/adityajain07/Affine_Metric-Rectification/blob/master/Points_Metric.png)  <br/>

Note: The 'small' green circles are NOT the selected points in metric rectification but are the points selected in affine rectification. Since we were printing the selecting points on the image, thus they are a part of the affinely rectified image.


Below is the image after applying metric rectification:
![Metric Rectification](https://github.com/adityajain07/Affine_Metric-Rectification/blob/master/MetricRectifiedImage.jpg)

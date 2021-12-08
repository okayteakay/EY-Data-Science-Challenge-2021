# EY-Data-Science-Challenge-2021
Our submission for the better working world data challenge organized by Ernst &amp; Young. Data supplied by European Space Agency and NASA.

### 1) Image Dataset 

Training Dataset: 129 Line-scan images (infra-red images taken from an airplane) of bushfires in Victoria, Australia, during the first three months of 2019. There are also polygons showing where the fire is in each image, hand drawn by EY collaborators at the Country Fire Authority (CFA). These polygons are the ground truth the solution, that we were required to recreate.

Test Dataset: 5 additional Line-scan images without fire boundaries.

### 2) Polygon Dataset 

While the polygons provided were created from the linescan images, it was not easy to identify which linescan was the source for a given polygon. Two kinds of matches existed- Direct matches & Composite Polygons. While Direct matches meant simple metadata matching could help, composite polygons represented larger fires that stretched over many linescan images. Thus, these were a little more trickier to match.

### 3) Visualizing Raw Data

a) Exampe of a linescan image

<img src="https://github.com/okayteakay/EY-Data-Science-Challenge-2021/blob/main/images/linescan1.png" width="420">

b) Example of matched polygons on the linescan image

<img src="https://github.com/okayteakay/EY-Data-Science-Challenge-2021/blob/main/images/linescan_polygon.png" width="420">

b) Example of polygon masks by image processing techniques

<img src="https://github.com/okayteakay/EY-Data-Science-Challenge-2021/blob/main/images/linescan_mask.png" width="700">



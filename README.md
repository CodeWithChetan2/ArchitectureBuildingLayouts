# Building Layout Analysis using Machine Learning

## Problem Description
An architecture company has recently completed an initiative to digitalize their building layout designs. As part of this exercise, they have converted the plan view of buildings architected by them into bitmaps of size 640 x 480 pixelsow.

A repository of 1183 such views (i.e., buildings) has been created in the first phase. These images are available in the file `E7-images.zip`.

The company aims to leverage data science and machine learning techniques to improve productivity, facilitate robust designs, and mine hidden information within these building layouts. They have posed several requirements and questions:

1. **Design Family Clustering**:
   - They suspect that their designs can be grouped into families based on their shapes. They want to explore at least two different approaches for clustering these designs into families to gain insights and standardize their designs by creating templates.

2. **Complexity Classification**:
   - They want to classify the complexity of layouts into Low, Medium, and High categories. They seek an analysis to establish criteria for determining layout complexity.

3. **Layout Retrieval based on Parameters**:
   - They want to speed up the layout design process by retrieving relevant prior layouts based on a set of gross parameters such as dimensions, layout area, and permissible complexity. Predicting the design family/families likely to provide the closest designs based on these parameters would aid in retrieving layouts for further detailing.

4. **Exploration of Additional Possibilities**:
   - They are open to exploring other possibilities and ideas for utilizing the image data and mined information to further enhance their design processes and productivity.

## Proposed Solutions
1. **Design Family Clustering**:
   - Explore two different clustering approaches such as K-means clustering and hierarchical clustering to group similar building layouts into families based on their shapes.

2. **Complexity Classification**:
   - Perform a formal analysis of the layouts to establish criteria for determining complexity. Use machine learning algorithms such as decision trees or support vector machines to classify layouts into Low, Medium, and High complexity categories.

3. **Layout Retrieval based on Parameters**:
   - Develop a machine learning model that takes input parameters such as dimensions, layout area, and permissible complexity, and predicts the design family/families likely to provide the closest designs. Retrieve layouts from these families for further detailing.

4. **Exploration of Additional Possibilities**:
   - Investigate the potential of using image recognition techniques to extract additional features from the building layout images.
   - Explore generative models to generate new layout designs based on existing ones.
   - Implement recommendation systems to suggest alternative designs based on customer preferences and requirements.

5. **The file ProjectDS.ipynb has all the solution to all the questions mentioned above

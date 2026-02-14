# MLPR Lab 5

## Overview

This project demonstrates face detection, feature extraction, clustering, and distance-based classification.

The complete workflow includes:

- Haar Cascade Face Detection
- HSV Feature Extraction (Mean Hue & Mean Saturation)
- KMeans Clustering
- Euclidean Distance-Based Classification
- Multiple Visualizations

All implementations and outputs are included in the Jupyter Notebook.

## Aim of the Lab

The objective of this lab was to:

- Detect multiple faces in a group image
- Extract meaningful color features from each face
- Perform clustering using a distance-based algorithm
- Classify a new template image using nearest centroid
- Visualize clustering and classification results

## Methodology

### Face Detection

- Converted group image to grayscale
- Applied Haar Cascade classifier
- Detected 30 faces
- Drew bounding boxes

### Feature Extraction

For each detected face:

- Converted face region to HSV color space
- Extracted:
  - Mean Hue
  - Mean Saturation

These values formed the feature vector for clustering.

### KMeans Clustering

- Used 2 clusters
- Applied Euclidean distance
- Computed cluster centers (centroids)
- Assigned faces to clusters

### Template Classification

- Loaded template face image
- Extracted HSV features
- Calculated Euclidean distance from centroids
- Assigned template to nearest cluster

## Visual Results

### Multi-Face Detection

<img width="1146" height="791" alt="image" src="https://github.com/user-attachments/assets/3ecec75b-1007-4623-b5dc-acf7fb2a9d8a" />


### Template Face Detection

![Template Detection](images/template_face_detection.png)

### HSV Feature Distribution (With Face Thumbnails)

![HSV Scatter with Faces](images/hsv_scatter_faces.png)

### Clustered Faces with Centroids

![Clustered Faces](images/clusters_centroids.png)

### Clusters with Template (Image Overlay)

![Clusters with Template](images/clusters_with_template.png)

### Final Classification Plot

![Final Classification](images/final_clusters_template.png)

## Key Observations

- Haar Cascade effectively detected multiple faces.
- HSV color space provided meaningful clustering features.
- KMeans separated faces into two distinct groups.
- Template classification was performed using Euclidean distance.
- Visualization helped interpret cluster separation clearly.

## Conclusion

This lab successfully combined computer vision and distance-based machine learning techniques.

The workflow demonstrated:

1. Object detection  
2. Feature engineering  
3. Unsupervised clustering  
4. Distance-based classification  
5. Visualization of results  

It provided practical understanding of how distance metrics and clustering algorithms can be applied to image analysis tasks.

## Author

Vayun Gupta  
U20240020
DSEB

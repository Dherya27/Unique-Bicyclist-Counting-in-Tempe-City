![Computer Vision](https://img.shields.io/badge/Computer%20Vision-blue)

# Bicyclist counting in Tempe City using Self-supervised Re-identification

## Problem
Tracking a bicyclist across multiple images to avoid duplicate counting

<img src="https://github.com/Dherya27/Motion_Planing/blob/main/same_bicylist.png">

## Locations where cameras have been deployed in Tempe City
  <img src="https://github.com/Dherya27/Motion_Planing/blob/main/image.png" width=400 height=300>     <img src="https://github.com/Dherya27/Motion_Planing/blob/main/images_location.png" width=500 height=300>

## Approach
<img src="https://github.com/Dherya27/Motion_Planing/blob/main/approach.png" width=450 height=250> 

## Classification
<img src="https://github.com/Dherya27/Motion_Planing/blob/main/classification.png" height=140> 

#### Success and Failure cases of Classification
<img src="https://github.com/Dherya27/Motion_Planing/blob/main/classification_success.png" width=300 height=200> <img src="https://github.com/Dherya27/Motion_Planing/blob/main/classification_failure.png" width=300 height=200> 

## Detection
<img src="https://github.com/Dherya27/Motion_Planing/blob/main/detection.png" height=120> 

#### Success and Failure cases of Detection
<img src="https://github.com/Dherya27/Motion_Planing/blob/main/detect_success.png" height=200> <img src="https://github.com/Dherya27/Motion_Planing/blob/main/detection_failure.png" height=200> 

Region of Interest(ROI) is too small in second picture, so it's difficult for model to detect.

## Unique Counting of Bicyclist by Siamese Network
<img src="https://github.com/Dherya27/Motion_Planing/blob/main/siamese_network.png" width=465 height=285>   <img src="https://github.com/Dherya27/Motion_Planing/blob/main/unique_counting.png" width=440 height=285> 

#### Triplet Samples
<img src="https://github.com/Dherya27/Motion_Planing/blob/main/Easy_negative.png" width=300 height=200> <img src="https://github.com/Dherya27/Motion_Planing/blob/main/hard_positive.png" width=200 height=200> <img src="https://github.com/Dherya27/Motion_Planing/blob/main/hard_negative.png" width=320 height=200> 









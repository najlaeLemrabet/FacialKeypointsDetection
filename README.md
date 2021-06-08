# Facial Keypoints Detection

In this repository a regressor was trained to predict keypoint positions on face images, a 15 keypoints representing the various coordinates on the human face. 
The repository includes:
- jupyter notebook containing all the steps: data loading ,data preprocessing, training, testinh
- Pre-trained weights

## DATASET
The dataset from kaggle contained 2 directories : train, test
each is a csv file containing the image and the keypoints of :\

- ***3 keypoints for each right and left eye:****
'left_eye_center_x', 'left_eye_center_y', 'right_eye_center_x', 'right_eye_center_y', 'left_eye_inner_corner_x', 'left_eye_inner_corner_y', 'left_eye_outer_corner_x', 'left_eye_outer_corner_y', 'right_eye_inner_corner_x', 'right_eye_inner_corner_y', 'right_eye_outer_corner_x', 'right_eye_outer_corner_y', 

- ***2 keypoints for each eybrow:***
'left_eyebrow_inner_end_x', 'left_eyebrow_inner_end_y', 'left_eyebrow_outer_end_x', 'left_eyebrow_outer_end_y', 'right_eyebrow_inner_end_x', 'right_eyebrow_inner_end_y', 'right_eyebrow_outer_end_x', 'right_eyebrow_outer_end_y',

- ***1 keypoint for the noise :***
'nose_tip_x', 'nose_tip_y'

- ***4 keypoints for the lips:***
'mouth_left_corner_x', 'mouth_left_corner_y', 'mouth_right_corner_x', 'mouth_right_corner_y', 'mouth_center_top_lip_x', 'mouth_center_top_lip_y', 'mouth_center_bottom_lip_x', 'mouth_center_bottom_lip_y'

- Below is an example of an annotated image:

<p float="left">
  <img src="/assets/annotated_image.PNG" width="200"  height="200" title="NORMAL" />
</p>
Kaggle Dataset : https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/data


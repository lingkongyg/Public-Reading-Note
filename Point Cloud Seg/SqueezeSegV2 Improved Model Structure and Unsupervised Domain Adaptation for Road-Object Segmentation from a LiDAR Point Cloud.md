# SqueezeSegV2 Improved Model Structure and Unsupervised Domain Adaptation for Road-Object Segmentation from a LiDAR Point Cloud

- Step 1 Title/Abstract/Figures

- Step 2 Intro(skim related works) + Conclusions + Figures + Skim rest

- Step 3 All but skip math

- Step 4 Whole thing but skip parts that don't make sense

## What did authors try to accomplish?

- Upgrade SqueezeSeg to be more robust against dropout noise in LiDAR point cloud.
- Use synthetic point cloud data to adapte real world scenario.

## What were the key elements of the approach?

- Newly proposed Context Aggregaion Module can reduse the sensitivity to dropout noise, mainly due to maxpooling
- Focal loss between the synthetic label and prediction, plus geodesic loss between synthetic and real data, as the loss function
- asdf

## What can you use yourself?

Domain adaptation method

## What other references do you want to follow

Apply domain adaptation method to more widly different datasets.

---
license: cc-by-4.0
task_categories:
- image-classification
tags:
- leaves
- plants
- custom-dataset
---
# Leaf Classification Dataset (own photos)

Photos of leaves of three houseplants taken in a home garden with a Samsung Galaxy A54, collected for an Advanced AI assignment
(KNN classification, K-Means and Agglomerative clustering).

## Classes
| Class | Images |
|---|---|
| arrowhead | 35 |
| money | 35 |
| spider | 35 |

## Structure
`<class_name>/<class>_NNN.jpg` - one folder per class. `Leaf_Dataset_Image_Log.xlsx` records lighting, background, distance and orientation for each photo.
`leaf_features.csv` holds the extracted numerical features used in the analysis.

## Collection procedure
Each photo shows a different leaf. Conditions were varied: direct sun / shade / indoor-evening, backgrounds (white paper, ground, hand, wall),
distance (close / medium / far) and orientation (flat / tilted / rotated). No filters or zoom. EXIF metadata (including GPS) was removed before upload.

## Limitations
Small dataset (~105 images), leaves from a limited number of plants in one garden, natural lighting only.

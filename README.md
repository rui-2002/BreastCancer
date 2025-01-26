# BreastCancer

## About the Dataset


This dataset is based on a digitized image of a fine needle aspirate (FNA) of a breast mass. The features in this dataset describe the characteristics of the cell nuclei present in the image. The dataset is used for breast cancer diagnosis, where the goal is to classify tumors as either **malignant** or **benign**.

The dataset is based on the work described in the paper:  
[K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This dataset is available from the UW CS FTP server:
- FTP server: `ftp ftp.cs.wisc.edu`
- Directory: `cd math-prog/cpo-dataset/machine-learn/WDBC/`

It is also available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).

## Attribute Information

1. **ID number**: Unique identifier for each sample.
2. **Diagnosis**: 
   - **M** = Malignant
   - **B** = Benign
3. **Features (3-32)**: Ten real-valued features are computed for each cell nucleus. These features describe the geometric properties of the cell nuclei extracted from the image.

### Feature List:
- **a)** Radius: Mean of distances from the center to points on the perimeter.
- **b)** Texture: Standard deviation of gray-scale values.
- **c)** Perimeter
- **d)** Area
- **e)** Smoothness: Local variation in radius lengths.
- **f)** Compactness: (Perimeter² / Area) - 1.0
- **g)** Concavity: Severity of concave portions of the contour.
- **h)** Concave Points: Number of concave portions of the contour.
- **i)** Symmetry
- **j)** Fractal Dimension: Coastline approximation - 1.

For each of these features, the dataset provides:
- **Mean** value
- **Standard Error** (SE)
- **Worst** value (Mean of the three largest values)

For example:
- Field 3 is **Mean Radius**
- Field 13 is **Radius SE**
- Field 23 is **Worst Radius**

### Data Properties:
- All feature values are recorded with four significant digits.
- **Missing attribute values**: None.

### Class Distribution:
- **357 Benign** samples
- **212 Malignant** samples

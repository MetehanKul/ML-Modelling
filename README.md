## Project Description
This project focuses on analyzing breast cancer data with the aim of building a machine learning model for cancer diagnosis. The dataset is part of the "Women Coders' Bootcamp" organized by Artificial Intelligence for Development in collaboration with UNDP Nepal. It contains features computed from digitized images of fine needle aspirates (FNA) of breast masses, describing the characteristics of the cell nuclei present in the images.

![Breast Cancer](https://user-images.githubusercontent.com/36210723/182301443-382b14e1-71c1-46ac-88f5-e72a9b2083e7.jpg)




### Dataset Features
The dataset includes several key features that provide insights into the cellular structure, which are critical for diagnosis. These features were selected using an exhaustive search method and include characteristics such as:

- **Radius**: Average distance from the center to points on the perimeter of the nuclei.
- **Texture**: Standard deviation of the grayscale values.
- **Perimeter**: The total distance around the nucleus.
- **Area**: The area of the nuclei.
- **Smoothness**: The local variation in radius lengths.
- **Compactness**: (perimeter^2 / area) - 1.0

### Methodology
The classification model was developed using the Multisurface Method-Tree (MSM-T), which employs linear programming techniques for decision tree construction. This method allows for the effective separation of classes in a multidimensional feature space.

### References
The approach utilized for constructing the decision tree is detailed in the works of K. P. Bennett, including:
- "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992.
- "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets," Optimization Methods and Software 1, 1992, 23-34.

## Conclusion
This analysis and model aim to enhance breast cancer diagnosis accuracy, potentially aiding healthcare professionals in making more informed decisions. By leveraging machine learning techniques, the project contributes to the broader goal of using technology for social good in health care.

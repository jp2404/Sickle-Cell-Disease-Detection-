Image Dataset Optimization for Machine Learning This project provides a method to optimize image datasets by selecting the top images in each class based on brightness and zoom level, helping to reduce dataset size while maintaining image quality and diversity. The approach is designed to support robust model performance by curating high-quality images even with limited data.

Key Features:

Brightness Scoring: Measures image brightness using the V (brightness) channel in HSV color space.

Zoom Level Estimation: Calculates an estimated zoom level by assessing the area of the largest contour in a grayscale, thresholded version of the image.

Combined Scoring for Selection: Normalizes brightness and zoom scores, combining them with customizable weights to rank images. This ensures the highest-quality images are selected based on both metrics.

Customizable Dataset Reduction: Allows selection of a specific number of top images per class, tailored to support training and testing requirements.

We have also attested a sample of ResNet50 Model trained on triplet loss with XAI results for your reference.

# -Car-Dataset-
Prospect Auto ML Project: Automated vehicle (Bus, Car, Van) classification using geometric features from silhouettes (Compactness, Circularity, Elongatedness, Aspect Ratios, etc.). Applies Supervised Learning to optimize fleet management by accurately identifying vehicle types based on their shape.

ML Project: “Prospect Auto” - Automated Vehicle Classification
Project Goal: The "Prospect Auto" project aims to develop an automated system for vehicle recognition and classification. The primary challenge is to accurately identify and categorize vehicle types (Bus, Car, Van) based on their geometric properties, with the ultimate goal of optimizing and intelligently managing vehicle fleets.

Approach: Our system relies on Supervised Learning techniques, utilizing geometric features extracted from vehicle silhouettes viewed from various angles. The dataset comprises a sample of vehicles, categorized into three main classes: Bus (specifically a double-decker bus), Van (like a Chevrolet van), and Car (including models such as Saab 9000 or Opel Manta).

Geometric Features: We analyze a set of 18 geometric features. The most significant ones, crucial for capturing the geometric and structural characteristics essential for fine-grained classification, include:

Compactness: Measures the density of the contour relative to its area.
Circularity: Assesses the similarity of the silhouette to a perfect circle.
Elongatedness: Indicates the degree to which the object is stretched.
pr.axis_aspect_ratio: The ratio of the length to the width of the ellipse approximating the object.
Hollows_ratio: Measures the presence of depressions or cavities in the shape.
Distance_circularity: A measure of deviation from circularity.
Max.length_aspect_ratio: Ratio of the maximum dimensions.
Scatter_ratio: Represents the scatter of the points.

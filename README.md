# mesh_pcd_similarity_finder
This repository contains a novel algorithm for robust and accurate similarity assessment between meshes and point clouds in 3D shape analysis. Our approach leverages a two-stage process:

Dependencies

Open3D
Pandas
GUDHI
Trimesh
PyVista
Scikit-learn
NumPy
SciPy
copy


Explanation of Key Features

Geometric Feature Extraction:

Oriented Bounding Box (OBB) dimensions: Provides a standardized representation of a mesh's scale and orientation.
Betti numbers (topological complexity): Captures the number of holes or loops in the shape, offering insight into its structural complexity.
Variance metrics from surface normals and triangle areas: Measures variation in surface curvature and local feature density.
Fast Point Feature Histograms (FPFH): Creates a descriptive local representation of the shape.
Refined Alignment and Comparison:

Enhanced Iterative Closest Point (ICP) algorithm: Iteratively finds the optimal transformation to align two shapes.
Random Sample Consensus (RANSAC): Robustly handles outliers and noise during the alignment process.


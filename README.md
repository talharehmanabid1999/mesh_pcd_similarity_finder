# mesh_pcd_similarity_finder
This repository contains a novel algorithm for robust and accurate similarity assessment between meshes and point clouds in 3D shape analysis. Our approach leverages a two-stage process:

Geometric Feature Extraction:

Oriented Bounding Box (OBB) dimensions
Betti numbers (topological complexity)
Variance metrics from surface normals and triangle areas
Fast Point Feature Histograms (FPFH)
Refined Alignment and Comparison:

Enhanced Iterative Closest Point (ICP) algorithm with Random Sample Consensus (RANSAC) for precise alignment of top candidate matches.
Key Innovations

Geometric and Topological Analysis: Combining both types of features provides a more comprehensive shape understanding for the initial similarity assessment.
Robust Pre-filtering: Geometric feature extraction reduces computational expense by narrowing down the search space.
Precision Alignment: Enhanced ICP with RANSAC tackles challenges in accurately aligning shapes with diverse scales and orientations.

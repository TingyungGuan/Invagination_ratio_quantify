# Invagination_ratio_quantify
A mesh-based pipeline for quantifying invagination ratio of nucleus via curvature classification. The pipeline was developed based on the method described by Biedzinski et al. (2020) (https://www.embopress.org/doi/10.15252/embj.2019103957). 
We improved the classification step by introducing a neighborhood voting system and a bridging function to connect disconnected concave areas, resulting in more consistent and robust segmentation.

# Features
1. Split the mesh containing multiple objects.

2. Simplify meshes while preserving structural integrity.

3. Estimate principal curvatures using patch fitting.

4. Classify surface regions as concave or convex based on curvature.

5. Quantify the invagination ratio (concave area / total surface area).

6. Export classification results and visualisations.

# How to Use
1. Download the Jupyter Notebook from this repository.

2. Install required Python packages (if not already installed).

3. Place all the .obj mesh files you wish to analyse into a fresh folder.

4. Open the notebook, modify the file paths and parameters accordingly.

5. Run the notebook step-by-step to perform mesh splitting, simplification, curvature analysis, classification, and result export.

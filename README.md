# Leonardo Vanni

**3D and 4D computer vision** · Incoming M.Sc. Mathematics in Science and Engineering, Technical University of Munich

I build computer vision systems that reconstruct moving 3D scenes and estimate when their predictions can be trusted. My work covers 3D/4D reconstruction, egocentric vision, multiple-view geometry, Gaussian Splatting, and uncertainty estimation for 3D foundation models.

[leonardovanni.com](https://leonardovanni.com) · [Research CV](https://leonardovanni.com/cv/leonardo-vanni-research-cv.pdf) · [LinkedIn](https://www.linkedin.com/in/leonardo-vanni/) · [info@leonardovanni.com](mailto:info@leonardovanni.com)

---

## Research

**Current work (2026 – present)** — Two first-author manuscripts under review at a 3D vision venue: one on 4D reconstruction of dynamic egocentric scenes, one on reliability estimation for 3D foundation models. Code will be released on acceptance. Details on the [research page](https://leonardovanni.com/research/).

**[SE(3) Uncertainty for VGGT](https://leonardovanni.com/thesis/)** — B.Sc. thesis, Bocconi University, 2026
Extends VGGT with a lightweight branch that predicts full 6×6 camera-pose covariances on SE(3) while keeping the frozen mean-pose pathway. A single temperature calibrates the uncertainty; its structure matches bundle-adjustment covariances and it flags mislocalized frames, giving the model a built-in failure detector. Validated on CO3D and EPIC-KITCHENS.

**[Prosthetic Arm Vision](https://github.com/VanniLeonardo/Prosthetic-Arm)** — Computer Vision Lead, BAINSA & Politecnico di Milano, 2024 – 2025
Real-time pipeline combining object detection, monocular depth, segmentation, hand tracking, and Kalman-filtered 3D state to decide whether a grasp is feasible before an EEG-controlled prosthetic hand closes. GUI demonstrator, containerized deployment. [Report](https://www.researchgate.net/publication/393399982_Vision-Based_Grasp_Validation_for_Prosthetic_Arms_using_3D_Scene_Analysis).

## Open source

**[Kornia](https://github.com/kornia/kornia)** — contributor since June 2026

- Stereo disparity metrics: MAE, RMSE, and bad-pixel ratio, with tests and documentation ([#3743](https://github.com/kornia/kornia/pull/XXXX))
- Removed import-time TorchScript decorators across `kornia.geometry` ([#3757](https://github.com/kornia/kornia/pull/3757))

## Focus

- **Geometry:** multiple-view geometry, SE(3) and Lie-group uncertainty, bundle adjustment, dynamic-scene reconstruction
- **Learning:** Gaussian Splatting, 3D foundation models, calibration and confidence-based abstention
- **Stack:** Python, PyTorch, CUDA, NumPy/SciPy, OpenCV, COLMAP, ROS2, Docker, Weights & Biases

## Background

- **M.Sc.** Mathematics in Science and Engineering, TUM — Oct 2026 – Sep 2028 (expected). Focus: robotics perception, multiple-view geometry, 3D learning.
- **B.Sc.** Mathematics and Computing Sciences for AI, Bocconi University — 110/110 cum laude, 2026. Exchange semester at École Polytechnique (GPA 4.3/4.0).
- Previously: Computer Vision Researcher at Vision Dental (CT reconstruction, 3D U-Net segmentation, voxel-level uncertainty); ML Engineer at Accenture; Head of Research at BAINSA, mentoring 60 student researchers.

---

Open to computer vision research and engineering roles in Munich, Zurich, and Paris.

# Project: I-Spy AI Object Solver
**UConn Data Science & Engineering | Automated Object Detection System**

## Project Description
This project utilizes Computer Vision and Deep Learning techniques to solve complex "I-Spy" visual puzzles. By implementing a custom TensorFlow model, the system is designed to perform object localization within highly cluttered environments. The model is trained to recognize specific targets across varying lighting conditions, angles, and backgrounds.

## The Project Team
Kenny
member
member

---

## Technical Resources and Data
| Resource Type | URL | Purpose |
| :--- | :--- | :--- |
| **Dataset** | [Roboflow Dashboard](https://universe.roboflow.com/ispyaisolverdata/ispy-ai-project) | Hosted imagery and annotation metadata |
| **Training Lab** | [Google Colab](https://colab.research.google.com/drive/1zN8oT6azPIjsTrP-FAPz1r29f30O4Bsz?usp=sharing) | Model training scripts and performance metrics |

## Key Technical Features
* **Custom Dataset Generation**: Includes over 200 original images captured under diverse environmental conditions.
* **Transfer Learning Implementation**: Utilizes a pre-trained SSD MobileNet backbone for efficient inference.
* **Automated Localization**: Provides real-time bounding-box visualization for all identified target classes.

## Technology Stack
* **Languages**: Python 3.9+
* **Core Frameworks**: TensorFlow 2.x, OpenCV
* **Development Tools**: Git, GitHub, Roboflow, VS Code

## Project Directory Structure
* `/data`: Local directory for raw image storage (Git-ignored).
* `/models`: Storage for serialized model weights and saved checkpoints.
* `/notebooks`: Interactive Jupyter/Colab notebooks for development.
* `/scripts`: Production-ready Python files for model execution.
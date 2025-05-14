# Neuro240
Neuro240

Code corresponding to each key checkpoint:

1. Midterm Report: Neuro240Midterm.iypnb
This notebook covers the foundational phase of the project, where the core convolutional neural network (CNN) was designed, built, and debugged from scratch.
	•	Defined and implemented a custom CNN architecture optimized for binary classification (“mass” vs “no finding”) using the NIH ChestX-ray14 dataset.
	•	Experimented with different layer configurations, activation functions, and regularization strategies.
	•	Preprocessed raw image data, including resizing, normalization, and basic dataset construction.
	•	Mainly code for data loading, visualization, model compilation, and early testing.

Focus: Pure CNN model engineering — from dataset construction to working architecture.

2. Close to the finish line: Neuro240FinalProject.ipynb and Neuro240AlmostThereCode.ipynb
Despite the names, these notebooks represent the main experimentation and performance evaluation phase, and contain experiments that were run all the way from right after the midpoint until the final project submission
	•	Ran a series of comparative training experiments across three dataset sizes:
	•	Minimal (250 images),
  • Baseline (500 images),
	•	Maximal (1,000 images),
	•	Full Dataset (7,000 images).
	•	Tested effects of class weighting, random noise augmentation, and training dataset scaling. This resulted in a total of over 12 different models being trained and evaluated.
  • Evaluated the effects in combination with each other and in isolation to isolate the effect each had and establish a causal link.
	•	Measured and plotted model performance (accuracy, AUC) across these conditions.
	•	Logged model behavior across epochs, explored performance/calibration issues, and examined confusion matrices.

Focus: Controlled experimental design and analysis of generalization performance under different model training regimes. This stage involved extensive iterative coding, parameter tuning, and data tracking.

3. Final Project Report: AM_Neuro240_FinalProject_Submission
This notebook contains the final stage of the project, focused on model interpretability and synthesis.
	•	Applied Grad-CAM to visualize which regions of chest X-rays contributed most to the CNN’s predictions, providing insight into the model’s decision-making process.
	•	Used these visualizations to qualitatively assess whether the model’s attention aligned with radiologically plausible regions.
	•	Integrated key results from prior experiments into a coherent final report, highlighting how data size, class balancing, and augmentation influenced performance.

Focus: Interpreting model behavior through Grad-CAM and summarizing project findings in a clear, well-documented form.

4. Some additional work was done in the checkpoint and almost there, code, this was primarily done for testing and evaluation of experimental design and approaches.

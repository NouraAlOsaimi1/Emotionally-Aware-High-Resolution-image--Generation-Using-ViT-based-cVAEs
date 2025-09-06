# Emotionally-Aware-High-Resolution-image--Generation-Using-ViT-based-cVAEs
In this project, we designed a hybrid generative model that combines the global attention capabilities of Vision Transformers (ViT) with the structured latent control of Conditional Variational Autoencoders (cVAE) to generate facial images that are not only realistic but also emotionally aligned. Developed by me & my team as part of our Advanced Artificial Intelligence course.
What makes our work special:
	•	It tackles the challenge of generating emotionally expressive facial images in high resolution.
	•	We integrated a CNN encoder, a ViT-based decoder, and a high-resolution refinement head to boost visual fidelity.
	•	We trained our model on a curated dataset of 38,000+ labeled grayscale facial images across 7 core emotions (e.g. Happy, Sad, Fear, etc.).

Evaluation metrics:
	•	FID Score: 232.70
	•	Inception Score: 1.47 ± 0.09
	•	Emotion classification accuracy also showed promising results, demonstrating improved emotional consistency over traditional cVAE models.

The project also dives into:
	•	A detailed literature review on the limitations of standalone ViTs and VAEs
	•	Comparative model outputs with and without resolution refinement
	•	Ethical concerns regarding facial data usage and emotional bias
	•	Future directions including emotion intensity control, video-based generation, and fairness optimization


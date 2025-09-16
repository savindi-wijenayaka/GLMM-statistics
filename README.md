# GLMM statisitcs

Statistical analysis of PTA stain vs iodine stain quality in micro CT imaging using generalized linear mixed-effect models (GLMMs) for the paper titled: Detailed MicroCT Imaging Protocol for Ex Vivo Rat Stomachs with Comparative Analysis.

Quantitative comparison of signal-to-noise ratio (SNR), contrast-to-noise ratio (CNR), and mean intensity is supported by the GLMMs. SNR and mean intensity were assessed using n = 260 data points, and CNR using n = 130, from 9 PTA-stained and 4 iodine-stained experiments. All GLMM models utilized a Gamma distribution with a log link function and were fitted using the Laplace approximation to maximum likelihood. Fixed effects included Stain for the SNR and CNR models, and Stain and Tissue for the mean intensity model. The fixed effect of Tissue was not retained in the final SNR model, as preliminary analysis
indicated no significant effect (p > 0.05) when included. Experiment and ROI were included as random effects. P-values and confidence intervals were derived using bootstrapping for robust inference. Model-derived group means are reported as estimated mean ± standard error.

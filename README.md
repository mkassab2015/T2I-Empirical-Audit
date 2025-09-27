# T2I-Empirical-Audit

This repository contains data, scripts, and supporting materials for a study investigating demographic and stylistic patterns in AI-generated images. The dataset includes 880 images generated from multiple models using role-based prompts, along with both human-coded and automated annotations.



\# Repository for Image Bias Audit Study



This repository contains data, scripts, and supporting materials for a study investigating demographic and stylistic patterns in AI-generated images.  

The dataset includes 880 images generated from multiple models using role-based prompts, along with both human-coded and automated annotations.



---



\## Repository Structure



\### 📂 Data \& Results

\- \*\*Generated Images (880 Images)\*\*  

&nbsp; Complete set of generated images across roles and models.



\- \*\*Images Data (Analysis per Model)\*\*  

&nbsp; Excel sheet with demographic and stylistic attributes aggregated by model.



\- \*\*Images Data (Analysis per Role)\*\*  

&nbsp; Excel sheet with results aggregated by role prompts.



\- \*\*Images Data\*\*  

&nbsp; Master Excel dataset containing all coded attributes (e.g., gender, race/ethnicity, age group, facial expression, composition).



\- \*\*Additional Analysis per Models\*\*  

&nbsp; Supplementary breakdowns and figures for model-level comparisons.



\### 📂 Analysis Scripts

\- \*\*analysis\_notebook.py\*\*  

&nbsp; Python script for reproducing analyses and generating visualizations.



\- \*\*DeepFace Analysis and Script\*\*  

&nbsp; Scripts and outputs from the DeepFace library, used for automated demographic and sentiment analysis.



\### 📂 Documentation

\- \*\*Coding Book (Used for coder training)\*\*  

&nbsp; Codebook guiding human coders in classifying demographic and stylistic attributes.



\- \*\*Image Analysis Prompt (Used to Prompt Models)\*\*  

&nbsp; List of text prompts used to generate the dataset across different roles and models.



---



\## Usage



1\. \*\*Explore the data\*\*: Start with `Images Data.xlsx` for the full annotated dataset.  

2\. \*\*Reproduce analyses\*\*: Use `analysis\_notebook.py` or scripts in `DeepFace Analysis and Script/`.  

3\. \*\*Understand methodology\*\*: Refer to the `Coding Book` and `Image Analysis Prompt`.  

4\. \*\*Check extended results\*\*: See `Additional Analysis per Models/` for supplementary findings.



---



\## Citation

If you use this repository, please cite the associated \*\*forthcoming publication\*\* (details to be added after review).



---



\## License

This repository is released for academic and non-commercial use only.




# Analytical Ltp Software
# Brief Description
**LTP Analytical Software** is novel software to analyzing Long-Term Potentiation (LTP) data, a key synaptic process essential for memory and impacted by neurodegenerative diseases. We will employ advanced time series analysis, machine learning, and feature selection techniques to improve data normalization, ensure quality control, standardize workflows, and detect otherr biologically significant regions in LTP waveforms. The result will be a cutting-edge tool for LTP data analysis, with the potential to identify early Alzheimer's disease pathological hallmarks.<img src="https://github.com/user-attachments/assets/92601708-33a5-4d87-97ab-89fed99a42d2" width="200" />
## Project Collaborator
**LTP Analytical Software** :Novel software integrates potentiation, time-series, spatial and temporal features to find patients’ clinical characteristics explaining differences in long-term potentiation recordings. **Collaborators: Beheshti Dehkordi Mohammadamin, Gomez Budia Mireia, Pelkonen Anssi and Malm Tarja, Giudice Luca** 

## Features & options
1. Introduce a **standardized workflow** for analyzing and comparing potentiation across samples.
2. Provide a **consensus** on LTP waveform analysis methods (e.g., operations, thresholds, parameters).
3. Biologically analyze **the rest of LTP waveform**
4. **Advanced Time Series Analysis and Signal Preprocessing**:such as bandpass filtering, down-sampling, and smoothing, followed by artifact detection.
5. **Quality Control through unsupervised machine learning and feature selection** to avoid data oversimplification.
6. **Spatial (with respect to electrode positions) and Temporal** Analysis of LTP Waveforms.
7. **Comprehensive Dataset Integration**:The project integrates features extracted from LTP waveforms with clinical data from **Idiopathic Normal Pressure Hydrocephalus (iNPH) patients**, including pathology, demographics, and genetic information. This comprehensive dataset allows for a robust analysis and potential discovery of correlations between LTP features and patient characteristics.
8. **Machine Learning Classifier** for **Disease Pathology Identification**: **A supervised Random Forest classifier** is employed to associate LTP waveforms with **Alzheimer's-related pathologies (e.g., amyloid-β, tau)**. The classifier's performance is optimized using **Grid Search**, and its predictive accuracy is assessed with **cross-validation** and **SHAP values**, which help explain the contribution of different features to the classification.
9. **Development of User-Friendly Software**:
The final output of the project is software that applies the developed methods to analyze LTP data. The software will include a **web-based graphical interface (Gradio)** and will be packaged for easy installation and use across different studies.
## Results
**We have tested our proposed method on an samall number (n=7) of Idiopathic Normal Pressure Hydrocephalus (iNPH) samples. The results are as follows:**

**1. LTP Induction:** The method successfully induced Long-Term Potentiation (LTP) across the samples, demonstrating the effectiveness of our approach in eliciting and capturing synaptic responses.

**2. Potentiation Measurement**: Our method provided potentiation measurements by analyzing individual waveforms, leading to more accurate assessments of potentiation intensity. The results showed a clear increase in potentiation among electrodes neighboring the stimulated ones.

**3. Spatial and Temporal Correlations**: The method identified significant spatial correlations, with electrodes near the stimulation site displaying higher potentiation. Temporal correlations were also observed, indicating that potentiation intensity varied over time.

**4. Classifier Performance**: The initial classification of waveforms based on Alzheimer’s pathology showed promising results, with high accuracy in distinguishing different pathological signatures.

# Install options
**Under Prepration ...**

## Sub-Projects
**For this project, we are developing three sub-projects simultaneously explplored in the following.**

 [Validating Long-Term Potentiation (LTP) Measurement with Old school style](Validating_Long_Term_Potentiation_(LTP)_Measurement_with_OLD_school_style.ipynb):</a> Our first project involved **developing a potentition measurment analysis using an old-school approach**. We averaged waveforms before and after stimulation to determine if there was any enhancement in synaptic activity, specifically to measure potentiation. The main purpose of this first project was to **validate** whether we could **successfully induce Long-Term Potentiation (LTP)** and to **compare the accuracy of our novel method** against existing literature. Code exist in (- Old-style-potentiation)

[Investigating potentition measurments with different Potentiation Features:](Investigating_potentition_measurments_with_different_Potentiation_Features.ipynb)
</a> In the second project, we investigated different **potentiation features**, such as **minimum peak, area under the curve, and amplitude**. The goal was to assess whether using different potentiation features significantly impacts on the final results of **potentiation measurment**, and if so, to **analyze how**. Code exist in (LTP_Code_potentiation_3_different_metrices_v1)

**Developing Novel Analytical Software for LTP Analysis**</a>: The third and **primary** project focused on **developing new analytical software with a novel potentiation method**. This method leverages **quality control, machine learning (both supervised and unsupervised), and feature selection algorithms** to enhance current analysis of LTP data.(code exist in Novel Analytical software LTP)



## Workflow and Dataset Description 
![Amin's First Illustration (10)](https://github.com/user-attachments/assets/b20ab8e9-08bd-482b-8ab5-effd68c3b477)
**Figure 1A.** Cartoon depicting an MEA (Microelectrode Array) - the device which record LTP waveforms.
**1B.** Idiopathic Normal Pressure Hydrocephalus (iNPH) patients from Kuopio University Hospital - the human cortical samples obtained from surgery. 
**1C.** Representative image of a slice on a Microelectrode Array (MEA).
**2A.** Long-Term Potentiation (LTP) waveform recorded for 90 minutes, with a 1.05-second interval per waveform recording. The recording is divided into baseline, post-TBS, and TTX phases.
**2B.** Potentiation regions are extracted.  
**2C.** TTX is used for denoising, and baseline amplitude will be subtracted from post-TBS to create potentiation.
**2D.** Features of each waveform are extracted. 
**2E.** All features from all patients are integrated together.
## Application and Significant 
We will develop a novel biological model and a user-friendly, accessible tool for analyzing time series LTP data by standardizing workflows on methodology, establishing consensus on different definitions, and exploring previously overlooked LTP waveform regions. This tool will improve our understanding of synaptic plasticity, particularly LTP and its relationship with neurodegenerative diseases like Alzheimer's. The outcomes of this software could be used in the development of new therapeutic strategies.
## License
**Under Prepration ...**

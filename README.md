# NeuroMatch
# 🧠 Tiny Rodents: NMA ISP Micropublication Project

This repository contains the code and data used in the Neuromatch Academy 2024/25 Impact Scholar Program micropublication:

**Title**: *Dissecting Neural Contributions to Decision-Making: The Contribution of Brain Regions and Neuron Subtypes in Choice Prediction*  
**Authors**: Abu M. Z. Al Rahman, Arthur R. Rodrigues (UFMG), Maria C. Vergara, Elena Torchinskaya, Yasaman M. Safaei, Nikolai Safronov, Mayank Mehta (UCLA)  
**Platform**: Neuromatch Academy, 2024/25  
**Link to paper**: _(to be added upon Zenodo publication)_

## 📌 Summary

This study investigates how spiking activity from different brain regions in the mouse cortex and hippocampus predicts behavioral choices in a visual discrimination task. Using data from Steinmetz et al. (2019), we:
- Analyzed spike data from CA3, DG, ACA, MOp, and MOs
- Applied logistic regression and SVM classifiers to decode choice and correctness
- Examined how signal timing and accuracy evolve with task difficulty
- Visualized hierarchical flow of decision-related activity
- Distinguished excitatory vs inhibitory contributions via waveform duration

## 🧪 Key Methods
- Logistic regression & SVM classification (time-resolved)
- Dimensionality reduction (UMAP, PCA)
- Cross-temporal generalization analysis
- PSTH generation and latency analysis
- Graph-based metrics (modularity, small-worldness)
- Cell-type classification (based on waveform peak-to-trough)

## 🛠️ Tools
- Python 3.11, NumPy, SciPy, Matplotlib
- Data: Steinmetz et al. (2019) Neuropixels dataset
- Analysis hardware: AMD Ryzen 9 7600, 32GB DDR5 RAM

## 💡 Future Directions
- Integrate optogenetic silencing to verify circuit causality
- Extend classification models to thalamus and basal ganglia
- Test generalization to non-visual tasks and species
- Implement closed-loop BCI using real-time neural predictors

## 📁 Repository Contents
- `Neuromatch_TinyRodents_ArthurRodrigues.zip`: Contains all analysis code and plots
- `README.md`: Project summary
- [Link to Zenodo / DOI will be added once published]

---

🔬 For inquiries, contact: **arthurribeirorodrigues94@gmail.com**


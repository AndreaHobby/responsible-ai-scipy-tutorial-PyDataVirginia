# Responsible AI Using SciPy

**PyData Virginia 2025 Tutorial**

## Overview

90-minute hands-on tutorial on implementing Responsible AI principles using SciPy and Python, presented at PyData Virginia 2025. Demonstrates practical approaches to bias detection, sensitivity analysis, and model explainability in healthcare and social impact applications.

## Tutorial Content

### Responsible AI Principles Covered

- **Fairness:** Bias detection and mitigation across demographic groups
- **Transparency:** Model explainability and interpretability techniques
- **Accountability:** Sensitivity analysis and uncertainty quantification
- **Privacy & Security:** Safe handling of protected attributes
- **Safety:** Validation approaches for high-stakes decisions

### Hands-On Tutorials

**Tutorial 1: Bias Detection and Mitigation Using SciPy**
- Statistical tests for demographic parity and equalized odds
- Measuring disparate impact across protected groups
- Reweighting and threshold optimization for fairness
- Case study: Healthcare risk prediction fairness analysis

**Tutorial 2: Sensitivity Analysis with SciPy**
- Parameter perturbation and stability testing
- Monte Carlo simulation for uncertainty quantification
- Robustness checks for model decisions
- Case study: Clinical decision support sensitivity testing

**Tutorial 3: Transparent and Explainable ML Models**
- Feature importance using statistical methods
- Partial dependence plots and individual conditional expectation
- SHAP values integration with SciPy
- Case study: Explaining algorithmic decisions to non-technical stakeholders

## Repository Structure
```bash
.
├── notebooks/           
│   ├── tutorial_1_bias_detection.ipynb          # Fairness analysis
│   ├── tutorial_2_sensitivity_analysis.ipynb    # Robustness testing
│   └── tutorial_3_explainability.ipynb          # Model transparency
├── data/
│   ├── case_data.csv                            # Synthetic healthcare data
│   └── datainfo.md                       # Variable descriptions
├── slides/
│   └── PyData_Virginia_2025_Slides.pdf          # Presentation slides
├── requirements.txt                              # Python dependencies
└── README.md
```

## Getting Started

### Prerequisites
```bash
# Python 3.8+
# Recommended: Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Installation
```bash
# Clone repository
git clone https://github.com/AndreaHobby/PyDataVirginia](https://github.com/AndreaHobby/responsible-ai-scipy-tutorial-PyDataVirginia.git
cd responsible-ai-scipy-tutorial-PyDataVirginia

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

### Required Packages

- `scipy` - Statistical computing and scientific computing
- `numpy` - Numerical operations
- `pandas` - Data manipulation
- `scikit-learn` - Machine learning utilities
- `matplotlib`, `seaborn` - Visualization
- `shap` - Model explainability (Tutorial 3)

## Key Takeaways

1. **Fairness is measurable:** Statistical tests can quantify algorithmic bias across demographic groups
2. **Transparency builds trust:** Explainable models are essential for high-stakes decisions (healthcare, lending, hiring)
3. **Robustness matters:** Sensitivity analysis reveals model stability and appropriate use cases
4. **SciPy is powerful:** Core scientific computing library enables sophisticated fairness and explainability analyses
5. **Context is critical:** Responsible AI requires domain expertise, not just technical skills

## Use Cases

This tutorial framework applies to:
- **Healthcare:** Clinical decision support fairness, treatment recommendation bias
- **Finance:** Lending algorithm audits, credit scoring fairness
- **HR/Hiring:** Resume screening bias detection, interview score analysis
- **Government:** Public service allocation, benefits eligibility fairness
- **Education:** Admissions algorithms, grading systems equity

## Skills Demonstrated

- Algorithmic bias detection and mitigation
- Statistical fairness metrics implementation
- Sensitivity analysis and robustness testing
- Model explainability techniques
- Healthcare AI ethics and responsible development
- Python scientific computing (SciPy, NumPy)
- Technical communication and teaching

## Conference

**PyData Virginia 2025**  
January 2025 | Charlottesville, VA

PyData brings together users and developers of data analysis tools to share ideas and learn from each other, with focus on Python-based tools for data science, machine learning, and analytics.

## About the Presenter

**Andrea Hobby**  
Healthcare Data Scientist | DrPH Student, Johns Hopkins Bloomberg School of Public Health

Andrea specializes in algorithmic bias in healthcare AI, health equity analytics, and patient safety. Her doctoral research examines fairness and safety implications of clinical decision support systems. She previously contributed to federal AI governance frameworks as a member of the HHS Artificial Intelligence Community of Practice.


**Connect:**
- **GitHub:** [@AndreaHobby](https://github.com/AndreaHobby)
- **LinkedIn:** [Andrea Hobby](https://www.linkedin.com/in/andreahobby/)
- **Newsletter:** [Health Innovation](https://healthinnovation.substack.com/) - Healthcare AI, algorithmic bias, and health equity
- **Email:** ahobby1@jh.edu

## Citation

If you use or reference this tutorial in your work:
```
Hobby, A. (2025). Responsible AI Using SciPy. 
Tutorial presented at PyData Virginia 2025, Charlottesville, VA.
https://github.com/AndreaHobby/responsible-ai-scipy-tutorial-PyDataVirginia
```

## License

Tutorial materials are provided under MIT License for educational use. See LICENSE file for details.

## Acknowledgments

Thanks to PyData Virginia organizers and participants for the opportunity to share practical approaches to Responsible AI implementation.

---

## Additional Resources

**Responsible AI Frameworks:**
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [Google's Responsible AI Practices](https://ai.google/responsibility/responsible-ai-practices/)
- [Microsoft's Responsible AI Resources](https://www.microsoft.com/en-us/ai/responsible-ai)

**Algorithmic Fairness:**
- Mehrabi et al. (2021). "A Survey on Bias and Fairness in Machine Learning." ACM Computing Surveys.
- Barocas, Hardt, Narayanan. "Fairness and Machine Learning" (fairmlbook.org)

**Healthcare AI:**
- [FDA's Proposed Regulatory Framework for AI/ML](https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-aiml-enabled-medical-devices)

---

*This tutorial demonstrates practical implementation of Responsible AI principles using accessible Python tools. For consultation on algorithmic bias audits, fairness evaluations, or healthcare AI governance, contact the presenter.*
```

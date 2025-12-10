# Lungvision: Seeing the Future of Asthma Risk

## Description and Goals

Lungvision aims to develop an early diagnostic tool for asthma, a condition that is typically diagnosed through patient interviews, physical examinations, and subjective medical assessments. Currently, these methods are often costly and not ideal for early detection. This project seeks to create a predictive model based on biomarkers to identify asthma risk and categorize it into childhood or adulthood-onset asthma. The goal is to integrate this model into healthcare systems as a diagnostic tool during routine physical exams and raise awareness about asthma's complexity and its biomarkers.

### Key Goals

- Create a model for early asthma detection to prevent life-threatening attacks and avoid unnecessary tests
- Integrate the model as a part of periodic medical exams, applicable to both children and adults
- Raise awareness about the complexity of asthma and environmental and physical factors affecting its prognosis
- Develop a rapid test to categorize asthma as childhood or adulthood-onset

### Success Criteria

- **Accuracy:** The model should accurately predict whether a person has asthma and its type/severity
- **Reliability:** The model should provide consistent and accurate results, making it a reliable first-line diagnostic tool
- **Ease of Use:** The model should be easy for healthcare professionals to interpret and use
- **Acceptability:** The model should be robust enough for adoption by both the medical community and the general public
- **Room for Improvement:** The model should be extensible, allowing for future updates with new research and biomarker data

## Getting Started

### Dependencies

To run this project, you'll need the following libraries:

```bash
pandas
numpy
scipy
xgboost
scikit-learn
matplotlib
seaborn
joblib
shap
os (built-in)
glob (built-in)
```

Install the necessary libraries by running:

```bash
pip install pandas numpy scipy xgboost scikit-learn matplotlib seaborn joblib shap
```

### Installing

1. Clone this repository to your local machine
2. Download the following Jupyter notebooks from the repository:
   - `Data_cleaning_and_preprocessing.ipynb`
   - `Asthma_models.ipynb`
   - `Asthma_onset_model.ipynb`
   - `Visualisations.ipynb`

3. Run the notebooks in this order:
   1. `Data_cleaning_and_preprocessing.ipynb`
   2. `Asthma_models.ipynb`
   3. `Asthma_onset_model.ipynb`
   4. `Visualisations.ipynb`

### Repository Structure

```
DATA PREPROCCESING/
    └── Contains dataset files used for making the merged datasets model training and analysis

Scripts/
    ├── Data_cleaning_and_preprocessing.ipynb
    ├── Asthma_models.ipynb
    ├── Asthma_onset_model.ipynb
    └── Visualisations.ipynb

Output Files/
    ├── ASTHMA MODEL OUTPUT/
    ├── ASTHMA ONSET OUTPUT/
    └── VISUALIZATIONS/
```

## Executing the Program

To execute the program, follow the order mentioned in the Installing section. Each notebook has specific steps to run, which will take you through:

1. Cleaning and preprocessing the data
2. Training the models and making predictions
3. Visualizing the results

You can open and run the Jupyter notebooks using an IDE or a Jupyter notebook server.

## Help

If you encounter issues, here are some troubleshooting tips:

- **Missing libraries:** Ensure all dependencies are installed using `pip install`
- **File paths:** Double-check that the DATASETS folder and script paths are correct and files are in place
- **Model issues:** Check if the dataset is formatted correctly, especially if it's not matching the expected input format for the models

For further questions or issues, feel free to reach out via GitHub Issues or contact the contributors.

## Authors

- **Ericsson David** - [@EricssonDavid7](https://github.com/EricssonDavid7)
- **Fabricio Montero Zuñiga** - [@fabriciomz24IMIM](https://github.com/fabriciomz24IMIM)
- **Deepta Susan Beji** - [@Deepta2020](https://github.com/Deepta2020)

## Version History

- **0.1** - Initial Release: Created data preprocessing, model training scripts, and visualizations

## Acknowledgments

**Inspiration:** This project was inspired by the need for early detection and accurate categorization of asthma.

**References:**
- World Health Organization, 2013
- National Institute for Care and Excellence, 2024
- Buhl et al., 2020
- Lavere et al., 2025
- CDC: Centers for Disease Control and Prevention/National Center for Health Statistics

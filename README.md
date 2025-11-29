# [Your Project Title Here]

> **⚠️ IMPORTANT: Your repository must be set to PRIVATE before submission. Go to Settings → Change visibility → Make private. Delete this warning once you have confirmed your repository is private.**

> **Instructions:** Replace the placeholder text in brackets with your actual information. When ready to submit, you can rename this file to `README.md` (after backing up the original template README if needed).

## Project Information

| **Course** | CIVE70111 Machine Learning |
| **Academic Year** | 2025/2026 |
| **Submission Date** | 12/12/2025 |



## Group Information

**Group 5:** 

| Name | CID | GitHub Username |
|------|-----|-----------------|
| [Marsol Ferrer, Sergi] | [Student 4 CID] | [@username4] |
| [Sanchez Gomez, Maria Lucia] | [Student 4 CID] | [@username4] |
| [Castro Barandica, Juan Camilo] | [Student 4 CID] | [@username4] |
| [Desai, Yusayrah] | [Student 4 CID] | [@username4] |
| [Yasser, Bilal] | [Student 4 CID] | [@username4] |
| [Vethakarn, Chanaporn] | [06050391] | [@ChanapornV] |



## Executive Summary

[Write a concise summary (150-300 words) describing:
- What is the purpose of this project?
- What data did you use?
- What methods/techniques did you apply?
- What are your key findings or results?
- What are the main conclusions?]

## Project Structure

```
your-project/
├── README.md                  # This file
├── requirements.txt           # Python package dependencies
├── data/                      # Data files (not committed to git)
├── notebooks/                 # Jupyter notebooks
│   ├── 00-report.ipynb
│   ├── 01-[description].ipynb
│   ├── 02-[description].ipynb
│   └── 03-[description].ipynb
├── src/                       # Source code
│   └── [your modules].py
└── docs/                      # Additional documentation
```

## How to Run

[Explain how to run your code and reproduce your results. Assume the reader has already created a conda environment and installed packages from requirements.txt]

1. [First step - e.g., "Run the data preprocessing notebook"]
   ```bash
   jupyter notebook notebooks/01-data-preprocessing.ipynb
   ```

2. [Second step - e.g., "Run the analysis notebook"]
   ```bash
   jupyter notebook notebooks/02-analysis.ipynb
   ```

3. [Continue with additional steps...]

**Note:** [Add any important notes about data files, such as:]
- Data files should be placed in the `data/` folder
- Download data from [source/URL] if not included
- [Any other setup notes]

[Optional: Include command-line instructions if you have Python scripts]
```bash
python src/your_script.py
```

## Data Sources

[Document all data sources used in your project]

- **[Dataset Name 1]**
  - Source: [URL or description]
  - Access Date: [Date]
  - Description: [Brief description]
  - Citation: [Proper citation if required]

- **[Dataset Name 2]**
  - Source: [URL or description]
  - Access Date: [Date]
  - Description: [Brief description]
  - Citation: [Proper citation if required]

## Methodology

[Provide a brief overview of your approach and methods]

1. **Data Collection:** [Describe how you obtained the data]
2. **Data Cleaning:** [Describe preprocessing steps]
3. **Analysis:** [Describe analytical methods used]
    - task 3 : 
        -

    - task4 : Classification of Operating Conditions
        - develop machine learning models to categorize optimal or suboptimal
        - compare 3 models : Logistic Regression, Random Forest and Support Vector Machines (SVM)
        - evaluated performance using F1-Score
    
    - 

4. **Visualization:** [Describe how you visualized results]

[For more detailed methodology, you can reference specific notebooks or documentation files]

## Results

[Summarize your key findings]

- [Key finding 1]
- [Key finding 2]
- [Key finding 3]
- In Task 4, the Random Forest classifier demonstrated superior performance compared to Logistic Regression and SVM, achieving a near-perfect F1-Score of 0.999 for detecting operational conditions. Feature importance analysis identified MODULE_TEMPERATURE, IRRADIATION, and AMBIENT_TEMPERATURE as the primary drivers for the model's decisions. Additionally, comparative experiments revealed that the 'Class Weighting' technique did not yield performance improvements for the Random Forest model, suggesting that the algorithm's decision trees could effectively isolate fault patterns without artificial balancing.
[notebooks/04_operating_condition_classification.ipynb]


[You can include links to specific notebooks or figures]
See [notebooks/03-results.ipynb](notebooks/03-results.ipynb) for detailed results and visualizations.

## Conclusions

[Summarize your main conclusions and their implications]

[Optional: Include limitations and future work]

## Individual Contributions (Group Projects Only)

<!-- Delete this section if individual project -->

> **Note:** Individual contributions are tracked through Git commit history. This section provides a high-level summary.

**[Student 1 Name]:**
- [Contribution area 1, e.g., "Data collection and cleaning (notebooks/01-data-loading.ipynb)"]
- [Contribution area 2, e.g., "Statistical analysis (src/analysis.py)"]
- [Contribution area 3, e.g., "Documentation (README.md, methodology)"]

**[Student 2 Name]:**
- [Contribution area 1]
- [Contribution area 2]
- [Contribution area 3]

**[Student 3 Name]:**
- [Contribution area 1]
- [Contribution area 2]
- [Contribution area 3]

**[Vethakarn, Chanaporn]:**
- [Contribution in Developed classification models for operating conditions]
- [Implemented and tuned Logistic Regression, Random Forest, and SVM classifiers]
- [Applied class weighting techniques to address the dataset imbalance]

**[Student 4 Name]:**
- [Contribution area 1]
- [Contribution area 2]
- [Contribution area 3]

**Joint contributions:**
- [Areas where team members collaborated, e.g., "Code review, testing, and integration"]

## Use of AI Tools

> **Important:** Disclose any use of AI tools (ChatGPT, GitHub Copilot, Claude, etc.) as per course policy.

<!-- Choose one of the following statements and delete the others: -->

**Option 2 - AI tools used:**
The following AI tools were used in this project:

- **[Tool Name, e.g., ChatGPT]**
  - Purpose: [e.g., "Used to debug Python code errors"]
  - Extent: [e.g., "Approximately 5% of code development"]
  - Specific instances: [e.g., "Helped resolve pandas DataFrame indexing issue in notebook 02"]

- **[Tool Name, e.g., GitHub Copilot]**
  - Purpose: [e.g., "Code completion suggestions"]
  - Extent: [e.g., "Used throughout development for boilerplate code"]
  - Note: [e.g., "All AI-generated suggestions were reviewed and tested"]

- **[Gemini]**
  - Purpose: code debugging and optimization 
  - Extent: Used primarily for guidance on how to implement, import, and structure machine learning models within the Jupyter Notebook environment
            debug code and suggest improvemeant part
  - Note: All AI-generated suggestions were reviewed and tested

**Important:** All code generated or suggested by AI tools was thoroughly reviewed, understood, and tested by the project team. We take full responsibility for all submitted work.

## Dependencies

See [requirements.txt](requirements.txt) for a complete list of dependencies.

Key packages:
- Python 3.11
- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn
- [Add other key packages]

## References

[List any references, citations, or resources used]

1. [Author(s). (Year). Title. Source. URL]
2. [Reference 2]
3. [Reference 3]

[Include academic papers, documentation, Stack Overflow answers, tutorials, etc.]

## Acknowledgments

[Optional: Acknowledge any help received, such as:]
- Course instructors and teaching assistants
- Peers who provided feedback (without sharing code)
- External resources or tools

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Repository:** [Link to your GitHub repository]
**Last Updated:** [Date]
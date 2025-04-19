#  Machine Learning Classification Project | WEKA

This repository contains our **Artificial Intelligence Project #2**, focused on implementing and evaluating **three machine learning algorithms** using **WEKA** on an audio-based Accent dataset.

---

##  Authors

- **Hala Jebreel** 
- **Diana Naseer**

**Course:** ENCS3340 – Artificial Intelligence  


---

##  Project Overview

We applied and analyzed the performance of the following classification algorithms using **WEKA**:

1. **Decision Tree (J48)**
2. **Naïve Bayes**
3. **Multilayer Perceptron (MLP)**

**Dataset Used:**  
 Accent Dataset (selected as group ID % 3 → 0)

---

## Methodology

###  Preprocessing
- Discretization: All attributes were binned (bins = 2).
- Data was visualized before and after discretization.

###  Classification Techniques
Each algorithm was evaluated using:
- 5-Fold Cross Validation
- Default hyperparameters
- Custom parameter tuning (e.g., confidence factor, batch size)

###  Metrics Used
- Accuracy (Correctly classified instances)
- Precision, Recall, F-Measure
- TP, FN, FP, TN breakdowns

---

##  Results Summary

| Algorithm       | Accuracy   | Best Precision | Best Recall | Best F-Measure |
|----------------|------------|----------------|-------------|----------------|
| Decision Tree  | 75.37%     | 0.643          | 0.692       | 0.667          |
| Naïve Bayes    | 75.37%     | 0.635          | 0.684       | 0.658          |
| MLP            | 75.37%     | 0.658          | 0.641       | 0.649          |

➡ **MLP and Naïve Bayes performed best in our tests** based on accuracy and F-measure.

---

##  Demo

A visual explanation and summary are included in:

-  `Project 2_Ai_1210363_1210606 - Made with Clipchamp.mp4`

---

##  Files Included

| File Name                                            | Description                                     |
|-----------------------------------------------------|-------------------------------------------------|
| `DianaNaseer_1210363_HalaHamed_1210606_Project2.pdf`| Full report including methodology and results   |
| `Project 2_Ai_1210363_1210606 - Made with Clipchamp.mp4` | Video summary and walkthrough (MP4)         |

---

##  Conclusion

This project provided valuable hands-on experience in:
- Preprocessing audio features
- Applying and tuning ML classifiers
- Interpreting classification results
- Using WEKA as a machine learning tool

We concluded that:
> **Hyperparameter tuning** slightly improved performance, but overall accuracy remained close across all models.

---

##  License

This project is for academic and educational purposes only.

---

##  Acknowledgments



> Built with teamwork, data, and dedication 

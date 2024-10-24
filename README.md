# OPTIMIZING-FETAL-HEALTH-PREDICTION-USING-CNN-WITH-DROPOUT
## INTRODUCTION :
Fetal growth analysis is crucial for prenatal care, providing insights into fetal well-being and development. Early detection of inadequate growth can help prevent serious complications, impacting both maternal and infant health. With rising pregnancy-related health issues, timely monitoring is essential to improve outcomes, aligning with the UN's Sustainable Development Goal 3 of promoting well-being for all.

Machine learning (ML) and deep learning (DL) offer powerful tools for fetal health prediction, with techniques like logistic regression, support vector machines, and convolutional neural networks (CNNs) showing promise in analyzing medical data. This project explores CNNs with dropout regularization to enhance predictive accuracy and real-time monitoring, aiming to improve prenatal care and maternal-infant health globally.

## SCOPE OF THE PROJECT :
Fetal Health Prediction focuses on developing a prediction portal using the MERN stack and deep learning to analyze Cardiotocogram data for accurate fetal health diagnosis. The project includes data collection, feature engineering, and model development (Random Forest, MLP, CNN). Deliverables include a trained model, a user-friendly interface, and documentation. Limitations include data constraints, resource needs, and potential variability on unseen data. Medical expert validation is essential for ensuring clinical relevance. Real-time monitoring and certain risk factors are excluded from the scope.

## EXISTING SYSTEM :
Current fetal health monitoring relies on cardiotocography (CTG) to assess fetal well-being, but its interpretation depends on clinician expertise, risking variability in diagnosis. Traditional methods also struggle with complex data and limited diagnostic accuracy. Machine learning (ML) and deep learning (DL) techniques, like logistic regression and CNNs, offer enhanced classification accuracy, yet many models face challenges like overfitting and poor generalization. Advanced algorithms are needed to leverage medical data more effectively for improved fetal health prediction and outcomes.

## PROPOSED SYSTEM :
The proposed system uses a CNN architecture tailored for fetal health prediction based on cardiotocography (CTG) signals. It classifies fetal health into Normal, Moderate, and Pathological categories by processing fetal heart rate and uterine contractions. Dropout layers help mitigate overfitting, enhancing generalization. Techniques like batch normalization and early stopping stabilize training. While a stacking ensemble approach was tested, the dropout-enhanced CNN consistently outperformed, proving its effectiveness in accurate classification. This system supports healthcare professionals in optimizing prenatal care by providing precise fetal health assessments.

## MODEL ARCHITECTURE :
![image](https://github.com/user-attachments/assets/14da282d-ff86-4885-ba1d-5591edb3a41d)


## OUTPUT :
### Pair Plot of Fetal Health Features with Risk Categories
![image](https://github.com/user-attachments/assets/7f750917-3e7c-4709-a4e0-eb14c180fb1e)

### Distribution of Baseline FHR
![image](https://github.com/user-attachments/assets/b6fa1891-b9df-40b8-bde7-57b0fa917afc)


### Accuracy Graph
![image](https://github.com/user-attachments/assets/cee38ba6-7aaa-473c-afe8-cfb473fd3459)


### Loss Graph
![image](https://github.com/user-attachments/assets/e65e7420-d11a-496c-bebd-914e77068e25)


## REFERENCES :
[1] Subrota, Mazumdar., Rohit, Choudhary., Aleena, Swetapadma. (2017). An innovative method for fetal health monitoring based on artificial neural network using cardiotocography measurements. 265-268. doi: 10.1109/ICRCICN.2017.8234518 [2] Mehdi, Fasihi., Mohammad, H., Nadimi-Shahraki., Ali, Jannesari. (2021). 5. A Shallow 1- D Convolution Neural Network for Fetal State Assessment Based on Cardiotocogram. doi: 10.1007/S42979-021-00694-6 [3] Shen, Liyue, et al. "Deep learning with attention to predict gestational age of the fetal brain." arXiv preprint arXiv:1812.07102 (2018). [4] Jiarui, Feng., Jennifer, Lee., Zachary, A., Vesoulis., Fuhai, Li. (2021). Predicting mortality risk for preterm infants using deep learning models with time-series vital sign data. 4(1) :108-. doi: 10.1038/S41746-021-00479-4 [5] Płotka, Szymon, et al. "FetalNet: Multi-task deep learning framework for fetal ultrasound biometric measurements." Neural Information Processing: 28th International Conference, ICONIP 2021, Sanur, Bali, Indonesia, December 8–12, 2021, Proceedings, Part VI 28. Springer International Publishing, 2021.

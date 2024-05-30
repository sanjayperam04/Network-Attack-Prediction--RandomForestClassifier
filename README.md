# Network Attack Prediction using RandomForestClassifier
 This project predicts normal or attack based on input features using a RandomForestClassifier model. Users input features via a text box in the web interface, receiving predictions labeled "Normal" or "Attack". Gradio library facilitates user interaction. Error handling ensures smooth operation.

## Features
### Data Preprocessing
- **Feature Selection**: A comprehensive approach is employed to select the most relevant features for training the model. This involves correlation analysis and standard deviation to identify and remove least correlated and least informative features.
- **Dimensionality Reduction**: Principal Component Analysis (PCA) is utilized to reduce the dimensionality of the feature space while retaining essential information, thereby enhancing model efficiency and performance.

### Model Training and Evaluation
- **RandomForestClassifier Training**: The RandomForestClassifier is trained on the preprocessed data to accurately predict different attack types. 
- **Model Evaluation**: Rigorous evaluation is conducted using ROC curves, providing insights into the model's ability to discriminate between different attack types and its overall performance.

### Hyperparameter Tuning
- **GridSearchCV Optimization**: Hyperparameters of the RandomForestClassifier are meticulously tuned using GridSearchCV to identify the optimal configuration that maximizes model accuracy and generalization.

### User Interface Integration
- **Gradio Integration**: The notebook seamlessly integrates with Gradio, a user-friendly library for creating interactive interfaces. This integration facilitates effortless input of features and immediate visualization of predictions.
- **Interactive Experience**: Users can input features via a text box, interact with the model in real-time, and receive instant predictions labeled as "Normal" or "Attack", thereby enhancing user accessibility and engagement.

## Dataset
- **NSL KDD Dataset**: The project utilizes the NSL-KDD dataset for training and evaluation. This dataset is a refined version of the widely-used KDD Cup 1999 dataset, specifically designed for intrusion detection research.

## Installation
## Usage
1. **Open Notebook**: Launch the notebook in a Jupyter environment.
2. **Execute Cells**: Execute the cells sequentially to load data, preprocess it, train the model, and create the interactive interface.
3. **Input Features**: Input features separated by spaces into the provided text box.
4. **Receive Predictions**: Obtain predictions labeled as "Normal" or "Attack" in real-time, facilitating efficient decision-making and analysis.
## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

## Credits
- Developed by Rupin Ajay, Rudra, Rohith, Sukrith, Sanjay, Raya
- Based on [Gradio](https://github.com/gradio-app/gradio) and [Scikit-learn](https://github.com/scikit-learn/scikit-learn)

## Acknowledgments
Special thanks to the developers of Gradio and Scikit-learn for providing excellent libraries for creating interactive web interfaces and machine learning functionalities, respectively.

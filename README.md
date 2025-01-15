<a name="readme-top"></a>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#meet-the-team">Meet The Team</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

## About The Project

This project is an application used to predict whether a user will be approved for a loan or not using several different machine learning algorithms, as using the publically available [Loan-Approval-Predicition-Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset).

When the program is run, users will be asked several questions about their financial and familial circumstances. This information will be cross-compared with the .csv dataset in order to give the user a more solid idea on whether they can expect to recieve a loan.

In particular, nine different machine learning classifiers, as implemented with tools such as Pandas, Keras, and Tensorflow, are run to decide the likelihood of the user attaining a loan. The results of each classifier's prediction are shown at the bottom of the program. These classifiers are:

- K-Nearest Neighbor (KNN) Classification,
- Decision Tree Classification,
- Logistic Regression Classification,
- Support Vector Machine (SVM) Classification,
- Ensemble Learning Classification techniques, which include:
  * Stacking Classification,
  * Bagging Classification,
  * Boosting Classification,
  * Neural Network Classification.
 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Meet The Team

Work on the project was a collaborative effort between five different members, each of whom implemented a different machine learning algorithm and code implementations for use with the program:

- [Ryan Coveny (Nqnt41)](https://github.com/Nqnt41) - Team leader, developed the input and output systems, KNN analysis, as well as some of the ensemble learning methods - averaging, bagging, and stacking.
- [Jack Ditzel (riptidereef)](https://github.com/riptidereef) - Created the bar graph data visualizations at the end of the program, created the text summary of results, and developed both the neural network implementation and boosting.
- [John Struckman (JohnnyStruk)](https://github.com/JohnnyStruk) - Performed data cleaning and preparation. Also developed the Logistic Regression Classifier code.
- [Ben Pratt (EAOzone)](https://github.com/EAOzone) - Created the Decision Tree Classifier as well as the large scale tree visualization present alongside the decision tree code.
- [Juan Rodriguez (JagerRager)](https://github.com/JagerRager) - Developed the implementation for Support Vector Machine analysis.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Built With

The core of the project uses Python with the Jupyter Notebook, as supported by the Anaconda Navigator. Anaconda is not needed to run the program, however, thanks to the environment.yml file.

Program dependencies include:
- Jupyter,
- Pandas,
- Seaborn,
- Matplotlib,
- Scikit-Learn,
- Imblearn,
- Keras,
- Tensorflow.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Getting Started

### RECOMMENDED - Using environment.yml to install dependencies:

This method should work with all IDEs, although it has been primarily tested using Visual Studio Code.

1. Ensure [Anaconda](https://docs.anaconda.com/anaconda/install/) or [Miniconda](https://docs.anaconda.com/miniconda/install/) is set up and installed.
2. Use the given command in the terminal to create the necessary Python environment on the local directory containing this repository's files:
  ```sh
  conda env create --file environment.yml
  ```
3. Activate the environment through the given command:
  ```sh
  conda activate loan_approval_env
  ```
4. Finally, if necessary, configure your IDE to use and interact with this environment. In Visual Studio Code, this is simply done with the Kernel Selection option in the .ipynb file, for example.

### If using the Anaconda Navigator and manually installing dependencies:

1. Create a new Anaconda environment set in Python version 3.9. A command that can accomplish this is below:
  ```sh
  conda install -c conda-forge keras
  ```
3. Manually add the following dependencies: jupyter, pandas, seaborn, matplotlib, scikit-learn, and imbalanced-learn.
4. Use the following two commands to install Keras and then Tensorflow:
* Keras
  ```sh
  conda install -c conda-forge keras
  ```
* Tensorflow
  ```sh
  conda install tensorflow
  ```
  * Note: [If using an M-Series Mac, the tutorial in this hyperlink should be used to install Tensorflow](https://youtu.be/xEBrzVYsuBc?si=aO7Am15ypTac69U-).
4. Run Jupyter Notebook using the created environment and open the .ipynb file to use the program.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Contributing

If you have any ideas for how to improve this project, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Added a new feature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

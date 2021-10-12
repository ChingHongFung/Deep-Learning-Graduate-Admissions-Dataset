# Deep Learning: Graduate Admissions Dataset

This is a project looking at a graduate admissions dataset. The objective is to use a feature set composing students' past academic performance to predict the probability of college admission. Data is available via https://www.kaggle.com/mohansacharya/graduate-admissions

A deep learning approach is used where I built and optimised a feedforward neural network using packages TensorFlow, Keras and SciPy. Optimision is done on a set of hyperparameters including batch size, epochs, early stopping, number of hidden layers, number of neurons per layer, regularistion terms (drop-out layers), etc. For evaluation, I used a loss function of mean squared error (applicable for linear regression problem) and monitored the mean squared error for early stopping purposes. I also plotted learning curves for either metrics for training and cross validation sets throughout each iteration to see how the model could be improved. More details of the step-by-step iterative process could be found in the Jupyter Notebook document.

#### Final model architecture:
![model_architecture_final_iteration](https://user-images.githubusercontent.com/91271318/136998845-12d11fe6-80c4-47bd-a2d9-ff3a8cdb786d.png)

#### Final model compilation and errors:
Final MAE metric: 0.05015536 \n
R2 metric (coefficient of determination): 0.8065634109200266
![model_compilation_final_iteration](https://user-images.githubusercontent.com/91271318/136999897-722b5c00-3480-4101-9c9e-1cc5e9c44e9a.png)

#### Final model learning curves:
![learning_curve_final_iteration](https://user-images.githubusercontent.com/91271318/136998843-76fdcd86-bcd5-48fe-8f5a-bd7facfcbbd2.png)

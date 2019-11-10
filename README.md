# Classification

* Classification is the action or process of categorizing something according
to shared qualities or characteristics.


* Clasification is the prediction of discrete outcomes. Outcomes are identified as 
labels/discrete outputs, which serve to categorize bi-class and multi-class features.


* Clasification is used to forecast and predict financial outcomes, automate underwritting and insurance premiums, detect and categorize health issues and 
overall health.

* Classification models have drastically improved financial efforts to properly categorize applicants, predict market decline , and categotize fradulent transactions
or suspicious activity.

* FICO credit scoring uses a classification model for its cognitive fraud analytics platform. Classification enginies have allowed the financial industry to become more effective and efficient at mitigating risk.



  # Clasiffication:

There are multiple approaches to classification. These include:

  # Logistic Regression


   * logistic regression is a common approach used to classify data points and make predictions.

   * Predictions are made by creating linear paths between data points.

   * Data points along the trajectory are normalized between 0 and 1.

   * If a value is above a certain threshold, the data point is considered either of clases 0 or 1.

   * Prediction is not 100% accurate. There is room for error, as well as false positives.


   * Running a logistic regression model involves 4 steps, which can be applied when running any machine-learning model:

        * Preprocess
        * Train
        * Validate
        * Predict





   # What is better : the false positive or false negative?

False positive, additional tests can be ran to refine the prediction and filter out individuals who do not have diabetes. This way, those with the potential of having it can be given the treatment and attention they need.

In addition to accuracy, a model must be measured for precision and recall, both of which can be used to eliminate false positives and false negatives.




# Accuaracy, Precision, Recall


Accuaracy, precision and recall are specially important for classification model that involve a binary decision problem. Binary decision problems have two possible correct answers: **True Positive** and **True Negative**


Innaccurate and imprecise models result in models returning false positives and false negatives.


* Accuracy is how ofter the model is correct - the ratio of correctly predicted observations to the total number of observations.

* Precision is the ratio of correctly predicted positive observations to the total predicted positive observations.

* Recall is the ratio of correctly predicted positive observations to all predicted observations for that class.



# Confusion Matrix 

A **confusion matrix** is used to measure and gauge the success of a model. Also, reveal the number of true negatives and true positives (actuals) for each categorical class and compares it to the number of predicted values for each class. 



n = 165 


                    Predicted: NO |     Predicted: YES
_________________|________________|______________________
**Actual=NO**    |      50        |     10                 = 60
_________________|________________|______________________
**Actual=YES**   |      5         |     100                = 105
                   = 55               = 110


These values are then individually summed by column and row. The aggregate sums are then compared to gauge accuracy and precision. If the aggregates match, the model can be considered accurate and precise.



* Precision = 100/(100+100) = ~91%
* Recall = 100/(100+ 5) = ~95%  
* F1 Score = 2*( 95% * 91%) / (95% + 91%) = 2* 0.86/1.86 = 1.71/1.86



# Support Vector Machines (SVM)

SVM is a supervised learning model that can be used for classification and regession analysis. SVM separates classes of data points into multidimesional space.

 **Linear Classifiers** 

 Linear classifiers attempt to draw a line that separates the data, but which line best separates the groups?

 * The SVM algorithm finds the optimal hyperplane that separates the data points with the largest margin possible.

 * The space is segmented by a line or plane that groups data points into their respective classes.

 * The goal with the hyperplanes is to get the margin of the hyperplane equidistant to the data points for all classes.

 * The data closest to/within the margin of the hyperplane are called support vectors, and they used tio define boundaries of the hyperplane.

 * Hyperplanes can be used clearly delineate classes in multiple dimensions.

 **Zero tolerance with perfect partition** Hyperplane also supports what is considered zero tolerance with perfect partition, which is a nonlinear hyperplane that will position and orient the hyperplane to correctly classify overlapping or outlying data points.

 In order to stablish zero tolerance with perfect partition, the SUPPORT VECTOR MACHINES model may introduce a new z-axis dimension for nonlinear hyperplanes.

 **SVM Model**

 Steps to implement an SVM model include:

 * Create the model with appropiate **Kernel** parameters.
 * Fit the model.
 * Extract min and max decision boundaries and store in a mesh grid.
 * Execute the **decision_function** to get classifier scores for pre-existing data points.

 * Run the **predict** funtion to classify new data points.


 

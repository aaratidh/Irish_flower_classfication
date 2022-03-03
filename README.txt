Irish Flower Classification Using Tensoflow in Anconda

Steps 1: 
	Importing and installing necassary libaraies 

Step 2: Reading the data 

step 3: Visualizing data: 
        Scatter plot: 
        For visualization of the dataset I have used scatter plot which is always fascinating.
        The intresting thing about scatter plot is it allow us to show the distribution of three different class of the species in a single figure.
        Scatter plot makes it easier to use different color for different types of species Iris-setosa,Iris-versicolor,Iris-virginica in a single graph.
        I have used REd blue green for respective color.
        
 	Pair plot: 
        This is another important weapon for visualization of the data. It helps to identify the best set of the variable to classify the data. 
	Most of the times the model for the classification can be achived by simple set of the linear relation between two features.
        In our case, pair polt clearly specify the we can seperate the cluster simply using petal width on on y-axis and petal length on x-axis.
        But we are heading to mke some use of tenswaor flow so we leave if potential if else model behind.

Step 5: Data prosessing: 
        This is our dataset we have a range of values for example the one pf the sepal length is in 5.2 range where as another se tof petal width has value of 0.2.
        so, we need for scaling of the dataset for better accuracy. The accuracy is highly affected by the range of the data in the dataframe. Normalizaing the dataset 
	into the same scale directly reduces the computational time for machine learning.Generally, the are two method for scaling of the data set one is standralization 
	and another is normalization. I have used sklearn standardlization for scaling the data. As the last columns species has the value in string form.
	I use label encoder to convert into interger form. 

Step 6: Spliting Traning and testing sets 
	Sklearn test_train split function is used for splitiing the tranning and testing data. I used 30% of data for testing and remaining 70% for training of the data.
	Before spliting the dataset into test and train form we seprated the fetaures and target value all the features were placed in the X variable and traget values is placed in Y 
	variable.
     

Step 6: Classifying the dataset 
	I have used Logistic model for the classification of the data. Logistic regression is very simple yet very powerful method for the machine learning.
	On the other hand, skleran has speed up all the process using the machine learning process. All we need to do is to import the model and then train 
	the model and predict the model.

Step 7: Making conclusion 
        From scatter plot we can see that Iris-setosa had wider sepal than of the versicolor and virginica.
        where as virginica  species has longer sepal length than remaning rest of them. The versicolor species turn out to be of average of the both with and length. 
	The accuracy result turn out to be a quite high about 95%. This might be due to standarlization and logistic regression is also a very effective model for prediction.
	I have used confusion matrix for display of the result which shows that 43 out of 45 data has been correctedly predicted. Only tow of them were false. For accuracy 43/45 = 95%   

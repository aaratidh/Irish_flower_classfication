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
	and another is normalization. I have used standardlization for scaling in the dataset.

Step 6: Spliting Traning and testing sets 

Step 6: Classifying the dataset 

Step 7: Making conclusion 
        From scatter plot we can see that Iris-setosa had wider sepal than of the versicolor and virginica.
        where as virginica  species has longer sepal length than remaning rest of them. The versicolor  species turn out to be of average of the both with and length. 

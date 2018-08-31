# PredictingChurn
Predicting Customer Churn
Implementation in Java to predict customer churn

How to set up

First, you need to make sure that you have Java Editor, JDK 1.7, weka 3+, wekar.jar and weka-src.jar (weka libraries from weka 3+) installed on your system. 

Then follow the following steps to run the application:
Go to command prompt and type "git clone https://github.com/TaiwoK/PredictingChurn.git" to clone the project

Go to Java Editor and click on File then select Import, select from ZIP
Click on Browse to locate the directory you cloned the project to 
Click on Import
Open the project in your Java Editor

Open file Menu.java and and right click on the file, select run
Menu.java is the application interface for you to perform your analysis

To convert your dataset in csv format to Arff format
Click on File on the Menu bar
Select Load Data and locate where you stored your data (csv format)
Locate where you want to store the arff file and enter filename.Arff (Ensure you put the extension .Arff)
Click on File again and select Convert csv to Arff format

To perform Clustering
Click on Clustering on the Menu bar
Select SimpleKMeans or EM(Expected Maximization)
You will be prompted to select the Arff file
Locate and select Arff file you converted and click on open
Type the number of clusters and click on ok
See the output on the console

To exit the applicationClick on File
Select Exit

Dataset Description

Dataset: SUMMARIZEDCALLRECORDS.csv
The dataset in csv format was converted to Arff format called cluster2.Arff

The dataset consists of the the listed attributes in the following order:

Subscriber 				# telecom customer represented by a unique id

Call Ratio 				#the proportion of calls which has been made by each subscriber to his/her total number of calls (incoming and outgoing calls)

Average Call Distance 	#the average time distance between one’s calls

Life 					# the period of time in the observed time span in which each subscriber has been active.

Max Distance 			# the maximum time distance between two calls of a specific subscriber in the observed period

Max Date 				# the last date in our observed period in which a subscriber has made a call

Min Date 				# the first date in our observed period in which a subscriber has made a call

No of Days 				# number of days in which a specific subscriber has made or received a call

Total No In 			# the total number of incoming calls for each subscriber in the observed period

Total No Out 			# the total number of outgoing calls for each subscriber in the observed period

Total Cost 				# the total money that each subscriber has been charged for using the services in the specific time period under study

Total Duration In 		# the total duration of incoming calls (in Sec) for a specific subscriber in the observed time span

Total Duration Out 		#The total duration of outgoing calls (in Sec) for a specific subscriber in our observed time span

To make use of this code cite as: Kolajo, T. and Adeyemo, A. B. (2012). Data mining technique for predicting telecommunications industry customer churn using both descriptive and predictive algorithms. Computing, Information Systems and Development Informatics Journal. 3(2): 27-34.

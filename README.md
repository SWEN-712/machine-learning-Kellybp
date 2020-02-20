The idea behind the code is that it is implemented along side https://towardsdatascience.com/using-azure-cognitive-services-for-sentiment-analysis-of-trumps-tweets-part-1-f42d68c7e40a

In the notebook that grabs the tweets I added two things;
		Preprocessing
		Word filters

	The intention of the preprocessing was to allow users the ability to make a dictionary based on 
	new lines rather than comas and to then move the data to a csv file format for use in various machine learning applications.
	For the most part, I commented out the preprocessing in python to differentiate it from the word filters. 

	The intention of the word filters (simple regex) is to allow users to pick and choose which tweets to save based on the words that
	they contain. In the example submitted, the word filters are based on some of the accessibility related terms I noted being mentioned.

How to run
	As mentioned earlier, the code should coincide with https://towardsdatascience.com/using-azure-cognitive-services-for-sentiment-analysis-of-trumps-tweets-part-1-f42d68c7e40a.

	I have broken the code segments into two sections following the two segment structure of the tutorial.

	Following the tutorial, I have broken the code segments into commands separated by cmdN---------, so they can be more easily transferred to databricks.





	See video for examples.

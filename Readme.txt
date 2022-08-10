Important libraries for the scraper: 
        -anaconda3
	-textblob (install using pip install textblob)
	-selenium (pip install selenium)
	Note for selenium: in order for the scraper to work you need to download the proper 
        ms edge browser driver and place the executable in a class's PATH directory. (For us we used C:/Users/user/anaconda3/Scripts)
	-link to driver: https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
	-nltk (pip install nltk)
Important libraries for the neural network:
	-tensorflow (pip install tensorflow)
	-pyplot, pyplot plus, and graphviz for creating the model graph (pip install pyplot pyplotplus graphviz)

Running instructions: 
	Run Depression_Neural_Net for a quick look to the NN with testing data readied (tweetData.csv and testData.csv)
	Note: if you wish to test on other files you can run the scraper or any of the "number@_____" files. 
	(In the create predictions block there is a line pred_data = pd.read_csv("testData.csv")) edit this file to your choosing
Running instructions for the scraper: 
	Is able to run with no additional issues if providided libraries are installed
	Note:If there it an output folder already in the directory this program is in, it will fill that folder with output files.
	Note:If there is not an output file already present, the scraper will create one in order to not crowd the directory with output files
			
	



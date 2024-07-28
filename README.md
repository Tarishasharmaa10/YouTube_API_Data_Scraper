# YouTube_API_Data_Scraper

In this project, we demonstrate the creation of a Python project focused on scraping YouTube data using the YouTube Data API. We utilize the API to gather data and subsequently load it into a Pandas DataFrame in Python for Analysis. At the end, we use the Seaborn library to create visualizations based on the extracted data.


<h3>Step 1</h3>

- First, we create a YouTube API Key which will be our credential to access YouTube data.
- Once the API Key is generated, we will see how to use this API key to access different YouTube data.
- We will look at the different sections in the documentation to access different data we need to build this project.
- We will also look at the sample Python code given by Google to call different resources and methods to fetch YouTube data.
 
![image](https://github.com/user-attachments/assets/7f9331f9-7fe9-4fe0-abee-6153b8e4afa9)

<h3>Step 2</h3>

- Then, we will get into writing the Python code to build this project. 
- Here I have used Jupyter Notebook to write my Python code. 1st we will install all the required Python packages.
- To access YouTube API data in Python, we'll need to install the "google-api-python-client" package. You can do this by running the command: 'pip install google-api-python-client'.

![image](https://github.com/user-attachments/assets/7b1d1391-2f9b-4bd2-9932-23152e7a0040)

 <h3>Step 3</h3>

- 1st we extract channel details from YouTube. I.e. we extract details such as YouTube channel name, total no of subscribers, total views, and total number of videos posted by each channel.
- We gather these details for a few Data Analyst/Data Scientist kind of channels and then compare these channel data with each other.
- We shall see who has the highest number of subscribers and who gets the most views and the amount of videos posted by these channels.
- We will be loading all of this data into a Pandas data frame and then analyzing it. We will also generate some basic visualization using this data so we can easily compare these multiple channels.

![image](https://github.com/user-attachments/assets/741c3fbd-2b95-460d-8030-934c9b8e56d9)

<h3>Step 4</h3>

- Following Step 3, we'll develop a process to retrieve video details from specific channels. Initially, we'll focus on extracting data from the Codebasics channel, followed by the Krish Naik channel.
- We will extract information such as the video title, total views, total number of likes, and favorites for each video posted by a specific channel.
- We will then analyze this data by loading it into a pandas data frame. At the end, we will create some visualizations using the Seaborn Python library.

![image](https://github.com/user-attachments/assets/daec5f54-395d-4632-ab92-3265d9e247b6)

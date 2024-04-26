 **Uniting Web Scraping, Data Analysis, ML Modeling, and Streamlit Visualization**

The project endeavors to integrate three key processes essential for data scientists. Firstly, we focus on data acquisition, achieved through web scraping of Transfermarkt and FIFA Stats websites. Secondly, we delve into data manipulation and preprocessing, laying the foundation for constructing a predictive model using Machine Learning techniques. Lastly, we embark on deploying our model. To accomplish this, we employ the Streamlit framework to develop an interface. This interface allows users to interactively adjust features and predict player fees, thereby providing an intuitive and customizable experience.

## Project Structure

The project is organized into the following directories:

   1. **step1**: Data scraping using BeautifulSoup and requests.
     - `data_preprocessing.ipynb`: Jupyter Notebook for data preprocessing.
     - `scrap_fifa_stats.ipynb`: Jupyter Notebook for scraping FIFA stats. https://www.fifaratings.com/
     - `scrap_transfer_market.ipynb`: Jupyter Notebook for scraping transfer market data. https://www.transfermarkt.com/statistik/neuestetransfers
      - `data`:  comprises four CSV files, each containing specific datasets. Firstly, there's "transfert_market.csv," housing data obtained from the Transfermarkt website. Secondly, "stats.csv" holds data sourced from the FIFA website. Thirdly, "names.csv" contains player names, serving as a crucial column facilitating the merging of the two datasets. Lastly, "model_training_data.csv" encompasses data subjected to cleaning, preprocessing, and feature engineering, ready for model training.
   2. **step2**: Building the model using different approaches.
     - `Final_Model.ipynb`: Jupyter Notebook for the model.
   3. **step3**: Building an interface using Streamlit.
     - `dataPreprocessingClass.py`: Python file for data preprocessing class.
     - `Video.mp4`: The video used in the inetrface.
     - `webSite_interface.py`: Python file for website interface.


## Project Demonstration and Explanation

Please refer to the following Google Drive link:
[Demo](https://drive.google.com/drive/folders/1GaEaL5FcIDnKLFAjXfP5KcYzHhOQi2np?usp=sharing)


## Ensure you have:

   1.Installed the required dependencies.

   
   2.Created a virtual environment.


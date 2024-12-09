# Advanced_Stock_Prediction_Using_FinBERT_And_Semantic-Search

## **Objective**
This project aims to achieve the following objectives:
1.	Analyze the Impact of Financial News on Stock Prices: Investigate how financial news sentiment influences stock price movements, addressing the gaps left by traditional time series models.
2.	Leverage Advanced Deep Learning Models: Explore the capabilities of Fin-BERT in analyzing financial news, highlighting their strengths in capturing sequential patterns and extracting meaningful insights from textual data.
3.	Incorporate Semantic Search for Enhanced Insights: Utilize vector-based semantic search techniques, such as IndexFlatL2, to retrieve relevant financial news articles efficiently. This enhances the analysis by focusing on contextually relevant information for specific cryptocurrencies.

## **Dataset**
The "Dataset" folder includes a Google Drive link to the dataset used in this project. The file "analyst_ratings_processed.csv" contains stock news headlines from 2009 to 2020 for over 6,000 stocks. Further details about this file can be found on Kaggle.

- https://www.kaggle.com/datasets/miguelaenlle/massive-stock-news-analysis-db-for-nlpbacktests

The "stock_data" folder contains historical stock prices for over 6,000 companies, sourced using the Polygon API.
For more information, refer to the "Data-Preprocessing" Jupyter notebook, which outlines the data preparation steps for the "analyst_ratings_processed.csv" file and includes a demonstration of using the Polygon API to fetch historical stock data.
The "Final_data" file, generated after running the Data-Preprocessing notebook, is used to train the model.

## **Softwares & Libraries**
<img src="https://github.com/KolanHarsha/DDos-detection-Using-Machine-Learning/assets/110462466/ec05c02a-389a-4363-8b8c-9b1ba8ca28b0" alt="python" width="150" height="100">
<img src="https://github.com/user-attachments/assets/6dcda243-fcec-45d4-9d77-8d1107e96275" alt="python" width="150" height="100">
<img src="https://github.com/user-attachments/assets/0d094a07-6ebd-4b8e-9cb2-f0d44e69b98d" alt="python" width="150" height="100">
<img src="https://github.com/user-attachments/assets/9dc4de8c-ff82-4d41-ba1a-52fc2cd8f410" alt="python" width="150" height="100">
<img src="https://github.com/user-attachments/assets/9dc00b20-f474-48cd-ac7e-337fa39ce1db" alt="python" width="150" height="100">


## **Model-Architecture**

![image](https://github.com/user-attachments/assets/701c0645-f343-44db-9a8a-e2384fd2c5de)

## **Model-Training**

The Mean Squared Error (MSE) is employed as the loss function, while the Adam optimizer is used for optimization. The model is trained for 50 epochs, and the training performance metrics are displayed in below graphs.

![image](https://github.com/user-attachments/assets/9911145f-90d0-4ec9-a8b1-e87f9cd9678d)

![image](https://github.com/user-attachments/assets/2348eda6-145c-46e1-acc1-1ec18703dbd6)

    Best epoch: 49 with Test Loss: 0.10980

The model weights for the best epoch are available in "model_epoch_49.pth" file.

## **Model-Evaluation**

#### **MORGAN-STANLEY STOCK**

![image](https://github.com/user-attachments/assets/2679f584-627d-4ea1-a2f0-ca323f08947a)

#### **CITI-GROUP Inc STOCK**

![image](https://github.com/user-attachments/assets/e902def6-a1c0-40a6-b386-9c8ddeb896cf)

## **Conclusion**

The results of this project on predicting stock prices using financial news have been quite impressive. The model demonstrated a significant ability to capture the influence of news sentiment on stock price movements, highlighting the relevance of financial news in forecasting market trends. However, it is important to recognize that stock prices are influenced by a multitude of factors beyond news. Market dynamics are also shaped by economic indicators, company performance, investor sentiment, geopolitical events, and various other variables. While financial news provides valuable insights, a comprehensive stock prediction model should consider these additional factors to enhance accuracy and robustness. Overall, this project underscores the potential of integrating news-based insights with other data sources for a more holistic approach to stock price forecasting.

## **Contributors**
- Sai Harsha Vardhan Reddy, Kolan- skolan@horizon.csueastbay.edu, harsha62334@gmail.com

Thanks for reading!





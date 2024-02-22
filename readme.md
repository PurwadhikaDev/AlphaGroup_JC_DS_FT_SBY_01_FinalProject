# **Hotel Booking Demands**

## **About**
This project is a part of JCDS Program : Purwadhika. This Repository contains file Python Notebook and file .sav (for model machine learning) for my Analyze about this Case Study. This project contains the results of my prediction using machine learning for Hotel Booking Demands. The data contains information from this article about datasets comprehend bookings due to arrive between the 1st of July of 2015 and the 31st of August 2017, including bookings that effectively arrived and bookings that were canceled.

## **Business Task**
The hotel sector is undergoing rapid expansion, driven by the growing integration of technology and escalating consumer expectations. This heightened engagement with these elements prompts hotel businesses to embrace inventive strategies, particularly in the realm of room reservation management. Given the continual rise in demand and the intricate interplay of factors shaping booking decisions, a refined method is essential for accurately forecasting reservation rates. The primary aim is to enhance hotel capacity utilization while mitigating booking cancellation rates, thereby ensuring maximum operational efficiency and long-term viability.

## **Business Problem**
In hospitality sector, efficient management of hotel bookings is critical to ensuring customer satisfaction and maximizing revenue. However, amidst the dynamics of hospitality industry, hotels face challenges in predecting and managing booking demand accurately. Moreover, currently there are cancellations of hotel bookings and this can affect customer satisfaction as well as affect hotel revenue. Therefore, the right analyzer and appropriate insights regarding predictions of customer booking cancellations are considered very important for today's hotel business models in order to optimize operations in this business. This will certainly have a serious impact considering that the hotel will suffer losses with empty rooms without visitors and other visitors who want to book will be disappointed because the hotel capacity is full and of course this will affect customer satisfaction.

## **Result and Conclusion**
1. Best Model: Random Forest Classifier with Random Over Sampler and Min Max Scaller.
2. Metric Evaluation: Recall score 1. With minimalizing False Negative.
3. Test Score (Recall) : 86% | (Accuracy) : 71%
4. Feature Importances : lead_time, market_segment, required_car_parking_spaces

## **Data Source**
The data used comes from the PMS (Property Management System) Hospitality Database in Portugal which was collected and used in the article written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019. (https://www.sciencedirect.com/science/article/pii/S2352340918315191).
Then the dataset was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020, and then distributed for educational purposes and made publicly available on the Kaggle.com platform. (https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).
For the purposes of trust and authenticity of data, this data is protected under the *Attribution 4.0 International (CC BY 4.0)* license and the conditions contained in the following link: https://creativecommons.org/licenses/by/4.0/.
The dataset is downloaded in .csv format.

Status Project: **Completed**
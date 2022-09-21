# Image Classification
As an introduction, here's the general overview of the project that I did over the course of my 3 months internship at SG-EDTS.

One problem encountered over the course of the project was that there was 2 types of KTP (Kartu Tanda Penduduk or Residence Identification Card in English),  either it was Fotocopy or Real. As a result, this creates an issue in the identification on whether or not a buyer from an application of the business client is real due to the algorithm unable to determine the difference between a real and fotocopy image, seen in the image below.

![Brief Overview](https://user-images.githubusercontent.com/64077541/191445670-a9bef093-cee4-40c8-b080-0cf9300017d2.jpg)

As a result, a machine learning algorithm was needed to be created as part of the data pipeline for the application so that the in-house algorithm of the client's application will be able to learn the difference of a fotocopy and real KTP. Hence, the project of Real and Fotocopy KTP Image Classification was created, seen in the below diagram. 

![Project Workflow](https://user-images.githubusercontent.com/64077541/191443933-ebae3e49-b7e1-40c6-8942-d74762e057d0.jpg)

Several machine learning algorithms and a deep learning algorithm will be tested for this project, such as Decision Tree, Logistic Regression, and Artificial Neural Network in order to test which algorithm suits best for the dataset according to its size and nature. 

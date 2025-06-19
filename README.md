# AI-BASED-RECOMMENDATION-SYSTEM

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : SAI REETHIKA

*INTERN ID* : CT04DF163

*DOMAIN* : JAVA PROGRAMMING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

##DESCRIPTION

An **AI-based recommendation system** is a software application designed to suggest relevant items to users by analyzing their preferences and behaviors. In this project, I built a basic recommendation system in **Java** using **Visual Studio Code (VS Code)** as the development environment. The goal was to implement a content-based filtering approach, which recommends items to a user based on the features of products they liked in the past. To achieve this, I created a CSV file (`products.csv`) containing a small dataset of products with attributes like name, category, price, and brand. Each product’s attributes were converted into a simple numeric feature vector (e.g., hash codes for text fields and normalized values for price). Then, using Java, I implemented a cosine similarity function to compare the feature vector of a selected product with all others in the dataset. The products with the highest similarity scores were returned as recommendations.

The project structure included a `data` folder with the CSV file and a `src` folder with the main Java class (`Recommender.java`). The Java code read the product data, computed feature vectors, and performed similarity-based matching. This was all done without using any external machine learning libraries to keep the logic transparent and understandable. VS Code was used for writing and running the code with the help of a simple Java extension pack. This project demonstrates how basic AI techniques like content-based filtering and similarity measurement can be implemented in Java to build an effective recommendation system from scratch.

#output

![Image](https://github.com/user-attachments/assets/ca05e9d8-4d3d-42e1-9fbf-e02d4ee1cc5e)

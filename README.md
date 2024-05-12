# i222014_i221913_i221996_BDA_FinalProject
# RhythmRabbit- A Streaming Platform Similar to Spotify With a Built In Music Recommendation System

## Introduction
RhythmRabbit is a web-based music streaming platform that also includes a mrecommendation system designed to provide personalized song recommendations to users. This platform allows users to explore various tracks, listen to them, and receive suggestions for similar songs based on their listening preferences.

## Features
- **User Authentication**: Secure login and sign-up options to manage user accounts.
- **Music Streaming**: Users can stream songs directly from their browser.
- **Personalized Recommendations**: The system suggests songs that match the user's taste.
- **Interactive Interface**: A user-friendly web interface with a minimalist design.

## Technologies Used
- **Frontend**: HTML5, CSS3 (Bootstrap 4.5.2), Jinja2 templates.
- **Backend**: Python with Flask framework.
- **Database**: MongoDB.
- **Data Processing**: Apache Kafka, Apache Spark.


## Installation and Setup

### Prerequisites
- Python 3.8 or above
- Flask 
- MongoDB
- Apache Kafka
- Apache Spark
- HTML,CSS,JS

### Required Technologies
#### Apache Spark
Apache Spark was instrumental in building the core recommendation algorithm. Spark's advanced analytics capabilities and in-memory computing power allowed for fast processing of large datasets, which is essential for delivering real-time music recommendations.

#### Apache Kafka
Apache Kafka played a crucial role in handling real-time data streaming. This data was continuously streamed into the system, allowing for real-time analytics and immediate updates to user profiles and recommendation models. 

#### MongoDB
MongoDB was utilized as the primary database to store and manage a wide array of data, including user profiles, song metadata, and user interactions. MongoDB's powerful querying capabilities enabled quick retrieval of song details and user data, facilitating efficient personalization of music recommendations. 

#### Flask
Flask was used to develop and manage the server-side logic and APIs. It provided the necessary tools to set up RESTful services, which facilitated the communication between the frontend user interfaces and the backend systems, including MongoDB and the recommendation engine built with Apache Spark and Hadoop. 

### Overview of Code
#### Extract, Transform, Load (ETL) Pipeline
At the core of the system is an ETL pipeline that facilitates the extraction of raw data from various sources, including user interactions and song metadata. This data undergoes transformation to ensure it is clean, consistent, and structured appropriately for analysis. This ETL process is crucial for maintaining the integrity and usability of the data, which directly impacts the effectiveness of the recommendation algorithms.

#### Backend Development with Flask
The backend of RhythmRabbit is powered by Flask, a Python web framework that offers flexibility and simplicity for web service implementation. Flask handles all server-side operations from managing user sessions and handling HTTP requests to interacting with MongoDB for data retrieval and storage. It also integrates seamlessly with Kafka to process streaming data and Spark to run the recommendation algorithms.

#### Apache Kafka for Real-Time Data Handling
Apache Kafka is utilized to manage real-time data streams. It captures live user activity data—such as tracks played, which is crucial for updating the recommendation models in real-time. Kafka's robust processing capabilities ensure that data flows smoothly and reliably between the user interface and the backend services.

#### Recommendation Engine with Apache Spark
Apache Spark is employed to build and run the sophisticated recommendation engine. Using Spark’s MLlib, the system analyzes user behavior and song features to generate personalized song recommendations. The engine operates on data processed by the ETL pipeline, leveraging Spark's powerful in-memory computing to deliver fast and accurate recommendations.

#### Frontend Implementation
The frontend is developed using HTML, CSS, and Bootstrap, providing a clean and responsive user interface. It allows users to interact with RhythmRabbit seamlessly, from signing up and logging in to browsing songs and receiving personalized recommendations. 

### Conclusion

In conclusion, the RhythmRabbit music recommendation system exemplifies a successful integration of various advanced technologies to create a dynamic and user-centric platform. Through the meticulous orchestration of an ETL pipeline, real-time data handling with Apache Kafka, robust backend services using Flask, and a sophisticated recommendation engine powered by Apache Spark, RhythmRabbit offers a seamless and engaging music listening experience.

### Team Members
- Taha Tariq (22I-2014)
- Haider Akbar (22I-1913)
- Hasnain Raza (22I-2014)

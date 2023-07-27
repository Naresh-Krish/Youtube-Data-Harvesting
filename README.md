# Introduction:
The project aims to develop a Streamlit application that facilitates users in accessing and analyzing data from multiple YouTube channels. Leveraging the Google API, the application allows users to input a YouTube channel ID and retrieve essential data such as channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, and comments for each video. Additionally, the application offers the functionality to store the acquired data in a MongoDB database, serving as a data lake. Users can collect data for up to 10 different YouTube channels and conveniently store them in the data lake with a single click. Furthermore, the application provides an option to choose a specific channel name and migrate its corresponding data from the data lake to a SQL database in the form of tables. Users can then effectively search and retrieve data from the SQL database, employing various search options, including the capability to perform table joins to access comprehensive channel details.

# Tools:
Streamlit: A Python library for creating interactive web applications with minimal effort, enabling the display of data and incorporating user inputs effectively.
Google API: Specifically, the YouTube Data API, which grants access to YouTube's vast repository of data, enabling retrieval of channel and video information.
MongoDB: An open-source NoSQL database that acts as a data lake, allowing the storage of unstructured data with ease.
SQL Database: Utilized for structured data storage and management, providing robust query capabilities.
Python: The primary programming language for the development of the application, as it offers a wealth of libraries and ease of integration with the selected tools.

# Procedure:
Users will be presented with an intuitive Streamlit interface to input a YouTube channel ID and access relevant data. Upon providing the channel ID, the application will use the Google API to retrieve information like the channel name, subscriber count, total video count, playlist ID, video ID, likes, dislikes, and comments for each video.

The fetched data can be optionally stored in MongoDB, acting as a data lake. This storage option allows users to accumulate data from multiple YouTube channels for further analysis.

Users can click a button within the application to collect data for up to 10 different YouTube channels and save them in the MongoDB data lake.

An additional feature will enable users to select a specific channel name and migrate its data from the MongoDB data lake to a SQL database. This process will structure the data into tables, making it easier for users to perform SQL queries and analysis.

To facilitate advanced data retrieval, the application will offer search options, allowing users to retrieve data from the SQL database using various filters and join operations to obtain comprehensive channel details.

The Streamlit application will be deployed to a web server, making it accessible to users via a web browser. Users can interact with the application through the provided interface, fetching, analyzing, and storing YouTube channel data effortlessly.

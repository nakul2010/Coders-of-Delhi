This project is a small simulation of a social media platform for developers called CodeBook. The main idea was to work with raw JSON data and build core social network features using only basic Python. No external libraries were used, so everything runs on built in data structures like lists, dictionaries, and sets.

The project is divided into four main parts. First, I loaded and explored the dataset to understand how users, friends, and pages are connected. Next, I cleaned the data by removing missing names, duplicate entries, inactive users, and repeated page IDs. Once the dataset was structured properly, I implemented two recommendation features.

The first feature is "People You May Know", which suggests new connections based on mutual friends. The second feature is "Pages You Might Like", which recommends pages using simple collaborative filtering logic. If two users like similar pages, they may be interested in other pages liked by each other.

This project helped me strengthen my understanding of data structures, basic graph logic, and recommendation systems. It also improved my problem solving skills by forcing me to implement everything from scratch without relying on libraries like pandas or NumPy.

Tech Used

Python 3

JSON

Built in data structures only

How to Run

Save the dataset as a JSON file

Run the Python script or notebook

Execute the cleaning and recommendation functions

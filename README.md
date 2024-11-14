# heart-disease-prediction
Description

A Regression type prediction model using Random Forest Regression algorithm. It uses accuracy score and classification report as the metric for prediction.
Git and other commands used in the command prompt:

    mkdir <file_name> to create the folder
    cd <file name> to go inside the folder
    git init, initializing folder as git repository
    git add . to add all the files into git track
    git commit -m "<message>", it commits whatever is there in the track
    git remote add origin <GitHub repository link>, builds connection between git and github
    git push --set-upstream origin master, sends all the files from git to github.

Docker Commands:

    docker build -t ,folder_name> .
    docker run <folder_name>

Steps:

    Create the required files such as the dataset csv file(heart.csv), training model python file, requirements txt file, Dockerfile.
    Create a new item under Freestyle Project item type
    Select Git in Source Code Management and paste your github repository url
    Add Execute Windows Batch Command step in Build Steps
    Save configurations
    Build now and visualize console output
    Now open command prompt with the path of the folder containing the required files
    Execute the Docker commands mentioned above
    Visualize the output in the command prompt and in the Docker Desktop app

Output:![test-1 proof of jenkins](https://github.com/user-attachments/assets/f42ea8f4-cc8a-49a0-97fb-b2b1f6faf088)
![my3 heart disease prediction docker proof](https://github.com/user-attachments/assets/d7c513ec-dcaf-4c5d-aee3-46131c277e9b)


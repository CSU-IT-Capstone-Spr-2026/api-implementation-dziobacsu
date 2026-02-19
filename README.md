[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zN2AskmG)
# XKCD Comic Viewer

A webapp that displays the latest issued XKCD comic. The user has the ability to: navigate between comics, randomly fetch one, search them by issue, and view recent uploads.

## Features Implemented

Check off the features you implemented (must have at least 4 and 2 are implemeted for you already):

- [X] Feature #1: Display the Latest Comic
- [X] Feature #2: Display a Specific Comic by Number
- [X] Feature #3: Random Comic Button
- [X] Feature #4: Navigation (Previous/Next)
- [X] Feature #5: Search by Comic Number Form
- [X] Feature #6: Display Multiple Recent Comics

## Technologies Used

- Python 3.8+
- Flask 3.0.0
- Requests 2.31.0
- XKCD API

## Installation and Setup

### Prerequisites
- Python 3.8 or higher installed
- pip (Python package manager)

### Steps to Run

1. Clone or download this repository

2. Navigate to the project directory in your terminal:
   ```
   cd projectName
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

5. Open your web browser and go to:
   ```
   http://localhost:5000
   ```

## Usage

User can click the Next and Previous buttons to navigate between comic issues. They can also click the "Random" button to fetch a random comic. There is a box to search for a comic by its designated issue number. There is also a button to display recently uploaded comics they may click.

## Screenshots

<img width="883" height="1173" alt="comic viewer" src="https://github.com/user-attachments/assets/e99702f1-e5a1-4e5a-aaf8-94c3278bd085" />


## API Endpoints Used

- `GET /info.0.json` - Fetches the latest comic
- `GET /{comic_number}/info.0.json` - Fetches a specific comic by number

## Challenges and Solutions

[Write 2-3 paragraphs about:]
- What challenges did you face while working on this assignment?
- How did you solve them?
- What did you learn about APIs?

I do not like coding, and I am not familair with HTML or APIs at all. At least with Python, I understand it for the most part. I am not familiar with JSON, APIs, nor HTML. So, I would say the challenge by and large was figuring out how to actually use these tools to do what the assignment asked I do. Another challenge I had was not being super familiar still with github or github desktop. The navigation came back quick though.

To solve my challenges I had to do extensive research and scour forums for coding errors I was facing, whether they were purely syntax or when I would try to run the code. I also read documentation on Flask, HTML, etc and cross referenced what I was reading with posts I would coem across that were trying to solve the same issues I was.

APIs are great for implementing features to an app. IT eliminates the need to code everything from the ground up, and you are able to effectively use APIs so long as you understand their actual implementation and use cases that pertain to what you are trying to do. 

## Future Improvements

I'd love a dark mode for the webpage. I feel like that could be cool to implement since the comics seem to all be black and white. You could invert them to have a dark mode for the app.

## Author

Daniel Dzioba

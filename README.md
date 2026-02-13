[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zN2AskmG)
# XKCD Comic Viewer

[Add your 2-3 sentence description of what your application does here]

## Features Implemented

Check off the features you implemented (must have at least 4 and 2 are implemeted for you already):

- [X] Feature #1: Display the Latest Comic
- [X] Feature #2: Display a Specific Comic by Number
- [ ] Feature #3: Random Comic Button
- [ ] Feature #4: Navigation (Previous/Next)
- [ ] Feature #5: Search by Comic Number Form
- [ ] Feature #6: Display Multiple Recent Comics

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

[Explain how to use your application - what can users do? What buttons should they click?]

## Screenshots

[Add screenshots of your application here - you can drag and drop images into GitHub or use Markdown image syntax]

Example:
```
![Latest Comic View](screenshots/latest-comic.png)
![Search Feature](screenshots/search.png)
```

## API Endpoints Used

- `GET /info.0.json` - Fetches the latest comic
- `GET /{comic_number}/info.0.json` - Fetches a specific comic by number

## Challenges and Solutions

[Write 2-3 paragraphs about:]
- What challenges did you face while working on this assignment?
- How did you solve them?
- What did you learn about APIs?

## Future Improvements

[Optional: What would you add if you had more time?]

## Author

[Your name]
# DCFI Trivia App
DevCareer Frontend Intermediate - Assignment 01

## Assignment Description
Build a simple trivia application using the Open Trivia DB api - https://opentdb.com/api_config.php  

#### Acceptance criteria :
- User should Enter their name as first action
- User must be able to chose which field of questions they want to answer
- User must be able to select difficulty
- Each Trivia session must not have more than 10 questions
- At the end of the trivia session users total score must be shown and an option to return back to home.  

LANGUAGE TO USE  - HTML, CSS and Javascript ONLY

## Assignment Solution
A simple trivia application has been built (directory structure below):
```
├── assets
│   ├── css
│   │   └── style.css
│   ├── fonts
│   │   └── *lineawesome icon files*
│   ├── images
│   │   ├── DevCareer-Logo.png
│   │   ├── icons8-quiz.gif
│   │   └── open-trivia-db_logo.png
└── index.html
```

Challenges faced:
- Merely combining ``correct_answer`` and ``incorrect_answers`` values to make all options would mean that the correct answer will always be the first or last option. I applied a shuffle function to fix this.
- String comparison between the user selected option and the correct answer requires an extra step to decode special HTML characters/entities.

#### External Resources Used
* Google Fonts: Nunito
* Yeti Themes: CSS Library
* Chart.JS: Chart Library
* Tippy JS: Tooltip Library
* LineAwesome: Icon Library

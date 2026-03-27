# oop-_lab_project-1-2
# Online Quiz Game (C++)

A simple console-based quiz project built for OOP practice.

## What it does
- Lets users register/login and take a quiz.
- Lets an admin add questions, options, and answers.
- Stores data in text files (`logIN.txt`, `Question.txt`, `Options.txt`, `Answer.txt`).

## Main files
- `main.cpp` — menu and app flow
- `login.*` — user registration/login/score
- `Admin.*` — admin panel and question setup
- `Questions.*` — question/option/answer handling

## Run
### Code::Blocks
Open `testfile.cbp` and run.

### g++
```bash
g++ -std=c++17 main.cpp login.cpp Questions.cpp Admin.cpp SignUP.cpp SingIN.cpp -o quiz_game
./quiz_game
```

> Note: This is a student/lab project and stores credentials in plain text.

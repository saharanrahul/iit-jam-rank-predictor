# IIT JAM Ranks Predictior

What is IIT JAM ?
IIT JAM is a competitive exam conducted by the Indian Institutes of Technology (IITs) for admission into Master’s (M.Sc.), Joint M.Sc.–PhD, and other postgraduate science programs.

##  What’s behind the reason for creating this project?

Many IIT JAM aspirants face confusion after the exam — **“Marks aa gaye, but rank kya aayegi?”**  
To solve this, I compared the **IIT JAM 2025 paper difficulty** with previous year trends. The 2025 paper felt close to the **2023 pattern**, so I estimated rank ranges around similar performance levels and designed a simple prediction logic.

Initially, I created this project as a **basic HTML + CSS tool** and published it on my **Blogger website** to help students quickly get an approximate rank idea.  
Later, as my programming skills improved, I upgraded it into a **Python + Flask based web application** and published the complete project on **GitHub** for better usability, maintainability, and future improvements.

##  Features
- Predicts **Rank Range** from expected JAM score
 - Supports **Category input** (General / OBC / SC-ST)
- Provides **Suggested IITs list** based on predicted rank



## Tech Stack
- **Backend:** Python, Flask
- **Frontend:** HTML, CSS

## 📂 Project Structure

```txt
jam_rank_predictor/
│── app.py
│── data.py
│── requirements.txt
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```
## Install Requirements
```
pip install -r requirements.txt
```

## How it Works (Logic Overview)

1. User enters expected JAM score

2.  User selects category

3.  App adjusts score using category factor

4.  App predicts rank range

5.  Shows recommended IITs list based on predicted rank

# ET GROUP 3 TERM PROJECT
This is a chatbot  designed to provide information from the JSON files uploaded by the instructor to the students in a conversational format.

# How to run it?

1. Clone this repository

```
cd Mental-health-Chatbot/
```

2. Create and activate virtual environment 

```
python -m venv venv
```
on Windows system
```
.\venv\Scripts\activate.bat
```
3. Install requirements

```
pip install  -r requirements.txt
```


4. Run the 
```
flask --app app --debug run

```

The chatbot should be hosted on http://127.0.0.1:8000

# Instructions for Teacher

The teacher can upload their coursework in a JSON file (like ``` sample_intent.json```.
The Chatbot will then query that particular json file and give conversational outputs to the students.

![Screenshot 2023-12-03 191437](https://github.com/mentaltraffic/ET-AI-chatbot/assets/58178738/28d17d3b-4aeb-4770-8170-a6c27dfb46b8)


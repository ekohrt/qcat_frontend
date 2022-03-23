# Q-Cat: Question Type Classifier
A machine learning question-type classifier. Uses Distilbert from Hugging Face to classify questions into 27 categories. Dataset includes about 900 labeled example qeustions. Frontend web app is made with Flask.
  
[Link to Hugging Face model](https://huggingface.co/ekohrt/qcat)  
  
![Q-Cat demo page](frontend_preview_image.png?raw=true "Title")
  
  
Instructions for running locally:
1. open terminal
2. navigate (cd) into the main directory containing Q-Cat
3. run these lines in the terminal:
  
set FLASK_APP=app.py  
set FLASK_ENV=development  
flask run  
  
4. you should see a url near the top of the output: copy and paste this into your browser. [Source](https://cs396-web-dev.github.io/winter2022/assignments/lab02#:~:text=try%20running%20your%20flask%20app%20from%20your%20command%20line)

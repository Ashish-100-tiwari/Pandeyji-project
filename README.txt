Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code

Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

run :python -m uvicorn main:app --reload
before executing enter the db_password and root
To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.

<div style="text-align:center"> 
  <br><br>
  <video align="center">
    <source src="https://github.com/Ashish-100-tiwari/Pandeyji-project/blob/a5e2a91ee2c77f0898d8e55b43a739c06f653d4a/home.html%23location%20and%204%20more%20pages%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge%202023-06-26%2021-55-29.mp4" type="video/mp4">
    Demo video 
  </video>
</div>

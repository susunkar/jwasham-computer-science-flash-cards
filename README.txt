https://github.com/jwasham/computer-science-flash-cards

1. Download core 
2. install python 2.7.17
3. install pycurl-7.43.0.1.win-amd64-py2.7.msi 
4. run python flash_cards.py
5. browser http://localhost:5000/general


#############################################################
Install dependencies:
Install Python
Add python as environment variable windows
To install pip, securely download get-pip.py
Run python get-pip.pyin terminal
Add pip to your PATH system variable windows
Run pip install -r requirements.txt in terminal after going to correct folder
Open flash_cards.py and uncomment the line 52-55 beginning from @app.route('/initdb')
Type python flash_cards.py - if you get error for flask then use python -m pip install Flask first then run flash_card.py file
Open localhost:5000/initdb
Login using id:USERNAME='admin', PASSWORD='default.
Comment the line 52-55 in flash_cards.py
NOTE: If you wish to use John's flash cards then also do following steps:

Copy db files such as cards-jwasham-extreme OR cards-jwasham and paste them in db folder
Edit file flash_cards.py line 11 and replace cards with any of the other database files
Repeat the above steps from step 3 Every time you wish to run your db just open folder in terminal and run python flash_cards.py
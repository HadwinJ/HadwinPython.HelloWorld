
# Create venv
mkdir globomantics
cd globomantics/
python3 -m venv venv
source ./venv/bin/activate
pip install Flask
pip freeze > requirements.txt // pip install -r requirements.txt

# Run the Flask
export FLASK_ENV=development
export FLASK_APP=app.py
flask run

# pdb command
request
request.form
request.args
c

# SQLite
python ./db/init.py
python ./db/show_tables.py

# Install Flash WTF
pip install flask_wtf
pip freeze > requirements.txt
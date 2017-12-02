## StudyTracker
# create requirement file
pip freeze >requirements.txt
# install requirement file
pip install -r requirements.txt
# run server
python manage.py runserver --host 0.0.0.0

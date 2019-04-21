# Django React Project Template
Template project for a web application which uses Django as a backend and React as a frontend. React is integrated in its own "frontend" Django app.

1. Navigate to the root of the project and execute the following command to install the Django related dependencies:
```
pip install -r requirements.txt
```
2. Again in the root of the project, execute the following command to install the React related dependencies:
```
npm install
```
3. Execute the following command to compile the React application for development (requires npm to be installed):
```
npm run dev
```
4. Execute the following command to run the Django development server locally:
```
python manage.py runserver
```
5. You should see "React and Django App" displayed once you visit:
```
localhost:8000
```

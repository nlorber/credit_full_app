# credit_full_app

This is the full-dataset version of the LGBM-based scoring app. Unfortunately, due to file-size issues, it is not deployable onto Heroku.
To run locally, type:

uvicorn app:app

in the terminal. Once the API is successfully deployed, run the command:

streamlit run dashboard.py

for the dashboard to start.
The online version of the app, based on a 1000-individual sample can be found at: https://credit-web.herokuapp.com/
and the corresponding code at https://github.com/nlorber/credit_light
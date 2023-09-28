# Instructions

1. install requirements
   1. `pip install -r requirements.txt`
2. create .env file
   1. `cp .env.example .env`
   2. fill in the .env file with values from [https://getmontecarlo.com/settings/api](https://getmontecarlo.com/settings/api)
3. make any adjustments to the regex in `dbt.py` to match your needs
4. run the script on Monday at 12:00 AM UTC
   1. `python3 main.py`

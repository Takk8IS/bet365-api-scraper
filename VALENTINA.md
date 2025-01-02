git clone https://github.com/Carlinhos10-pk/bet365-api-scraper
cd bet365-inplay-api

python -m venv venv
source venv/bin/activate   # On Windows, use `venv/Scripts/activate`

pip install -r requirements.txt

python api.py
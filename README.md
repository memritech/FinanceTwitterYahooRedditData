# Read Twitter, Reddit

Code borrowed from 
https://medium.com/swlh/how-to-create-a-dashboard-to-dominate-the-stock-market-using-python-and-dash-c35a12108c93?sk=718924d0c0e01a7b426a54dabc4f1df0


### Python
```
python -m venv .env
.env/bin/python -m pip install -r requirements.txt
source .env/bin/activate
python index.py
```
### Git push
```
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/memritech/FinanceTwitterYahooRedditData.git
git push -u origin main
```

### Config.py
```
twitter_consumer_api_key = ''
twitter_consumer_api_secret_key = ''
twitter_access_token = '-'
twitter_access_token_secret = ''
r_cid = ''
r_csec = ''
#user_agent
r_uag = 'Chrome'
```
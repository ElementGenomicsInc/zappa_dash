A [Dash example](https://plot.ly/dash/getting-started) deployed to AWS Lambda and API Gateway using [Zappa](https://github.com/Miserlou/Zappa)

```bash
python3 -v -m venv .venvs/zappa
source .venvs/zappa/bin/activate

git clone git@github.com:ElementGenomicsInc/zappa_dash.git
cd zappa_dash/
pip install -v --no-cache-dir -r requirements.txt
zappa deploy
```


pip install --upgrade coingecko

import coingecko

client = coingecko.CoinGeckoDemoClient(api_key=<CG-W19jzQBo4PEWNTrcdFWCTneh>)

response = client.ping.get()

pip install --upgrade coingecko

import coingecko

# Demo API key
client = coingecko.CoinGeckoDemoClient(api_key=<CG-W19jzQBo4PEWNTrcdFWCTneh>)

# Test your API key with ping
response = client.ping.get()

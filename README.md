# base4
Fetching Token Balances Across Multiple Wallets  Monitoring multiple wallets is useful for DeFi analytics and airdrop predictions.  Python example
addresses = ["0x123...", "0xabc..."]
for addr in addresses:
    balance = w3.eth.get_balance(addr)
    print(addr, balance)

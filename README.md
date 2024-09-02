# BTC-transactions-Data

This dataset contains detailed information about Bitcoin transactions associated with our specific target addresses in each csv file . The dataset has been created to analyze transaction patterns, amounts, and the flow of funds for certain entities of interest.

this repo consists of data samples for transactions associated with wallets that belong to those organizations:
1) Infowars (Alex Jones), original BTC address: **`bc1q0kpk303cljyn62vgve34hcxlztn7zfmh0jgjtf`**
2) Infowars (Alex Jones), original BTC address: **`bc1qt7fhd9dr3k67hjaycu0e09dkt829scxwvhxh20`**
3) Infowars (Alex Jones), original BTC address: **`bc1q5kx8976cz6k3dhlcyht0znh22gr754uygq8xhl`**

"Script to extract and create your own data: **`data_extraction_script.ipynb`**" 

### Data Features
Entity: The name of the entity associated with the Bitcoin address.

target_wallet_address: The target Bitcoin address for the transaction.

bitcoin_address: The Bitcoin addresses involved in the transaction with our target address (could be the sender or receiver).

transaction_id: Unique identifier for the transaction.

date: Timestamp of when the transaction occurred.

amount_satoshi: The amount transferred in the transaction, in satoshis (1 Bitcoin = 100,000,000 satoshis).

amount_btc: The amount transferred in the transaction, in Bitcoin.

amount_usd: The equivalent value of the Bitcoin amount in USD at the time of the transaction.

type: Indicates whether the transaction was "Incoming" or "Outgoing" relative to the target wallet address.



### License

This dataset is provided for educational and research purposes. Ensure that usage complies with all relevant laws and guidelines, particularly when handling sensitive financial data.


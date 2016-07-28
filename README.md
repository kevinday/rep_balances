# rep_dist
Generates REP balances/ETH addresses from Augur crowdsale for initial distribution.

#Usage
To use, export the augur crowsale stormpath db using stormpath-export.
```
npm install
node index.js ./data
```
Where `./data` is the root dir of the db you exported.

Spits out `report.txt` which is a list of accounts with bad/missing data to take aciton on, and `arrays.py` whcich contains two parallel arrays whcich represetn eth addrress and balances.

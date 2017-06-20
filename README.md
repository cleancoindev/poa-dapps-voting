# Oracles network Voting Dapp

## Initial page (Settings)
Choose your voting key from the list to continue. You can return to this page from any page by clicking **Settings** button.

![](./settings.png)

## Ballots page
You'll see the page with the list of all ballots. Here you can switch to see only your **UNANSWERED** or **EXPIRED** ballots. 
**Search** by ballots' data is available too.

Single ballot page is opened by clicking **VOTE NOW** button.

![](./ballots.png)

## Single ballot page
Here you can vote for or against notary. If total number of votes > 3, notary will be added or deleted from the network depending on votes majority after voting will be finished.

![](./ballot.png)

## New ballot page
Click **NEW BALLOT** button from any page to create a new ballot. 

![](./new_ballot.png)

## Configuration file
It is configured with [Oracles network contract](https://github.com/oraclesorg/oracles-contract)

Path: `./assets/javascripts/config.json`

```
{
  "environment": "live",
  "Ethereum": {
    "live": {
      "account": "Oracles_contract_owner_address",
      "contractAddress": "Oracles_contract_address"
    }
  }
}
```

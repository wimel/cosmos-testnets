# gaia-9003

Let's collect genesis transactions in this folder.

### Step 1

`gaiad init --home {your gaiad home dir} --chain-id gaia-9003 --moniker {your moniker}`

### Step 2

`gaiad gentx --amount 10000STAKE --home {your gaiad home dir} --name {the key to sign the tx}`

The gentx json will be stored at {your gaiad home dir}/config/gentx/.


Submit this file by making a pull request.

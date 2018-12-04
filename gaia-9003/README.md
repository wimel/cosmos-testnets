# gaia-9003

Let's collect genesis transactions in this folder.

### Step 1

`gaiad init --home {your gaiad home dir} --chain-id gaia-9003 --moniker {your moniker}`

### Step 2

`gaiad gentx --home {your gaiad home dir} --name {the key to sign the tx}

The gentx json will be stored at {your gaiad home dir}/config/gentx/.

### Step 3

Update the amount of delegation from 100 to 10000. You should see this in the file.

```
  "delegation": {
    "denom": "STAKE",
    "amount": "100"
  }
```          

Change it to 

```
  "delegation": {
    "denom": "STAKE",
    "amount": "10000"
  }
```  

Save it and submit this file by making a pull request.

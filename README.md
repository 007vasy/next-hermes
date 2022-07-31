# next-hermes
sending on chain messages in bulk to addresses in the logs

## DEV

using venvwrapper

### ENV setup
```bash
mkvirtualenv next-hermes
workon next-hermes
pip install upgrade pip
pip install -r requirements.txt
```

### Using ape
```bash
export WEB3_INFURA_PROJECT_ID=<YOUR_INFURA_PROJECT_ID>
ape console --network ethereum:mainnet:infura
```



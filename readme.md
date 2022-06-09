```
ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts upload \
    -e devnet \
    -k ~/.config/solana/id.json \
    -cp config.json \
    ./assets

ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts verify_upload \
    -e devnet \
    -k ~/.config/solana/id.json 

ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts mint_one_token \
    -e devnet \
    -k ~/.config/solana/id.json 

ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts withdraw_all \
    -e devnet \
    -k ~/.config/solana/id.json

ts-node ~/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts sign_all \
    -e devnet \
    -k ~/.config/solana/id.json

solana-keygen recover 'prompt://?key=0/0' -o <file.json>


```
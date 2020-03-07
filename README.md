# vex.token
After you install binaries and vex.cdt
follow this command
mkdir CONTRACTS_DIR
cd CONTRACTS_DIR
git clone https://github.com/YudaAdiPratama/vex.token/
back dir ../

./cleos wallet unlock --password PWDKASJFJSFLSAFJLASJF.... (change with your password)

set contracts
./cleos --url http://209.97.162.124:8080 set contract ur_account CONTRACTS_DIR/vex.token --abi vex.token.abi -p ur_account@active

create token
./cleos --url http://209.97.162.124:8080 push action ur_account create '[ "issue_account", "50000000000.0000 PAYA"]' -p ur_account@active

Issue Tokens
./cleos --url http://209.97.162.124:808 push action ur_account issue '[ "issue_account", "50000000000.0000 PAYA", "memo" ]' -p ur_account@active

Transfer token
./cleos --url http://209.97.162.124:8080 push action ur_account transfer '[ "sender", "reciv" "10000.0000 PAYA", "memo" ]' -p sender@active# vex.token
After you install binaries and vex.cdt
follow this command
mkdir CONTRACTS_DIR
cd CONTRACTS_DIR
git clone https://github.com/pindapanda/vex.token/
back dir ../

./cleos wallet unlock --password PWDKASJFJSFLSAFJLASJF.... (change with your password)

set contracts
./cleos --url http://209.97.162.124:8080 set contract ur_account CONTRACTS_DIR/vex.token --abi vex.token.abi -p ur_account@active

create token
./cleos --url http://209.97.162.124:8080 push action ur_account create '[ "issue_account", "50000000000.0000 PAYA"]' -p ur_account@active

Issue Tokens
./cleos --url http://209.97.162.124:808 push action ur_account issue '[ "issue_account", "50000000000.0000 PAYA", "memo" ]' -p ur_account@active

Transfer token
./cleos --url http://209.97.162.124:8080 push action ur_account transfer '[ "sender", "reciv" "10000.0000 PAYA", "memo" ]' -p sender@active

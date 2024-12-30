1. Get your Alchemy node URL `https://eth-mainnet.g.alchemy.com/v2/fjsahfejdhfdkfsjk` -> Something like this
2. Go to the Foundry folder and complete your test 
3. Run the test with the test name 
```bash
forge test --match-test "test_name" --fork-url $FORK_URL
```
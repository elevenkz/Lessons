# Lessons
python

This code uses the requests library to make GET requests to the DEXs' APIs to get the token's price. 
The get_token_price function takes a single argument, token_symbol, which is the symbol of the token to check the price of. 
The function first defines a list of DEXs to check, and initializes two variables best_price and best_dex to keep track of the current best price and the DEX it is on. 
Then the function iterates through the DEXs and for each DEX, it makes a GET request to the DEX's API to get the token's price, then it compares the price with the current best price and if it is lower it updates the best price and best DEX. 
At the end of the loop, the function returns the best DEX and price.

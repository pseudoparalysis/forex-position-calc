# Forex Position Calculator
The exchange rate is pulled from "https://api.exchangeratesapi.io/".
The table of exchange rates will change accordingly when the base currency changes.
Note that the currency pairs displayed in the table might not be the standard currency pairings.

# Features
- Exchange rates are automatically cached to localStorage. (If the broswer does not support local storage, no caching will happen)
	- If the api call fails to pull the updated exchange rates, the calculator will get the exchange rates from an existing cache.
- Saving details will save your capital size and risk inputs into localStorage.

# Important
The exchange rate API is no longer fully open.
Sign up is required to get an API key and there is a rate limit.
Read the API's documentation and update the API call to use this calculator.


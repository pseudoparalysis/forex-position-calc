# Forex Position Calculator
The exchange rate is pulled from "https://api.exchangeratesapi.io/".
The table of exchange rates will change accordingly when the base currency changes.
Note that the currency pairs displayed in the table might not be the standard currency pairings.


# Features
- Exchange rates are automatically cached to localStorage. (If the broswer does not support local storage, no caching will happen)
	- If the api call fails to pull the updated exchange rates, the calculator will get the exchange rates from an existing cache.
- Saving details will save your capital size and risk inputs into localStorage.

Fitbit Automatic Download
v0.0.1

This is a python program in development that will use the urllib2 library and the Fitbit API to automatically download the user's health information. It is possible to write the data to a local sqlite3 database.

The benefit of this programs is to not have to pay for the yearly subscriptions by automatically downloading the information at the desired time interval.

Requirements:
	1. An account on fitbit.com with a verified email address
	2. A registered app on dev.fitbit.com
		2a. The implicit grant flow is used for OAuth 2.0 authentication
# APIs




# AXIOS


# API Authentication
1. No authentication
- API Limit, checking each IP address for how many requests are being made by them and limit it.
2. Basic Authentication
- Username & Password
- Passing of username and password as the header in Base64 encoding (username:password)
- Authorization in Postman, Basic Auth, Postman generates header from the username and password as Basic username:password
- If intercepted, can be decoded.
```
let result = await axios.get(
		"https://secrets-api.appbrewery.com/all?page=2",
		{
			auth: {
				username: yourUsername,
				password: yourPassword,
			},
		}
	);
```
3. API Key authentication
-Safer because you can delete and regenerate keys
```
	let result = await axios.get(
		`https://secrets-api.appbrewery.com/filter?score=7&apiKey=${yourAPIKey}`
	);
```
4. Token Based Authentication
- Logged in with usename:password, then token is generated and used by API, without directly involving itself with username/password
- Thid-party app asking for login, takes the username and password to generate and token, then uses that token to interact with other services that you used your login for, based on the token, the third part app can do anything with the token.
```
	let result = await axios.get(
		"https://secrets-api.appbrewery.com/secrets/42",
		{
			headers: {
				Authorization: `Bearer ${yourBearerToken}`,
			},
		}
	);
```



* Normally API providers paginate the response so that huge amounts of data is not sent in one go.
* ### Authorise/Authenticate
* Authentication => Allows you to be identified as an user to the API Provider
* Authorisation => Let's you use the API 


# REST API
1. Various AXIOS commands/functions, e.g. post, get, put, patch, delete, get
2. Importance of Config tag
3. app.use(express.static("public")

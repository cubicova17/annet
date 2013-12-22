1. MVP
	a) User tracks metric track('Pageview',dictionary, timestamp)
	b) Program remotely does js API request
	c) On a server side User can login to his profile and check his metrics
2. Design
	a). JS lib to invoke API calls
	b) simple django auth on server
	c) Django api for receiving api calls from js
	d) redis for metrics
3. Methods

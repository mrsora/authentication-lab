# Answers
1. Basic and Session authentication. Adding to DEFAULT_AUTHENTICATION_FRAMEWORK in settings.py
2. Basic authorisation, using username:password
3. Session stores authencation details in server, while token is just stored by client
4. Client requests permission to access service resources from Resource Owner (eg. bitbucket), which then returns an authorisation grant, which the client then sends to the Authorisation Server (eg. google), then the client receives an access token. The client can then use the access token to access the Resource server (bitbucket contents), and the server sends it to the client.
5. https://github.com/mrsora/authentication-lab
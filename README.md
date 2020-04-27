# BoxToSharePoint

create a box developer account and sign in to register your application 
  here: https://cloud.account.box.com/login?redirect_url=/developers/services/edit/
 
set your redirect URI (www.google.com)

Select your scopes

Make note of client_id and client_secret

Use a GET request
  GET https://account.box.com/api/oauth2/authorize?response_type=code&client_id=MY_CLIENT_ID&state=security_token%3DKnhMJatFipTAnM0nHlZA

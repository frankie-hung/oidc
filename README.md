# OIDC SPA Demo
This is a sample webapp to illustrate a Single Page Application (SPA) using authorization code flow with PKCE.

## Setup
1. Create a service from a OIDC provider, authgear.com in my example.
2. Config the redirect_url (e.g. http://localhost/callback.htm) in OIDC provider.
3. Edit spa.htm form to update the authorization endpoint, client_id and redirect_url.
4. Edit callback.htm form to update the token endpoint, client_id and redirect_url.
5. Upload both files in your web server.

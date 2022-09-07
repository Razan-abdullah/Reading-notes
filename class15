#  Authentication

- [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html){:target="_blank"}

  1. What is OAuth?

OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

  
1. Give an example of what using OAuth would look like.

The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website


  1. How does OAuth work? What are the steps that it takes to authenticate the user?

1- The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
2- The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
3- The first site gives this token and secret to the initiating user’s client software.
4- The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
5- The user approves (or their software silently approves) a particular transaction type at the first website.
6- The user is given an approved access token (notice it’s no longer a request token).
7- The user gives the approved access token to the first website.
8- The first website gives the access token to the second website as proof of authentication on behalf of the user.
9- The second website lets the first website access their site on behalf of the user.
10- The user sees a successfully completed transaction occurring.



  1. What is OpenID? 

OpenID. At a base level, the distinction between the two is simple to grasp. 

- [Authorization and Authentication flows](https://auth0.com/docs/flows){:target="_blank"}

  1. What is the difference between authorization and authentication?

Authentication and authorization are two vital information security processes that administrators use to protect systems and information. Authentication verifies the identity of a user or service, and authorization determines their access rights

  1. What is Authorization Code Flow?



  1. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The user clicks Login within the regular web application.

Auth0's SDK redirects the user to the Auth0 Authorization Server (
/authorize
endpoint).

Your Auth0 Authorization Server redirects the user to the login and authorization prompt.

The user authenticates using one of the configured login options and may see a consent page listing the permissions Auth0 will give to the regular web application.

Your Auth0 Authorization Server redirects the user back to the application with an authorization code, which is good for one use.

Auth0's SDK sends this code to the Auth0 Authorization Server (
/oauth/token
endpoint) along with the application's Client ID and Client Secret.

Your Auth0 Authorization Server verifies the code, Client ID, and Client Secret.

Your Auth0 Authorization Server responds with an ID Token and Access Token (and optionally, a Refresh Token).

Your application can use the Access Token to call an API to access information about the user.

The API responds with requested data.

  1. What is Implicit Flow with Form Post?
  1. What is Client Credentials Flow?
  1. What is Device Authorization Flow?
  1. What is Resource Owner Password Flow?



## Bookmark and Review

- [Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react){:target="_blank"}

# Reading Class 15

What is OAth

1) OAuth is open-standard authorization protocol that allows access without sharing the initial related single logon credential.

2) With a logon to a website, you can use one or more opportunities to log on using another service for login, suche as your Google account.

3) OAuth uses authorization tokens to prove an identity between two entities. The authorization token was previously established when you logon with another service, and the logon service verifies it was the user before establishing authorization tokens with site needing the token.

4) OpenID is authentication of the user, verifiying the user itself.

Authentication and Authorization Flows

1) Difference between authentication and authorizations is mainly about verifying the user, versus verifying if the user has access.

2) Authorization code flow is the process which the exchang of an Authorization Code for a token between OAuth and another login service.

3) Proof Key for Code Exchange (PKCE) is specifically for mobile and native applications, since there is no way to securely store the Client Secret.

4) Implicit Flow with Form Post is when web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, it is unnecessary to obtain, maintain, use, and protect a secret in the application.

5) Client Credentials Flow is when the system authenticates and authorizes the app rather than a user.

6) Device Authorization Flow is when the device asks the user to go to a link on their computer or smartphone and authorize the device.

7) Resource Owner Password Flow is the process which requests that users provide credentials (username and password), typically using an interactive form

## Things I want to know more about
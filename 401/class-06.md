# Reading Class 03

Securing Passwords

1) Hashing is process where data is scrambled into a short string using some sort of encryption algorithm. This process is a one way function, so once scrambled, it can't be unscrambled and reverted back to the original string. To make sure the password is correct, the client compares the two hash to see if they're the same, which indicate they inputted the correct password.

2) Bcrypt is a encryption algorithm that uses key stretching, which dynamically increase how expensive the hash function needs to be.

3) As brute forcing techinque become faster, with Bcrypt, the hash function encryption is also increased, scaling with the brute force efficiency.

Basic Auth

1) Basic authentication is a method for HTTP user agent (ex a web browser) to provide a username and password associated when making a request, to gain access to restricted resources provided for the user who logged in.

2)A necessary property in the header for Basic Auth is Authorization: Basic credentials, where credentials is the Base64 encoding of ID and password joined by a single colon :

3) See above.

OWASP auth cheatsheet

1) UserID and a robust set of rules for password is required. At login, the userID and password is securely transmitted over to the server side. If the credentials matches what was stored on the server side, requested data would be

2) Error message from HTTP status codes should be kept to bare mininmum, in order to not reveal any other information about the login. The same with HTML. The behaviour of HTML should be the most generic message about the failed login.
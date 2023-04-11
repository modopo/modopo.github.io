# Reading Class 03

Intro to JWT

1) JSON Web Token iss a compact, URL-safe means of representing claims to be transferred between two parties.

2) JWT are commonly used for authentication and authorization in web applications and APIs with information exchange.

3) Claims are expected in the payload.

Basic Auth

1) If you can decode the payload of a JWT, it doesn't necessarily mean that the JWT is not secure. The security of a JWT depends on what cryptographic algorithms were used , and the integrity of the signature.

2) The same secret

3) JWT can be signed using a secret key known only to the issuer. The signature is used to verify the authenticity of the JWT and to ensure that it has not been tampered with. The recipient can use the same secret key to verify the signature and to decrypt the payload to access the content.

JWTs Explained

1) JWT is commonly used for securely transmitting information between parties as a JSON object. It is stateless and digitially signed.

2) JWT is compact and self-contained because it contains all the necessary information within the token itself, including the payload and the signature. This makes it easy to transmit and store the token, without needing to access an external storage or database. This allows for faster and more efficient transmission and processing of the token, as it doesn't require additional lookups or queries.

3) Header: The header of the JWT contains information about the type of token and the signing algorithm used. Payload: The payload of the JWT contains the actual data being transmitted, such as user information or authorization details. Signature: The signature of the JWT is a string of characters created by signing the header and payload using a secret key. The signature is used to verify the authenticity of the token and to ensure that it has not been tampered with.
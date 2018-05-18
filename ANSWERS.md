<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.

### Middleware is the go between function used in apps that have data being used across multiple routes and servers.

### Express-sessions creates a unique browsing session for distinct users by validating cookies. 

### bcrypt is a password hashing function that is meant to add a layer of protection to user data. 

### JSON Web Tokens are another way of validating distinct users by hashing whole identities and allowing the user to browse through encrypted credentials.

2.  What does bcrypt do in order to prevent attacks?

### bcrypt stores a hashed iteration of a users password in the database to protect the information as an added layer of protection from hacker attacks.

3.  What are the three parts of the JSON Web Token?

### the JWT is comprised of a header, a payload, and a signature. The header is the beginning of the hashing algorithm and tells you basic information about the token such as the type. The payload is essentially the user information that is being stored in the token. The signature is an encrypted string that the browser passes back after reading the header and payload. It acts as the final point of entry for a user hoping to browse a webpage with hidden credentials.
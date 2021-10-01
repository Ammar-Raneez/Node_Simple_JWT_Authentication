# This is a simple JWT Authentication example using refresh and access tokens with token expiry

## Generate random 64 byte hex string for JWT signing
### require('crypto').randomBytes(64).toString('hex')


# Test environment not ideal for prod, instead, use a DB or a Redis cache to store refresh tokens

<p>This is a simple JWT Authentication example using refresh and access tokens with token expiry</p>

Generate random 64 byte hex string for JWT signing: <code>require('crypto').randomBytes(64).toString('hex')</code>

<p><strong>Test environment not ideal for prod, instead, use a DB or a Redis cache to store refresh tokens</strong></p>

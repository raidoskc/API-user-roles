create env file for access and refresh token (secret key).

require('crypto').randomBytes(64).toString('hex')

ACCESS_TOKEN_SECRET=YOUR_VALUE
REFRESH_TOKEN_SECRET=YOUR_VALUE

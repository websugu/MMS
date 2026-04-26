# Fix Email Sign-In — Switch to Email/Password Auth

## Goal

Remove email verification requirement and allow users to sign in with email and password only.

## Steps

- [x] 1. Update `JS/login.js` — Rewrite signup() to use actual password from form, remove email verification
- [x] 2. Update `JS/login.js` — Rewrite login() to use email + password only, remove phone lookup logic
- [x] 3. Update `login.html` — Replace phone fields in login form with password field
- [x] 4. Update `login.html` — Keep signup form password field (now actually used)
- [x] 5. Verify the auth flow changes

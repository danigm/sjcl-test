# sjcl-test
Javascript SJCL crypt library test with symmetric and asymmetric crypt

In this js example we generate a pair of asymmetric keys but we encrypt the
private key with a password, to make it storable in a database but not
usable if you don't know the password.

This is usable for example to store in a database encrypted messages for an
user, encrypted using the public key. We also store the private key, but
it's encrypted with a password so admins can't decrypt any message, only
the user with his password can decrypt the secret key and then with the
secret key decrypt the real message, all in js.

## links
 * http://bitwiseshiftleft.github.io/sjcl/doc/
 * https://github.com/bitwiseshiftleft/sjcl/wiki/Asymmetric-Crypto

# Alpine-SSH
Alpine Linux docker image with SSH support.

## Features
 - Allows **ONLY** key-based authentication
 - Uses hardened SSHD config from https://cipherli.st
 - SSHD logs to stderr, so errors are visible in docker log

## Usage

 - Put your public key into the AUTHORIZED_KEYS environment variable
 
## Notes

 - This uses hardened settings, so DSA keys (and maybe others) are not supported.  If you can't login, check the log.
 - Not up-to-date? Just let me know, I'll trigger a build!!
 

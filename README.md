=== README ===

netcat-encrypted-transfer is a set of two bash scripts that allows
you to exchange files between Linux servers without having to
worry about security thanks to OpenSSL. Enjoy the flexibility and
powers of netcat and openssl together with this set of tools!

 - Requirements:

   netcat and openssl installed on both client and server.

 - Usage:

   ./send [ip] [port] [file] --- Send a file

   ./receive [port] [file]   --- Receive a file
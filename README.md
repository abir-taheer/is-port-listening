# is-port-listening

This is purely a command line tool to determine if a port is open or closed.

Exits with code 0 if the port is being used by another process and exits with code 1 if the port is not listening and available.

Example usage:

```
npx is-port-listening --port=3000 && echo "An app is running on port 3000"
```

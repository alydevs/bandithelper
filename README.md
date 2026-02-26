bandithelper
============

depends on: sshpass

1. run `./bandit` once to create and populate the solutions directory with the example
2. put any known passwords into `.bandit`
3. if any password fails, the cache will be invalidated and solutions will be run to acquire them again
4. Put your solutions in `solutions/$number.sh`, these are bash scripts that are run on the server

# slack (cli)
Yet another command line interface to a python module: `slackclient`.

Usage:
```
# Send a message
slack -t "xoxb-XXXXXXXX-YYYYYYYYYYYYY-ZZZZZZZZZZZZZZZZZZZZZZ" -c D014F3MSW2C "Hello"

# Send a message using stdin
tail /var/log/messages | slack -t "xoxb-XXXXXXXX-YYYYYYYYYYYYY-ZZZZZZZZZZZZZZZZZZZZZZ" -c D014F3MSW2C

# Send a file / snippet
slack -t "xoxb-XXXXXXXX-YYYYYYYYYYYYY-ZZZZZZZZZZZZZZZZZZZZZZ" -c D014F3MSW2C --upload ./filename -v
```

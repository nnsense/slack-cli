# slack (cli)
Yet another command line interface to a python module: `slackclient`.

Usage:
```
# Send a message
slack-cmd -t "xoxb-XXXXXXXX-YYYYYYYYYYYYY-ZZZZZZZZZZZZZZZZZZZZZZ" -c D014F3MSW2C "Hello"

# Send a message using stdin
tail /var/log/messages | slack-cmd -t "xoxb-XXXXXXXX-YYYYYYYYYYYYY-ZZZZZZZZZZZZZZZZZZZZZZ" -c D014F3MSW2C

# Send a file / snippet
slack-cmd -t "xoxb-XXXXXXXX-YYYYYYYYYYYYY-ZZZZZZZZZZZZZZZZZZZZZZ" -c D014F3MSW2C --upload ./filename -v
```

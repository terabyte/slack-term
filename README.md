Slack-Term
==========

A [Slack](https://slack.com) client for your terminal.

*This project is still in development*, but you can test it by downloading one
of the binaries for your system from the `bin` folder. Rename the file for
convenience into `slack-term` and create a `slack-term.json` file with
the following contents in your home folder.

```
{
    "slack_token": "yourslacktokenhere"
}
```

Run `slack-term`: 

```bash
$ ./slack-term
```

Usage
-----

| key       | action                   |
|-----------|--------------------------|
| `i`       | insert mode              |
| `left`    | move input cursor left   |
| `right`   | move input cursor right  |
| `esc`     | normal mode              |
| `k`       | move channel cursor up   |
| `j`       | move channel cursor down |
| `pg-up`   | scroll up chat pane      |
| `pg-down` | scroll down chat pane    |
| `q`       | quit                     |


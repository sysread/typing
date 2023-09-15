# NAME

typing

# SYNOPSIS

```
echo "How now brown bureaucrat" | typing
```

# DESCRIPTION

Prints piped output to the terminal, introducing short delays to make it appear
as though it is being typed by a person.

![Typing the truth](./assets/thetruth.gif)

![Typing Shakespeare](./assets/shakespeare.gif)


# OPTIONS

- `--help` - show help information
- `--slow` - type slower
- `--fast` - type faster

# ENV VARS

- `TYPO_PROBABILITY` - the number of chances out of 10,000 that a typo will be
  introduced (and then corrected). Defaults to **50**.

# Telesm
An offline-first dictionary using WordNet

## Why Offline?
I'm sick of online dictionaries. Most of them display lots of ads which is distracting, and almost none of them let you save the words to review them in the future and memorzie them, unless, well, you pay for a premium package.

## Introducing Telesm
So, here's an offline dictionary that uses WordNet to display the definition and the examples of a word. It saves your searched words in a list so you can check them later in your spare time.

## Terminology
Telesm is the Persian word for Talisman.

## Installation
Using `pip`:

```bash
pip install telesm
```

Or if you want to have it globally:

```bash
pipx install telesm
```

## Usage

### Definition of a word

```bash
telesm <word>

# Example output:
talisman:
        ‣ a trinket or piece of jewelry usually hung about the neck and thought to be a magical protection against evil or disease
```

This will save the word to the database by default, if you don't want to save the word pass `--no-save` argument.

```bash
telesm <word> --no-save
```

### List all words

```bash
telesm --list
```

If you want to navigate over the words one by one, pass `--navigate` argument:

```bash
telesm --list --navigate
```

### Random word

```bash
telesm --random

# Example output:
accruing:
        ‣ grow by addition
Examples:
        ⁃ The interest accrues
```

### Search in saved words

```bash
telesm --search tal

# Example output:
talisman:
        ‣ a trinket or piece of jewelry usually hung about the neck and thought to be a magical protection against evil or disease
```

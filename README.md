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

## Usage

- To search for a meaning of a word:

```bash
telesm <word>
```

This will save the word to the database by default, if you don't want to save the word pass `--no-save` argument.

```bash
telesm <word> --no-save
```

- To list all the saved words:

```bash
telesm --list
```

If you want to navigate over the words one by one, pass `--navigate` argument:

```bash
telesm --list --navigate
```
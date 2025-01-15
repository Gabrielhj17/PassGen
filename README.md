# PassGen

A command line password generator

## Prerequisites

Homebrew installed on your system

If not go to: [Homebrew Installation](https://docs.brew.sh/Installation)

## Installation

Open terminal and run:
```bash
brew tap Gabrielhj17/tools
```

Followed by:
```bash
brew install passgen
```

## Usage

After installation you can run:
```bash
passgen
```

You will be given a 12 character password with special characters, numbers, upper-case and lower-case letters

## Changing password length
To change the length of the generated password, add a number after the passgen keyword
For example, to generate a 16 character password run:

```bash
passgen 16
```

## Removing special characters

To remove special characters from your password, add the following tag after 'passgen':
```bash
--no-special
```

Example:
```bash
passgen --no-special
```

## Removing numbers

To remove numbers from your password, add the following tag after 'passgen':
```bash
--no-numbers
```

Example:
```bash
passgen --no-numbers
```

## Removing upper-case letters

To remove upper case letters from your password, add the following tag after 'passgen':
```bash
--no-uppercase
```

Example:
```bash
passgen --no-uppercase
```

## No requirements

By default the generated password will require one of each character type, you can disable it by adding the following tag after 'passgen'
```bash
--no-requirements
```

Example:
```bash
passgen --no-requirements
```

## Combining tags

Tags can be combined in any way you desire, for example if you wanted a 20 character password with no special characters you could do as follows:
```bash
passgen 20 --no-special
```

## Help

If you're stuck and require help or a reminder of the keywords you can run as follows:
```bash
passgen -h
```

Or also
```bash
passgen --help
```

















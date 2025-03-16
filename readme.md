# Pretty Password Generator

[deployed page](https://toricubes.github.io/password-generator/)

## Description

Password generator that allows the user to choose from the following character sets:
- uppercase letters
- lowercase letters
- numbers
- special characters

Also allows the user to exclude characters from the generation set. This allows for compatibility with certain password fields/prompts that disallow certain characters.

Uses the [Web Crypto API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API) to pull random characters from a given set.
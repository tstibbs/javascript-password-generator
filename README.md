[![License: MIT](https://img.shields.io/github/license/tstibbs/javascript-password-generator)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/tstibbs/javascript-password-generator.svg)](https://github.com/tstibbs/javascript-password-generator/issues)

## What is this?
A simple javascript password generator, giving you choices about what characters you want to use to make up the password: http://tstibbs.github.io/javascript-password-generator/generate.html

## Isn't it a bad idea to have some website generate my password?
The password is generated in your browser; this tool does not transfer your password anywhere.

## Is is cryptographically secure?
No. It's uses javascript's `Math.random()`, see http://stackoverflow.com/questions/5651789/is-math-random-cryptographically-secure. That doesn't mean it's useless though, it's still better than using 'password123' for each of your passwords.

## Why is the javascript embedded within the html?
So you can just download the file and run it locally if you'd feel more comfortable using it that way.

## Contributing

PRs are very welcome, but for any big changes or new features please open an issue to discuss first.

# Disclaimer
I am not responsible for anything bad that happens as a result of your use of this tool or its code. This tool is meant purely for education. Password security is an important and complex topic and you should not blindly trust some random guy on the internet. 

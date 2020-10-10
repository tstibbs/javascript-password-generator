![Project Screenshoot](/images/screenshoot.png?raw=true)

## What is this?
A simple javascript password generator, giving you choices about what characters you want to use to make up the password: https://sitemapxml.github.io/password-generator/

## Isn't it a bad idea to have some website generate my password?
The password is generated in your browser; this tool does not transfer your password anywhere.

## Is is cryptographically secure?
No. It's uses javascript's `Math.random()`, see http://stackoverflow.com/questions/5651789/is-math-random-cryptographically-secure. That doesn't mean it's useless though, it's still better than using 'password123' for each of your passwords.

## Why is the javascript embedded within the html?
So you can just download the file and run it locally if you'd feel more comfortable using it that way.

# Disclaimer
I am not responsible for anything bad that happens as a result of your use of this tool or its code. This tool is meant purely for education. Password security is an important and complex topic and you should not blindly trust some random guy on the internet. 

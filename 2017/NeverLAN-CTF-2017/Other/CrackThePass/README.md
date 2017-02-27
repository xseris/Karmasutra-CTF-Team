# CrackThePass

Points : 150

Solves : 38

## Question
The 'bad guys' have cryptolocker-ed your company, but they weren't very smart. They left the key on a system in SHA1 format. Didn't they know SHA1 was dead?

Here's the SHA1 key. Can you get the password?
ac0a96e036d11092712ef57f59ff9c7cb81fd909

Hint 1: Password reuse is a bad idea, but some people still use their old rockyou password

## Solution
Just decode the SHA-1 key:

![flag](https://github.com/xseris/Karmasutra-CTF-Team/blob/master/2017/NeverLAN-CTF-2017/Other/CrackThePass/decoded.jpg)

PWDUMP8

We decided to add a new version in the pwdump saga just because since win 10 v1607 was released, MS moves obfuscation techniques away from RC4 encryption to AES (128 cbc-mode) so, on those systems, tools like pwdump7 and others no more dumps the nt\lm hashes correctly. Pwdump8 requires administrative privileges, as previous releases.

- Compatible with AES-encrypted hashes
- Supported windows versions: 2000/XP/Vista/7/2008/8/8.1/10/2012/2016/2019
- Works with local system, dumped reg files

25.06.19 Released pwdump - version 8.2
 Added support for domain cached account
 Fully supporting dump from file (both SAM and SECURITY reg hives)
 Minor bugfix

11.05.19 Released a new version of pwdump: pwdump8 by blackmath now supports AES-128 encrypted hashes and works on Windows 10 v1607 and later As no source code is available since pwdump version 6, we've rebuilt it all from scratch. Please submit any bug / suggestion to info@blackMath.it, source code will be available soon.. enjoy your(..or not..) hashes!!

http://www.blackmath.it

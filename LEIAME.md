# KokoroReader
Open source online manga reader.

## Links
- Projects page on developers personal site: https://linux.ime.usp.br/~duilio/?kokoro
- Wiki: https://github.com/duiliofelix/KokoroReader/wiki
- Sites running Kokoro Reader:
 - http://s2yuri.16mb.com/

## Content
- Description
- Installing / Using
- Coding

## Description
Kokoro Reader is an open source, free to use online manga reader. Its objective is to give a simple, yet powerfull tool to scanlators for upload and distribute their contents. At same time, its meant to be a good and complete reader for any user who wants to read manga or talk about it with the scanlators community.

Some of the planned features are:
- Easy installing
- Full documentation
- Tool for upload content
- Tags for series and chapters
- Tool for organize the translation team
- Reader module with customizable options
- User acounts with manga list
- Lots of infos feedback for all users (admin, translation team, final reader)
- Multi-language support
- Multi-skin support

If you want to use it, just download and push to your server, its free =D. All that I ask is to messsage me a link to the site for me to know how much the project is being used.
Any problemns or bugs, just message me. If you want to help with coding, please read about de projects decisions below.

## Installing / Using
The project is meant to be super easy to install. If you already have PHP, MySQL and Apache installed, all you need to do is download the code to your server and run <---> from your browser.
This script will build up your database and configure all the needed files.
In the default setup, a user with all the privileges will be created with username and password set as 'admin'.

## Coding
If you want to help the development, here is some of the main philosophies about the code:
- The project is built in a MVC model -without- frameworks.
- The code is meant to be simple and easy to read/modify.
- Code in the dev branch or some another subbranch, never in master.
- We use -Propel- as ORM (Do not throw SQL in the code randomly).
- Identation -is- very important.
- Use just one pattern (If you see variables in camel casing, use camel casing to name yours).
- Comments in the code are wellcome, but no need to spam them.

All these itens and much more are described in the wiki.

LittleBirdy
============

LittleBirdy is PDF security utility designed to remove the Permissions Password and all associated restrictions from PDF files. It also has the ability to remove Document Open Passwords, but only if the Document Open Password is known.

**If you don't know the Document Open Password for a PDF file, LittleBirdy cannot operate on it!** It is only designed for removing Permissions Passwords automatically, and removing Document Open Passwords *if they are known*. So, if you've forgotten the Document Open Password for a PDF file (or otherwise need to access a password protected PDF), please look elsewhere.



Quick start
-----------

Clone the repo, `git clone git@github.com:jakepetroules/litlebirdy.git` and make sure GhostScript is installed on your system and in your `PATH`. You can download a copy of that [here](http://www.ghostscript.com/download/gsdnld.html).

Once you've downloaded LittleBirdy, all you need to do is run `./littlebirdy /path/to/document.pdf`. LittleBirdy will prompt you for the Document Open Password - again, if the document has one you *must* provide it. If the document does not have a Document Open Password, simply press enter without typing a password. LittleBirdy will then proceed to remove the Document Open Password and Permissions Passwords from the document, and save it in an "unlocked" folder relative to the location of the littlebirdy script.

LittleBirdy also comes with several PDF test files with varying levels of restriction if you simply want to try out its functionality.



Bug tracker
-----------

If you've found a bug, please create an issue here on GitHub!

https://github.com/jakepetroules/littlebirdy/issues



Authors
-------

**Jake Petroules**

+ http://twitter.com/jakepetroules
+ http://github.com/jakepetroules



History
-------

Why is this application called LittleBirdy? Back in college I had a professor who would provide his students with lecture notes in the form of password-protected PDF files. The reason for this was because he didn't trust Blackboard to store them securely, so he would upload the encrypted notes to Blackboard and email his students the Document Open Passwords. For us students, this was very annoying since we would have to type the password every time we wanted to view his notes, and in addition the Permissions Password prevented some things like copying and highlighting, which often would have been useful. Needless to say, LittleBirdy proved quite useful for us during this professor's classes.

The name itself comes from an inside joke this professor had with his students, where he would often begin a sentence with "My little birdy tells me..." and then proceed to tell us what he thought we were thinking. This application is named after that particular avian.

*For the record, the professor in question is aware that I made this application and used it on his lecture notes for the benefit of myself and the other students taking his class, and had no issues with that.*



Copyright and license
---------------------

Copyright (c) 2012 Jake Petroules. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

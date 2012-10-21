uniquelyidentified.schema
=========================

This package contains LDAP schema for cyrus mailbox server and cyrus-aware
management tools.

WORD OF CAUTION
===============

This is experimental schema. It is also advisable to test it on non-production
setup before deciding to use it with production service. The schema is under
development and may change without notice.

INTRODUCTION
============

TODO:

REQUIREMENTS
============

TODO:

INSTALLATION
============

The files to install are located within **schema** directory. The
**schema/ezmcyrus.schema** may be used for traditionally configured servers.
Follow standard instructions for your directory server. For OpenLDAP with
new-style config (olcXxx) use **schema/ezmcyrus.ldif** as follows:

`sudo ldapadd -Y EXTERNAL -H ldapi:/// < schema/ezmcyrus.ldif`

LICENSE
=======

Copyright &copy; 2012 by Paweł Tomulik

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE

# tpm
Tina's Package Manger

Dependencies:
-

curl

Server:
-

set up a http server with for example nginx, and create a user accessible folder on the http server.
this folder needs to contain a "index.html" file with a list of downloadable packages, and the
packages themselves, in the ".tar.gz" format (you can remove the file ending, for easier downloading)

Client:
-

git clone https://github.com/Tina-lel/tpm && cd tpm

chmod +x tpm config

open up "config" in a text editor and edit the variables to point to a http server.

config variables:

"HOST" = a http server

"PORT" = the http port

"DIR" = remote directory containing a "index.html" file with a list of packages, and packages in tar.gz format

"EDIR" = directory to extract files to on your machine

Ussage:
-

-h : help

-d : download

-l : list

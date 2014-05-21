Dummy-SMTP
==========

A dummy Linux SMTP server that drops emails to a folder, instead of sending them.


It’s really simple to use :

1.    Download the .zip
2.    Extract it
3.    Make “listen.py” executable
4.    Kill any process using port 25 (usually “sudo pkill sendmail” is enough)
5.    Type “sudo ./listen.py” on your console
6.    Tada! All emails sent will be dropped in the “mails” folder.

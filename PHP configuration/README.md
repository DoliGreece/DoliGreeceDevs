Αν χρειάζεται για λόγους συμβατότητας τοποθετήστε το .htaccess αρχείο για την 7.4 στο htdocs

Μελοντικά μπορειτε να τροποποιήσετε ανάλογα για:
// PHP 8.0
FcgidWrapper "/home/httpd/cgi-bin/php80-fcgi-starter.fcgi" .php

// PHP 8.1
FcgidWrapper "/home/httpd/cgi-bin/php81-fcgi-starter.fcgi" .php

// PHP 8.2
FcgidWrapper "/home/httpd/cgi-bin/php82-fcgi-starter.fcgi" .php

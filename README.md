mediawiki-backup
================

Mediawiki dumpgenerator (based on [http://code.google.com/p/wikiteam/](wikiteam archiving tools).

Only changes to dumpgenerator.py are `username` and `password` parameters
for dumping a wiki with HTTP Basic authentication.

For example:
    ./dumpgenerator.py --username=USER --password=PASSWORD --api=http://WIKI.URL/w/api.php --xml

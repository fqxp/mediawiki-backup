mediawiki-backup
================

Mediawiki dumpgenerator (based on the [wikiteam archiving tools](http://code.google.com/p/wikiteam)).

Added `username` and `password` parameters to `dumpgenerator.py`
for dumping a wiki using HTTP Basic authentication.

For example:

    ./dumpgenerator.py \
        --username=USER --password=PASSWORD \
        --api=http://WIKI.URL/w/api.php --xml

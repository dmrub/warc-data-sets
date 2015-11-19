# warc-data-sets
WARC Data Sets

In order to remove chunked encoding do following:

sudo pip install warctools
./warc2warc.py -D input-warc-file.warc > output-warc-file.warc

Note that warc2warc.py is slightly modified version to the one provided with warctools package:
https://pypi.python.org/pypi/warctools

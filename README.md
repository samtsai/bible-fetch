# Bible Fetch

A command line tool for fetching bible passages from biblegateway.com.

## Prerequisites

[Beautiful Soup 4](http://www.crummy.com/software/BeautifulSoup/), [Requests](http://docs.python-requests.org/en/latest/), and [Unidecode](https://pypi.python.org/pypi/Unidecode/) are required to run bible-fetch.

```bash
pip3 install beautifulsoup4 Requests Unidecode
```

## Running

```bash
./bible psalm 23
./bible jn 3.16 --version NLT
./bible luke 5.1-11 --verse-numbers
./bible John 12:23-26 --ascii
```

## License

MIT style license (see LICENSE).

# Noun-Phrase Extractor Service

Noun-Phrase Extractor Service was mirrored from [jprobinson's newshound](https://github.com/jprobinson/newshound/tree/master/lib/np_extractor).

When the service starts, it will setup a quick noun-phrase extractor that has been trained with NLTK's Brown corpora and expose it on port 1029.

You can post to the server directly or import the np_extractor.service module and run `service.np_extract("text")` as long as the service is running locally.

This library expects the following Python modules to be installed:

- `pip install -r requirements.txt`
- nltk's brown corpora, stopwords and punkt tokenizers

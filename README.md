## Solr Hammer

Simple tool build with Thor to enable you to send search requests to a specified solr server.

Hammer generates a default 100 term dictionary file and uses that to run searches.

You can generate a larger dictionary file with a </code>hammer dictionary -n NUMBER</code> command or use your own.

Results are logged into <code>response.log</code> file and contain the term, results number, HTTP and Solr headers.

# Chapter 3: Developers

_We're going to hold off on the details of installing Riak at the moment. If you'd like to follow along, it's easy enough to get started by following the [install documentation](http://docs.basho.com/riak/latest/) on the website (http://docs.basho.com). If not, this is a perfect section to read while you sit on a train without an Internet connection._

Developing with a Riak database is quite easy to do, once you understand some of the finer points. It is a key/value store, in the technical sense (you associate values with keys, and retrieve them using the same keys) but it offers so much more. You can embed write hooks to fire before or after a write, or index data for quick retrieval. Riak has SOLR search, and lets you run MapReduce functions to extract and aggregate data across a huge cluster in relatively short timespans. We'll show some configurable bucket-specific settings.


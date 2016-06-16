# A Repository for Dash Docsets

To learn more about Dash, go here: https://kapeli.com/dash

## Why This Repository

Dash comes with a bunch of docsets available by default.  However, it can't have everything and it is easy to create your own.  Dash maintains a set of user-contributed Docsets.  It too, of course, can't have everything.  So I created my own for Apache Spark and perhaps some others in the future.  I can't commit to maintaining it as new versions come out, so I can't contribute it to the official Dash collection.  I do want to make it available, however. Hence this repository.

## Disclaimer

I'm happy when people download and use this docset.  However, I cannot fix problems or otherwise offer support.  It is provided "as is."

## How did I create these?

Easy to use scripts are provided by Dash for many platforms: https://kapeli.com/docsets

You'll need a Javadoc (or similar for other languages) folder to get started.  Is the only documentation you have online?  Then you can scrape it to a local folder before buildling the docset.  Here are the instructions I followed to use wget to scrape Apache Spark's javadoc: http://stackoverflow.com/questions/6597562/rip-javadocs-from-a-doc-site-to-a-local-zip-file

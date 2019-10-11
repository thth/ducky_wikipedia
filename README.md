OpenSearch XML for a [Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-wikipedia/) to go directly to the top DuckDuckGo ```site:wikipedia.org``` search result using:

```xml
<Url type="text/html" method="post" template="https://duckduckgo.com/html/">
  <Param name="q" value="\site:wikipedia.org {searchTerms}"/>
</Url>
```
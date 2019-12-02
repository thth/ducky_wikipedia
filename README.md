WebExtensions search overrides [Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-wikipedia/) for going directly to the top DuckDuckGo ```site:wikipedia.org``` search result using:

```json
"search_url": "https://duckduckgo.com/html/",
"search_url_post_params": "q=\\site:wikipedia.org {searchTerms}",
```
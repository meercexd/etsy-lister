# Listing Check for Etsy

A browser-based checker for Etsy sellers who draft product titles and tags outside Shop Manager. Paste your copy to catch common formatting issues before publishing.

## Run it

Open `index.html` in a modern browser. No installation, Etsy login, or API key is required. The tool can run offline, and listing text stays in the tab.

1. Paste a listing title.
2. Paste tags separated by commas or new lines.
3. Select **Check listing** to see issues and suggestions. **Try an example** loads a draft with two things to review.

## Checks

| Check | Feedback |
| --- | --- |
| Empty title or title over 140 characters | Issue |
| More than 13 tags or a tag over 20 characters | Issue |
| Unsupported tag characters or leading punctuation | Issue |
| Repeated tags, missing tags, or a title with 15 or more words | Suggestion |

The checks cover the limits and guidance described in Etsy’s [listing help](https://help.etsy.com/hc/en-us/articles/115015628707-How-to-Create-a-Listing) and [tag help](https://help.etsy.com/hc/en-gb/articles/360000336307-How-to-Use-Tags-to-Get-Found-in-Search). Character counts use Unicode code points after NFC normalization. Etsy’s listing editor determines whether it will accept a draft.

## Contributing

For a rule change, include a link to Etsy’s current guidance and a short example that shows the expected result.

## License

MIT. See [LICENSE](LICENSE). This is an independent tool and is unaffiliated with Etsy.

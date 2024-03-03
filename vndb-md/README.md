# VNDB Markdown Formatter

Replace VNDBID with Markdown hyperlink in espanso.

Install command:

```sh
espanso install vndb-md --git https://github.com/Vinfall/espanso-packages --external
```

Usage:
- Input: `:v12345:`
- Output: `[v12345](https://vndb.org/v12345)`

All VNDBID as per https://vndb.org/d9#4 are supported as well as other prefix like `t`.

More information is available in my blog post [Text Replacement with Espanso](https://blog.vinfall.com/posts/2024/03/espanso/).

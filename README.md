# notacu.lt

## Create a shortlink
To create a shortlink create a pull request, editing the [slugs.json](slugs.json) file.

Slugs should be in alphabetical order and have a description and URL to forward to.

Short URLs are case insensitive, but should be stored in all lowercase.

e.g.
```jsonc
{
  /// ...
  "the-slug-is-the-bit-after-notacu.lt": {
    "description": "Describe where this link goes",
    "url": "https://the-original-long-url"
  },
  // ...
}
```


[![Rockdove logo](https://avatars0.githubusercontent.com/u/8012972?s=18&u=4445fca5751d1c3cdf95c7e62074c358e28530fc&v=4) Rockdove](https://rockdove.uk)

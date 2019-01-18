# Message

Super simple *Markdown* messages in clean HTML.

Install once. Write your text. Build it. Publish with [Netlify Drop](https://app.netlify.com/drop). Share.

## Install

Only the first time.

- [Pandoc](https://pandoc.org/installing.html)
- Clone this repo.

## Build

```bash
mkdir example
pandoc message.md -o example/index.html --css style.css --self-contained --metadata title="Ejemplo"
```

## Deploy

There are several options.

- Host in your own server.
- Host for free with a GitHub repository using [GitHub Pages](https://pages.github.com/) (like this page).
- Use a cloud service like [Dropbox](https://www.dropbox.com/) or [pCloud](https://www.pcloud.com/) to generate an online URL.
- Use an online service like [Netlify Drop](https://app.netlify.com/drop) to publish your site for free.

## Example

- [https://carleslc.me/message/example/](https://carleslc.me/message/example/) using [GitHub Pages](https://pages.github.com/).
- [https://eager-elion-4ce525.netlify.com/](https://eager-elion-4ce525.netlify.com/) using [Netlify](https://app.netlify.com/drop).
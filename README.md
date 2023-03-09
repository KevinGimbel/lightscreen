# lightscreen
> A tiny web app for usage as a reading light. 

<!-- BEGIN mktoc -->
- [How to use](#how-to-use)
- [Development](#development)
- [WHY?](#why)
- [Changelog](#changelog)
<!-- END mktoc -->

## How to use

1. Go to [https://kevingimbel.github.io/lightscreen/](https://kevingimbel.github.io/lightscreen/) on your phone
2. Select a color
3. Enjoy your reading light

## Development

It's a single HTML file (`docs/index.html`) with some HTML, CSS, and a JavaScript Web Component, all in-line and without any build steps.

For development I use the Python `http.server` module, which serves the directory on `localhost:8000`.

```bash
$ python -m http.server
# now go to http://localhost:8000/docs/
```

## WHY?

I've always been super paranoid when it comes to reading light or flash light apps on phones so I decided to make my own as a simple website.

I use it everyday when I read books to my son. :) 

## Changelog

**09.03.2023**

- Refactor to include default colors instead of just a simple color picker
- Add short description and link to source code / website

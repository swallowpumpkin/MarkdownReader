# MarkdownReader

This code will parse your markdown file on local environment.
It searches same name markdown (i.e. README.html searches README.md).

You have to prepare the web server somewhere, because this code needs http connection.
I recommend using python http module if you have python environment.

```
python -m http.server 8080
```

And access to localhost on you web browser.

---

It might be noisy, but if you want to display github-like style, download github-markdown.css from this repository and remove '.markdown-'.

[sindresorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)

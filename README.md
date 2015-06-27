Chris Ashton's CV
=======

This my public CV. As this exists on the web, and as other things exist on the web (namely, bots and spiders that scan for email addresses to spam), some contact information is obscured. My apologies for that.

Quick bit of SEO: CV for @ChrisBAshton, web developer, software engineer, BBC, Webdapper, Aberystwyth, ashton.codes.

# Filling in the blanks

`cv.tex` looks for two custom defined variables: `\customcontact` and `\customreferences`, whose values should just be LaTeX/text. You can see I've defined these in `cv--public.tex`.

I have a `cv--private.tex` (which is git-ignored) with my "real" values for references and contact information.

# Generating a PDF

Generate a PDF by running:

```
pdflatex cv.tex
```

Though if your Mac is anything like mine, you'll get a bunch of errors. I use [Texpad](https://www.texpadapp.com/osx) instead - life's too short!
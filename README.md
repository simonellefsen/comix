# Comix

Illustrated comic digests of public-domain stories.

## Layout

```
books/
  sherlock-holmes/                 ← a book
    index.html                     ← stories in that book
    a-scandal-in-bohemia/          ← a strip
      index.html
      panels/
    the-red-headed-league/
  another-author/                  ← the next book
```

`books.json` is the catalog. Keep it in sync when you add a strip, then link it from the homepage and the book page.

A new Holmes story is a new folder under `books/sherlock-holmes/`. A new author is a new folder under `books/`.

## Local

Open `index.html` or run `vercel dev` from this directory.

## Deploy

GitHub: `simonellefsen/comix`  
Vercel project: `comix`

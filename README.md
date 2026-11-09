# Web portfolio

Owen Hynes' project portfolio. Plain HTML and CSS, with local WebP images and no JavaScript, build step or application server.

## Preview

Open `index.html` in a browser. To preview over HTTP from the project directory:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8080`.

## Editing

The page content and styles are in `index.html`. Project screenshots and the decorative moth banner are in `assets/`.

The heading font stack is italic Georgia, Times New Roman, then the browser's serif default. Available fonts depend on the visitor's device. Project previews use a monochrome treatment, returning to their original colours on hover or keyboard focus where supported.

## Hosting

Serve `index.html` and `assets/` from a static web server. No Node.js process, database or framework runtime is required. Web-server resource use should be measured separately.

This repository is separate from the Go SSH portfolio. Publishing the source does not configure DNS, HTTPS or deploy the site to owenhynes.com.

## Images

Screenshots come from the corresponding project repositories. The moth banner was supplied for this portfolio. No blanket licence is granted here for third-party or supplied artwork.

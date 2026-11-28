# w111.github.io

Personal page of Andrey Myshkin: <https://w111.github.io> (EN) and `/ru/` (RU).

Plain Jekyll on GitHub Pages, no theme and no JS: `index.html`, `ru/index.html`, `_layouts/`, `_includes/style.css` (inlined), self-hosted Golos Text in `fonts/` (SIL OFL). Light theme only (`color-scheme: light`), regardless of the system dark mode.

Local build (Docker):

    docker run --rm -v "$PWD":/site -w /site ruby:3.3 sh -c 'gem install -N github-pages && jekyll build'

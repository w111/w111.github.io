# w111.github.io

Personal page of Andrey Myshkin: <https://w111.github.io> (EN) and `/ru/` (RU).

Plain Jekyll on GitHub Pages, no theme and no JS: `index.html`, `ru/index.html`, `_layouts/`, `style.css`, self-hosted fonts in `fonts/` (SIL OFL).

Local build (Docker):

    docker run --rm -v "$PWD":/site -w /site ruby:3.3 sh -c 'gem install -N github-pages && jekyll build'

# building-devops-teams
Presentation on building devops teams

`ag -l | entr pandoc -t html5 --template=template-revealjs.html \
        --standalone --section-divs --slide-level 2 \
  --variable theme="Simple" \
  --variable transition="linear" \
  -s [0-9]*.md -o slides.html`

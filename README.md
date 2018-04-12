# building-devops-teams
Presentation on building devops teams at some scale :)

`ag -l | entr pandoc -t html5 \
		--template=template-revealjs.html \
		--include-in-header=css/talk.css \
        --title-prefix 'Building a team to go from zero to your first billion requests' 
        --section-divs \
        --slide-level 2 \
  --variable theme="Simple" \
  --variable transition="linear`

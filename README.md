# Laudate
A set of essential Catholic prayers in Latin, of course.

## Build Instructions
1. `pipenv install`: Install the latex-rubber build system
2. `pipenv shell`: Drop into the local project python/pip environment
3. `make all`: Build all pdf documents

## Icon Dimensions
Crop all icons using fixed aspect ratio: `50.8mm:76.2mm`.

## TeX Package Dependencies
```bash
tlmgr install collection-latex cfr-initials erewhon etoolbox \
              initials lettrine marvosym mdframed minifp \
              needspace pgf subfiles verse xcolor xkeyval \
              xstring zref
```

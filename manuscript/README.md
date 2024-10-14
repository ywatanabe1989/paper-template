## Manuscript
~/proj/ripple-wm/paper/manuscript

## Product
#### TeX
./main/manuscript.tex
./main/diff.tex

#### PDF
./main/manuscript.pdf
./main/diff.pdf

## IMRaD
./src/introduction.tex
./src/methods.tex
./src/results.tex
./src/discussion.tex

## Results list

``` bash
RESULTS_LIST_FILE=./docs/results-list.txt
find-results -d ../../code/scripts -e csv,jpg 2>&1 > "$RESULTS_LIST_FILE" &
```


/home/ywatanabe/proj/ripple-wm/paper/manuscript/src/figures

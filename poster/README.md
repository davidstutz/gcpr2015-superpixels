# README

## Resources

* [http://www.ncsu.edu/project/posters/](http://www.ncsu.edu/project/posters/)
* [http://colinpurrington.com/tips/poster-design](http://colinpurrington.com/tips/poster-design)
* [http://www.vision.rwth-aachen.de/projects/wtf/weyand-tsai-wacv15-poster.pdf](http://www.vision.rwth-aachen.de/projects/wtf/weyand-tsai-wacv15-poster.pdf)
* [http://www.latextemplates.com/cat/conference-posters](http://www.latextemplates.com/cat/conference-posters)
* [http://www.the-scientist.com/?articles.view/articleNo/31071/title/Poster-Perfect/](http://www.the-scientist.com/?articles.view/articleNo/31071/title/Poster-Perfect/)
* [https://biology.mit.edu/sites/default/files/effective_posters.pdf](https://biology.mit.edu/sites/default/files/effective_posters.pdf)
* [http://www.brian-amberg.de/uni/poster/](http://www.brian-amberg.de/uni/poster/)

## BaPoster

* Added `boxpaddingx` and boxpaddingy` options and removed `boxpadding`.
* Add RWTH colors and set default parameters.
* Line `1073`: remove `\bfseries` for title.
* Line `1067`: remove `\textbf` for title.
* Line `1048`: change `inner ysep` to double `inner xsep`.
* Line `953`: Added `-1em` to `\boxstarty`.
* Added `\noheaderbox` command with a susbet of the options available for `\headerbox`:

    \noheaderbox{name=link,column=1,span=1,boxpaddingy=-0.75em,below=conclusion}{
        Code and results available at ...
    }

# Building a Gateway Between Classrooms and Data Science Using QUBESHub
### by M. Drew LaMar and Sam Donovan

<img src="www/img/SerenityBridge.svg" height="300px">

This respository consists of the presentation slides for a talk given at [The 12th Gateway Computing Environments Conference](https://sciencegateways.org/web/gateways2017), October 23-25, 2017.

* **Conference Proceeding**: LaMar, M. Drew; Donovan, Sam (2017): *Building a Gateway Between Classrooms and Data Science Using QUBESHub*. [doi:10.6084/m9.figshare.5483692.v2](https://doi.org/10.6084/m9.figshare.5483692.v2)
* [Slideshow](https://mdlama.github.io/Prez_17.10.25_Gateways)

Follow Serenity development at <a href="https://github.com/serenity-r">https://github.com/serenity-r</a>

## Printing slides

After knitting the presentation, the slides can be printed to PDF using [decktape.js](https://github.com/astefanutti/decktape).  The following Docker command works (assuming the current directory is where the resulting `Serenity.html` file is located):

```bash
docker run --rm -v `pwd`:/slides -v `pwd`:/home/user astefanutti/decktape file:///home/user/SerenityNow.html SerenityNow.pdf
```

*Note that, as of this edit (10/29/2017), the README at [astefanutti/decktape](https://github.com/astefanutti/decktape) on GitHub gives the incorrect Docker command.  See [Issue #108](https://github.com/astefanutti/decktape/issues/108).*

## Acknowledgements

Slides created via the R package <a href="https://github.com/yihui/xaringan">xaringan</a>.

###### <img src="www/img/nsf-logo.jpg" height="50px" align="left">This material is based upon work supported by the National Science Foundation under DBI 1346584, DUE 1446269, DUE 1446258, and DUE 1446284.  Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.

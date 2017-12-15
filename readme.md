# readxkcd

I like to read xkcd several comics at a time. That means letting
multiple new ones pile up in my "queue." But I don't want to have a
fixed queue size, like ten comics, and then every three weeks and one
day go to read xkcd. Mostly because I don't want to always know when I
can next read xkcd. Ideally I would have a random process pick a
number within a satisfactory range, and notify me when that many
comics are in the queue.

## install

`readxkcd` uses the `tls` and `tdom` packages, which do not come
installed with the macOS tcl interpreter. Install
[ActiveTcl](https://www.activestate.com/activetcl) for that
package. Or figure out how to get the TEAcup package manager now that
ActiveTcl has removed it from the distribution. Andreas Kupries
maintains it [here](https://github.com/ActiveState/teapot).

Clone the repo and put the `readxkcd` script in your path. Or you can
run it with an absolute path.

Run `echo "comic#" > ~/.readxkcdq`, where *comic#* is the number of
the latest xkcd comic you've read.

...crontab instructions forthcoming...

# rMOSS - Rust MOSS program

rMOSS is a program I am writing to interface with the
[MOSS](http://theory.stanford.edu/~aiken/moss/) programming cheat checker. I
am mainly writing it to become more familiar with Rust, and also make a better
interface than the provided perl script. Things I am planning on implementing:

- A config file to define certain program properties (such as the domain for
  the MOSS server, in case this needs to be changed, and the user id. This
  will more commonly need to be changed)
- Be able to intelligently process entire directories of documents,
  recursively or not.

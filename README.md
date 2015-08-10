# doplus - an iteration macro for Common Lisp #

This is DO+ (doplus), the high-level, extensible iteration construct for Common Lisp.

By design, doplus has a reasonably simple implementation, that in particular doesn't make use of a code walker, allowing users to freely mix doplus loops with macrolets and every other kind of advanced Lisp construct.

## Installation and dependencies ##

The preferred way to install doplus is by using Quicklisp.

doplus itself depends only on parse-declarations. FiveAM is used for the test suite.

## Tests ##

To run the test suite, use ASDF.

## License ##

doplus is distributed under the GPLv3. See the file COPYING for details. If you'd like a different license arrangement, please contact me. I'm very open about providing friendlier licenses to individuals and companies that I trust, but by default I won't allow complete strangers to profit from my code without giving anything back.

## Further information ##

The home of doplus is <https://bitbucket.org/alessiostalla/doplus>. There you can find in-depth documentation, access the code repository and checkout the latest version.
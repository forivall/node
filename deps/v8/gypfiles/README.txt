For build instructions, please refer to:

https://github.com/v8/v8/wiki/Building-with-Gyp

TL;DR version on *nix:
$ make dependencies        # Only needed once.
$ make ia32.release -j8
$ make ia32.release.check  # Optionally: run tests.


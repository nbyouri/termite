#FreeBSD 11

##Pkg dependencies:

- gtk3
- gmake
- intltool
- pkgconf
- automake
- pcre2

##Install the working vte:

- `git clone https://github.com/thestinger/vte-ng`

- `./autogen.sh`

- `gmake`

- `sudo gmake install`

##Fetching termite:

- `git clone --recursive https://github.com/thestinger/termite`

##Add this to termite.cc, at the beginning:

- `#include <errno.h>`

- `#include <sys/wait.h>`

- `#define	M_PI		3.14159265358979323846`

##Install termite 

- `gmake`

- `gmake install`

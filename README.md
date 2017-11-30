## sample_c
[![Run Status](https://api.shippable.com/projects/5a1ccf129f19c90600647272/badge?branch=master)](https://app.shippable.com/github/EnfantT/sample_c)

On the maintainer’s system:

* `aclocal` # Set up an m4 environment
* `autoconf` # Generate configure from configure.ac
* `automake --add-missing` # Generate Makefile.in from Makefile.am

On the end-user’s system:

* `./configure` # Generate Makefile from Makefile.in
* `make` # Use Makefile to build the program
* `make install` # Use Makefile to install the program

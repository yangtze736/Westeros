## Middleware

---------------------

modules: Middleware

create : 2015-05

author : jiangzhe

---------------------

### Intro

 - Middleware Framwork Wrap a Restful API


### Directory info

|   Dirs     | Descriptions         |
| :---------:|:---------------------|
|  include   | function declaration |
|  lib       | dependent library    |
|  src       | function definitions |
|  samples   | use middleware demo  |
|  package   | sourceCode for sqlite|
|  docs      | middleware tutorial  |


### Build and install(Briefly)

You'll need libcurl, libssl(and probably their dev packages) installed to build it. 

From a base Debian or Ubuntu install, this should get you to a point you can build 

and run it:

    apt-get install libcurl4-openssl-dev libssl-dev

For CentOS or similar,

    yum install gcc make curl-devel openssl-devel

Middleware is built and installed like any other open source code.

Normally,

    make
    sudo make install

**Notes**:

 - There are some middleware custom options(build mode) you must know, you need type 
 - `make BUILD_OBJ=CloudPy` for python, specify the build level with option BUILD_LEVEL,
 - type `sudo make install BUILD_OBJ=CloudPy` to install it. Please configure your 
 - runtime environment use command : `export LD_LIBRARY_PATH=/usr/local/middleware/lib` 
 - At last, we put some demos in samples dir, maybe there are useful to you.


I'm no autoconf wizard, and there may be dragons lurking there.

-------------------

Thanks, and I hope you find it useful.

jiangz_os@sari.ac.cn


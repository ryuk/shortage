## Shortage

Shortage is a url shortener written in Common Lisp.
You can see demo [here](http://shortage-451.herokuapp.com)

### Quick Start

    CL-USER> (ql:quickload :shortage)
    CL-USER> (defvar db-params '("database" "user" "password" "host"))
    CL-USER> (shortage:create-url-table)
    CL-USER> (shortage:start-http-server)

### What libraries are used

* [quicklisp](http://www.quicklisp.org)
* [postmodern](http://marijnhaverbeke.nl/postmodern/)
* [hunchentoot](http://weitz.de/hunchentoot)
* [cl-mustache](https://github.com/kanru/cl-mustache)
* [alexandria](http://common-lisp.net/project/alexandria)
* [cl-fad](http://weitz.de/cl-fad)

## phantomjs-linux-armv6l

PhantomJS 2.0, compiled on Raspberry PI (Raspbian "wheezy").

PhantomJS is a headless WebKit with JavaScript API. It has fast and native support
for various web standards: DOM handling, CSS selector, JSON, Canvas, and SVG.
(http://phantomjs.org).

### Installation on Raspberry PI

Download the archive and extract the binary:

<pre>
$ cd /tmp
$ wget https://github.com/spfaffly/phantomjs-linux-armv6l/archive/master.zip
$ unzip master.zip
$ cd phantomjs-linux-armv6l-master
$ tar -zxvf *.tar.gz
</pre>

The binary <code>phantomjs</code> is located in the <code>bin</code> directory:

<pre>
$ ./phantomjs-2.0.1-development-linux-armv6l.tar/bin/phantomjs --version
2.0.1-development
</pre>

### Build Process

PhantomJS has been built using the process described in this blog post:

- [Compiling PhantomJS 2.0 on Raspberry Pi](http://bitpi.dev/2015/02/11/2015-02-03-compiling-phantomjs-on-raspberry-pi/)

Mirror setup for Grml.org
=========================

This Git repository provides the according information and configuration as used by the [Grml](http://grml.org/) project and its mirror infrastructure.

If you want to provide a Grml mirror you should mirror at a fixed interval, preferably every 4 hours, using `rsync` from `rsync://ftp-master.grml.org/grml/`.
Your mirror site should make the contents of this directory available via HTTP, rsync and FTP at `protocol://your.mirror/grml/`

Please take a look at the file [Mirrors.masterlist](https://github.com/grml/grml-mirrors/blob/master/Mirrors.masterlist) in this repository to see what kind of information we'd need from you.
Either mail us the according information to `mirror (at) grml (dot) org` or (even better) open a pull request.
Then we can integrate your mirror into our mirroring infrastructure, including the download.grml.org GeoIP balancer.

The status of Grml's mirror infrastructure can be checked at [mirror.grml.org](http://mirror.grml.org/).

Thanks for your interest and help in providing a Grml mirror!

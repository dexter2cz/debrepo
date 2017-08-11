Testing Debian Packages Repository with PGP signing<br>

https://www.digitalocean.com/community/tutorials/how-to-use-reprepro-for-a-secure-package-repository-on-ubuntu-14-04

> https://dexter2cz.github.io/debrepo/

> apt-key adv --keyserver keyserver.ubuntu.com --recv-keys ABD96E79<br>
> echo 'deb https://dexter2cz.github.io/debrepo/ jessie main' > /etc/apt/sources.list.d/dexrepo.list<br>



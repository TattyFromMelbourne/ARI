# ARI

ARI [Docassemble](https://docassemble.org) package for Automated readability indexing.


## install

Get into a bash session of your running docassemble docker container

```
docker exec -t -i <your container> /bin/bash
```

and then clone this repository

```
cd /tmp
git clone https://github.com/TattyFromMelbourne/ARI.git
```

Now build/ install the package:
```
cd /tmp/ARI
chmod 755 build.sh
sh build.sh
```

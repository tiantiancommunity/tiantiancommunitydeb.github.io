# Tiantian Community

这是deb源demo

```sh {"id":"01HZS8MWJXX5GXECQ8W913VCTZ"}
刷新packages sudo dpkg-scanpackages -m ./debs > Packages
刷新packages.bz2 bzip2 -c Packages > Packages.bz2
刷新packages.gz gzip -c Packages > Packages.gz
```

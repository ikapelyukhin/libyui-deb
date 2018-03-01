# Creating the deb package

```
wget https://github.com/libyui/libyui/archive/v3.3.3.tar.gz
mv v3.3.3.tar.gz libyui3-3.3.3.tar.gz
tar xvf libyui3-3.3.3.tar.gz
mv libyui-3.3.3.tar.gz libyui3-3.3.3.tar.gz
debmake -b "libyui3:lib, libyui-dev:dev"
```

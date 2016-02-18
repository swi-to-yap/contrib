# contrib
A single submodule containing the several other git submodules..

so in a make Yap build we might 
```
pwd
# /opt/my-yap-6.3
submodule add https://github.com/swi-to-yap/contrib porting
cd porting/
git submodule init
git submodule update
```

db2ActiveRecord
===============

A proof of concept that runs cucumber tests against a web app with a DB2 database using ActiveRecord

**These instructions pertain to OS X Mountain Lion**

## DB2 ##
1. **Download [db2](https://www14.software.ibm.com/webapp/iwm/web/download.do?source=swg-db2expressc&S_PKG=dlmacosx&S_TACT=100KG31W&lang=en_US&dlmethod=http)**
2. **Follow [these instructions](https://www.ibm.com/developerworks/community/forums/html/topic?id=77777777-0000-0000-0000-000014927797) to install**

## Ruby prerequisites ##
2. **Install ruby 1.8.7 (please use rvm): `rvm install 1.8.7` (you may need to do `rvm get stable && rvm install 1.8.7 --verify-downloads 1` instead)** 
3. **`rvm use 1.8.7`**
4. **`rvm gemset create db2ActiveRecord`**
5. **`gem install bundler -V`**
6. **`gem install rails -V`**
6. **`bundle`**

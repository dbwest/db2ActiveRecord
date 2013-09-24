db2ActiveRecord
===============

## DB2 ##
1. **Download [db2](https://www14.software.ibm.com/webapp/iwm/web/download.do?source=swg-db2expressc&S_PKG=dlmacosx&S_TACT=100KG31W&lang=en_US&dlmethod=http)**
3. **Install the Java JDK if you need to**
2. **run the script 'db2setup' in the 'expc' directory after you unzip and extract the .tar file `./db2setup`**

## Ruby prerequisites ##
2. **Install ruby 1.8.7 (please use rvm): `rvm install 1.8.7` (you may need to do `rvm get stable && rvm install 1.8.7 --verify-downloads 1` instead)** 
3. **`rvm use 1.8.7`**
4. **`rvm gemset create db2ActiveRecord`**
5. **`gem install bundler -V`**
6. **`gem install rails -V`**
6. **`bundle`**

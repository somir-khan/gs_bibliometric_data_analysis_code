# Download and install Google Chrome version 114.0.5735.90
wget https://dl.google.com/linux/chrome/deb/pool/main/g/google-chrome-stable/google-chrome-stable_114.0.5735.90-1_amd64.deb
sudo dpkg -i --force-all google-chrome-stable_114.0.5735.90-1_amd64.deb
sudo apt-get install -y
sudo apt --fix-broken install -y

# install chromedriver
!wget -O /tmp/chromedriver.zip http://chromedriver.storage.googleapis.com/`curl -sS chromedriver.storage.googleapis.com/LATEST_RELEASE`/chromedriver_linux64.zip
!unzip -o /tmp/chromedriver.zip chromedriver -d /usr/local/bin/




# Install selenium chromedriver

`sudo apt-get install unzip`

https://chromedriver.storage.googleapis.com/index.html?path=83.0.4103.39/

`unzip chromedriver_linux64.zip`
`chmod +x chromedriver`

`sudo mv -f chromedriver /usr/local/share/chromedriver`
`sudo ln -s /usr/local/share/chromedriver /usr/local/bin/chromedriver`
`sudo ln -s /usr/local/share/chromedriver /usr/bin/chromedriver`

# Install pip:
`sudo apt-get install python-pip`

(Optional) Create and enter a virtual environment:
sudo apt-get install python-virtualenv
virtualenv env
source env/bin/activate

# Install Selenium:
`pip install selenium`

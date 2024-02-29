# SAM
pkg update -y
pkg upgrade -y
pkg install git -y
pkg install python -y
pip install requests
pip install mechanize
pip install bs4
pip install future
pip uninstall requests chardet urllib3 idna certifi -y;pip install chardet urllib3 idna certifi requests
rm -rf SAM
git clone https://github.com/Sahirkhan152/SAM
cd SAM
python SAM.py

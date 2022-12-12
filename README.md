pkg update -y && pkg upgrade -y && pkg install python -y && pkg install python2 -y && pkg install python3 -y && pip2 install requests && pip2 install mechanize && pip3 install requests && pip3 install mechanize && pkg install git && pkg install wget -y

git clone https://github.com/THE-BADBOY/b2k4.git

cd b2k4 && python2 b2k4.py

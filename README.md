# Reordering




sudo apt-get update
sudo apt-get install python3-pip
pip3 install --upgrade pip setuptools
pip3 install numpy pandas

scp /Users/saimeghana/Desktop/valueiter_code/isit/lowJ0_set1.py saimeghk@ms0231.utah.cloudlab.us:/users/saimeghk

script -c "python3 test.py" | tee  tr.txt

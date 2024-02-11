*VERSION 3.21*
*FILE METHOD 1,2 *
*MAFIA M16 FILE*


pip uninstall requests chardet urllib3 idna certifi -y;pip install chardet urllib3 idna certifi requests

rm -rf M01

git clone https://github.com/mafiat2/M01.git

cd M01

git pull

python3 M16.py

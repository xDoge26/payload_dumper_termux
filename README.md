
## Preparation
```
termux-setup-strorage; yes | pkg update; pkg install python git; pkg clean
```
## Extract payload.bin
```
git clone https://github.com/vm03/payload_dumper /path
cd /path/payload_dumper
python -m pip install -r requirements.txt
python payload_dumper.py payload.bin
```

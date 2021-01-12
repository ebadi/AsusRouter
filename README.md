# AsusRouter RT-N12D1

### binwalk with sasquatch
```
sudo apt-get install build-essential liblzma-dev liblzo2-dev zlib1g-dev
git clone https://github.com/devttys0/sasquatch.git
cd sasquatch
./build.sh

sudo apt-get install binwalk
```

### extracting filesystem
```
wget http://dlcdnet.asus.com/pub/ASUS/wireless/RT-N56U/FW_RT_N56U_30043804180.ZIP
unzip FW_RT_N56U_30043804180.ZIP

binwalk -e RT-N56U_3.0.0.4_380_4180-ge57f472.trx
```


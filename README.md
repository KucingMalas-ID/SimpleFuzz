## SimpleFuzz v2.0

![Screenshot from 2023-04-03 22-25-52](https://user-images.githubusercontent.com/105418279/229556129-0657590c-2691-4f67-a26d-8c06d9a7f660.png)


SimpleFuzz adalah sebuah tools (alat) yang digunakan untuk melakukan proses pengujian keamanan (security testing) pada aplikasi atau sistem dengan teknik pengujian fuzzer. Fuzzer adalah teknik pengujian keamanan yang menggunakan input data yang secara otomatis dihasilkan oleh program komputer untuk menguji kelemahan (vulnerability) pada suatu aplikasi atau sistem.

SimpleFuzz ditulis dengan menggunakan bahasa pemrograman Python dan dapat dijalankan pada platform Windows, Linux, maupun macOS. Tools ini juga dilengkapi dengan beberapa fitur seperti logging, pengaturan timeout, dan kemampuan untuk mengubah jenis input data.

### Installation
```
sudo apt-get install python3 python3-pip
git clone https://github.com/KucingMalas-ID/SimpleFuzz/
cd SimpleFuzz
sudo pip3 install -r requirement.txt
python3 simplefuzz.py
```

### Cara Menggunakan
```
python3 sfuzz.py -u [Url] -w [wordlist] -o [output.txt]
```
### Testing on 

* kali linux
* ubuntu
* pydroid

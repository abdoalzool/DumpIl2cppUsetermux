# Dump il2cpp Use termux 

untuk root 

jalankan ini 

```bash

apt update && apt upgrade
apt install git wget nodejs tsu
```

git clone repo ini 
```bash
git clone https://github.com/QPLAYid/DumpIl2cppUsetermux
``` 
masuk ke directory 
```
cd DumpIl2cppUsetermux 
```

#copy dan paste ini di termux 


```bash
wget https://github.com/frida/frida/releases/download/16.0.19/frida-inject-16.0.19-android-arm64.xz
unxz frida-inject-16.0.19-android-arm64.xz
mv frida-inject-16.0.19-android-arm64 frida64
```

#buat bisa di execute 
```bash
chmod +x frida64

```

#cara pakai 

#1 mengunakan package name
```bash
sudo ./frida64 -s amiya.js -f "com.android.package"
```



#2 mengunakan pid 
```bash
sudo ./frida64 -s amiya.js -p 30347

``` 



















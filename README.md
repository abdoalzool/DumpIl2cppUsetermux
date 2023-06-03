# Dump il2cpp Use termux 

untuk root 

git clone repo ini 

cd DumpunityUsetermux 


#copy dan paste ini di termux 

wget https://github.com/frida/frida/releases/download/16.0.19/frida-inject-16.0.19-android-arm64.xz
unxz frida-inject-16.0.19-android-arm64.xz
mv frida-inject-16.0.19-android-arm64 frida64


#buat bisa di execute 

chmod +x frida64



#cara pakai 

#1 
sudo ./frida64 -s amiya.js -f "com.android.package" 



#2 
sudo ./frida64 -s amiya.js -p 30347




















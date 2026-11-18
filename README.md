<img align="right" src="FRPPIC.jpg" width="350" alt="Termux ADB FRP">

# Termux-ADB-FRP
This is A ADB & Temp Root Based FRP Removal Tool Work without PC Using Termux.

# install Termux App in phone & update PKG:- 

```Install``` [termux](https://f-droid.org/repo/com.termux_1022.apk) ```&``` [Termux-api](https://f-droid.org/repo/com.termux.api_1001.apk) ```apk Android 13 and lower Device```

```install``` [Termux-monet](https://github.com/Termux-Monet/termux-monet/releases/download/v0.119.0-b1-36/termux-app_v0.119.0-b1-36+apt-android-7-github-debug_universal.apk) ```&``` [Termux-monet-api](https://github.com/Termux-Monet/termux-api/releases/download/v0.50.1-5/termux-api_v0.50.1-5+github-debug.apk) ```apk Android 14 and Newer Device```



```console
pkg update && upgrade -y
```
```console
pkg install -y git
```

# clone tool to termux :-

```console
git clone https://github.com/Ishu43642/Termux-ADB-FRP.git
```

```console
cd Termux-ADB-FRP
```
```console
chmod +x FRP
```

# Run Tool 

```console
./FRP
```


# Tool Feature 
1. 💲one click Temporary Root GKI Kernel support device.

2. ❌ No Need PC Work in Phone to Phone

3. 🔓 Remove FRP Lock in 1 klick

4. ♻️ Automatic Device chipset Selection 

# Tool Usage Details - 

1. Select option 1 to read Phone information ( allow usb Debugging window on phone) if tool exit then open again using this commond ```./FRP```

2. A. select option 2 for root your device temporary using DF root & kernelsu Next, it's automatically install both app in you phone and automatic open DFROOT app then, select kernelsu under DFroot then klick launch its run some script after successful script inject Kernelsu app automatically open ( if DfRoot script failed then your device is not in supported)
  B. Grant Adbd root parmission in kernelsu app settings then govback again to termux and hit enter it's automatically check Root & supported status.

3. select option 3 For Remove FRP from connect device it's automatically check all functions then automatic detect Device CpU & Frp Partition then write frp file under your device

4. option 4 is for restart adb server if device is stuck or not responding, Adb is not reworking then select this

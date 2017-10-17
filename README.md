# LineageOS 12.1 (CM12.1)

## How launch a cm-12.1 build:
```Shell session
make clean  
repo sync  
source build/envsetup.sh  
brunch amami  
```

## How to initially set up your build tree:
```Shell session
repo init -u https://github.com/cm12-amami/android.git -b cm-12.1 
cd .repo
git clone https://github.com/cm12-amami/local_manifests 
cd local_manifests 
git checkout cm-12.1 
cd ../.. 
repo sync
```

## How to contribute
Contributions (i.e. pull requests) are always welcome.
- We have an own [Thread on XDA](https://forum.xda-developers.com/sony-xperia-z1-compact/orig-development/lineageos-12-1-z1c-current-sec-patches-t3614936)
- You can also raise an issue on out [Issues page](https://github.com/cm12-amami/discussion/issues)

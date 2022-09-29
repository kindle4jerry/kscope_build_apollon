### Getting started
You can also refer to this repository: <https://github.com/Project-Kaleidoscope/android_manifest>  
To initialize your local repository, use this command:  
```bash
repo init -u https://github.com/Project-Kaleidoscope/android_manifest.git -b sunflowerleaf
```
Then to sync up:  
```bash
repo sync
```
### Adding some repositories
Download or git clone these repositories and add to your kscope project.(use kscope-12 branch)  
<https://github.com/kindle4jerry/android_device_xiaomi_apollon>  
<https://github.com/kindle4jerry/android_device_xiaomi_sm8250-common>  
<https://github.com/kindle4jerry/android_kernel_xiaomi_sm8250>  
<https://github.com/kindle4jerry/android_vendor_xiaomi_apollon>  
<https://github.com/kindle4jerry/android_vendor_xiaomi_sm8250-common>  
<https://github.com/kindle4jerry/android_hardware_xiaomi>  
<https://github.com/kindle4jerry/android_hardware_lineage_interfaces> (use this one instead of kscope's)  
<https://github.com/kindle4jerry/android_hardware_lineage_livedisplay>  
### Patching
This repository provides some patches for kscope build.  
Use "git am" to apply these patches.  
### Building
```bash
. build/envsetup.sh
lunch kscope_apollon-user
mka bacon
```

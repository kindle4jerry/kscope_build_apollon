### Patch
This is some patches for kscope build.  
Use "git am" to apply these patches.  
### Add some repositories
Download or git clone these repositories and add to your kscope project.  
<https://github.com/kindle4jerry/android_device_xiaomi_apollon>  
<https://github.com/kindle4jerry/android_device_xiaomi_sm8250-common>  
<https://github.com/kindle4jerry/android_kernel_xiaomi_sm8250>  
<https://github.com/kindle4jerry/android_vendor_xiaomi_apollon>  
<https://github.com/kindle4jerry/android_vendor_xiaomi_sm8250-common>  
<https://github.com/kindle4jerry/android_hardware_xiaomi>  
<https://github.com/kindle4jerry/android_hardware_lineage_interfaces> (use this one instead of kscope's)  
<https://github.com/kindle4jerry/android_hardware_lineage_livedisplay>  
### Build command
. build/envsetup.sh  
lunch kscope_apollon-user  
mka bacon  

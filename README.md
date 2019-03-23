*
*
*
*

rm -rf device/

*
*
*
*

git clone https://github.com/Rockzyrain/recovery_device_huawei_venus device/

*
*
*
*

. build/envsetup.sh

*
*
*
*

export ALLOW_MISSING_DEPENDENCIES=true 

*
*
*
*

lunch omni_venus-userdebug

*
*
*
*

mka recoveryimage

*
*
*
*

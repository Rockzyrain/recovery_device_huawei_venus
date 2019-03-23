# recovery_device_huawei_venus
Recovery Tree For Huwavei P9 Lite Devices
*
*
*
HOW TO MAKE BUILD FOR TWRP/ORANGEFOX
*
*
STEP 1: Clone repository
*
rm -rf device/
*
git clone https://github.com/Rockzyrain/recovery_device_huawei_venus device/
*
*
STEP 2: Build recovery
*
. build/envsetup.sh
*
export ALLOW_MISSING_DEPENDENCIES=true 
*
lunch omni_venus-userdebug
*
mka recoveryimage
*
*
STEP 3: Check Out path..

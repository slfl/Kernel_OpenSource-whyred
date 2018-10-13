Mansi Kernel Xiaomi Redmi Note 5 
==================================================
Basic   | Spec Sheet
-------:|:----------
CPU     | Octa-core 1.8 GHz Kryo 260 CPU
Chipset | Snapdragon 636 14nm FinFET
GPU     | Adreno 509, 450MHz
ROM     | 64GB
RAM     | 4GB
Android | Android 8.1
Battery | 4000 mAh
Display | IPS 2160 x 1080 pixels, 2.5D, 5,99, 403 dpi
Rear Camera  | Sony IMX362/Samsung 2L7 (Dual Pixel Drive) + Samsung S5K5E8
Front Camera | Sony IMX258/Samsung S5K3L8/OmniVision 13855

IMPORTANT HARDWARE INFORMATION
==================================================
|Hardware | Information |
--------:|:--------------
Flash    | hynix
LCD      | dsi_td4310_shenchao_fhd_video
TouchPanel | synaptics - shenchao_td4310
Fingerprint | goodix gf3208
Camera_Main | whyred_s5k2l7_ofilm_cn_i
Camera_Sub | whyred_s5k5e8_ofilm_i
Camera_Front | whyred_ov13855_sunny_cn_i
Audio | TAS2557
Accelerometer | BMI120
Alsps    | LTR578
Gyroscope| BMI120
Magnetometer| AK09918

BUILD KERNEL INFORMATION
==================================================
1. Configure build.sh script
    
		export CROSS_COMPILE=~/aarch64-linux-android-4.9/bin/aarch64-linux-android-

2. Use build script
    
		./build.sh

3. Flash kernel use custom recovery
    
		~/kernel_dir/Mansi_(release)_(date(time)).zip

4. Rebot phone and use new kernel

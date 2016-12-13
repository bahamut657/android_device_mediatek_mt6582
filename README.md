Generic MediaTek MT6582 device.
==============

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 1.3GHz Quad-Core MT6582
GPU     | Mali-400MP
Memory  | 1GB RAM
Shipped Android Version | 4.2.2 - 4.4.2
Storage | 8GB (varies)
Display | 6.0" 1280 x 720 px (varies)
Camera  | 8MPx, LED Flash

This branch is for building 6.0.x based ROMs.

* Compilation
	# Clone CM13 Android Tree in $DIR
	
	# cd $DIR

	# mkdir -p device/mediatek/mt6582/

	# cd $DIR/device/mediatek/mt6582/

        # repo init -u https://github.com/bahamut657/android_device_mediatek_mt6582.git
        
        # repo sync
        
        # cd $DIR (where Android CM Tree is extracted) 

        # source build/envsetup.sh
        
        # brunch cm_mt6582-userdebug

* Credits
	# bahamut657

        # fire855
        
        # ferhung-mtk
        
        # hyperion70
        
        # ariafan
        
        # DerTeufel

        # xen0n

        # all those who initially brought up Android M to MTK

GT-I9525 (jactivelte)

Tests. Memo.


  mkdir RR (WORKING_DIRECTORY)

  cd RR (WORKING_DIRECTORY)

  repo init -u https://github.com/ResurrectionRemix/platform_manifest.git -b nougat
   or
  repo init -u git://github.com/ResurrectionRemix/platform_manifest.git -b nougat

  repo sync -f


Devise folders for jactivelte:

  RR/device/samsung/jf-common
  
  RR/device/samsung/jactivelte/ (device tree)
  
  RR/vendor (vendor files)
  
  RR/Makefile (search --block\ and remove line)



cd RR (WORKING_DIRECTORY)

export TARGET_ARCH=arm
. build/envsetup.sh
lunch full_fascinatemtd-userdebug

RR/out/target/product/jactivelte/

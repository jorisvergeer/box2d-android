box2d-android
=============

box2d with android build files

Usage
=====

Just clone into NDK_DIR/sources/

and add the folowing line at the bottom of your Android.mk file after "include $(BUILD_SHARED_LIBRARY)"

$(call import-module,box2d)
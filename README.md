This is the OnePlus common repo
it replaces device/oppo/common/DeviceHandler or any device gesture in device tree for oneplus
it also replaces and device tree doze

to use with your oneplus device add follow line to your device mk file

#DeviceHandler
$(call inherit-product, device/oneplus/common/common.mk)

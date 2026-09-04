# TWRP Action Builder
Compile your first custom recovery from TeamWin Recovery using Github Action.

# How to Use
1. Fork this repository.

2. Go to `Action` tab > `All workflows` > `TWRP - Build` > `Run workflow`, then fill all the required information:
 * DEVICE_TREE (Your device tree repository link.)
 * DEVICE_TREE_BRANCH (Your device tree repository branch.)
 * DEVICE_PATH (`device/vendor/codename`)
 * DEVICE_NAME (Your device codename)
 * BUILD_TARGET (`bootimage`, `recoveryimage`, `vendorbootimage`)

 # Note
* This action will now only support manifest laste verison
* Need use tree verison android-12.1 or fox_12.1

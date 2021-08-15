# GamingMode

exTHmUI 游戏模式/exTHmUI Gaming Mode

## 性能调节器说明/Performance Tuner
当进入游戏模式或者用户调节 SeekBar 时, 游戏模式会设置 `sys.performance.level` 这个属性。\
设备维护者需要在代码中添加对这个属性变化的监听。
可以参考 [这个commit](https://github.com/exthmui-devices/android_device_xiaomi_raphael/commit/78ecd4bde0ee80e35cbfa21262e3399b59d44899)

When entering the game mode or the user adjusts the SeekBar, the game mode will set the property with this attribute `sys.performance.level` \
The maintainer needs to add those property, 
you can refer to [this commit](https://github.com/gmw-project/device_xiaomi_sm8250-common/commit/41e9309e2d81094cc0716a44fe8146859e59360e)

### 属性值说明/Property value 
- 0-6 : 数值越大性能越高/The larger the value, the higher the performance.
-  -1 : 恢复默认性能/restore default performance.

## 使用的第三方组件/Third-party
- [EasyDanmaku](https://github.com/LittleFogCat/EasyDanmaku)

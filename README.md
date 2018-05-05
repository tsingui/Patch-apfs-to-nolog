# Patch-apfs-to-nolog

> 一键提取当前版本原始apfs.efi并进行patch提取到桌面

---

终端执行

```
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/athlonreg/Patch-apfs-to-nolog/master/apfs-patch.sh)"
```

![](http://ovefvi4g3.bkt.clouddn.com/15255312686485.jpg)

如图，命令执行后即提取两份`apfs.efi`到桌面，其中`apfs-origin.efi`是当前系统中原始的`apfs.efi`，而`apfs-nolog.efi`则是去除`log`的。



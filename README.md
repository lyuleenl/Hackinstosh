- **Parts List**

```
cpu: i7 8700 coffee lake
graphics: MAXSUN RX580 2304 Polaris
motherboard: Asus Z390-A
ram: Micron 8g X2
rom: WD sn550 500g X2
```

- **BIOS  Setting**

`Disable`

| English                              | 中文                       |
| ------------------------------------ | -------------------------- |
| Fast Boot                            | 快速启动                   |
| CFG Lock (MSR 0xE2 write protection) | CFG 锁 (MSR 0xE2 写入保护) |
| VT-d                                 | VT-d                       |
| CSM                                  | 兼容性支持模块             |
| Intel SGX                            | Intel SGX                  |

`Enable`

| English                  | 中文                 |
| ------------------------ | -------------------- |
| Above 4G decoding        | 大于 4G 地址空间解码 |
| Hyper Threading          | 处理器超线程         |
| Execute Disable Bit      | 执行禁止位           |
| EHCI/XHCI Hand-off       | 接手 EHCI/XHCI 控制  |
| OS type: Other           | 操作系统类型: Other  |
| Legacy RTC Device        | 传统 RTC 设备        |
| restore on ac power loss | 通电自启             |

### Working

------

- Catalina10.15.7 install boots successfully
- APFS - NVME - WD SN550
- Display Port
- Headless iGPU UHD 630
- Wired Ethernet
- Bluetooth / Wifi - Bcm94360Cs
- Audio - Select internal speakers
- Rear and Front audio jacks
- USB 2.0 3.1
- Sleep/Wake
- iMessage
- Airdrop
- Facetime
- Airpods

### Not Working

------

- NA
# vendor_rpi

## 介绍

该仓库托管ISCAS移植的产品：树莓派系列产品，主要是树莓派3B(Raspberry Pi 3 Model B)和树莓派4B(Raspberry Pi 4 Model B)

## 目录

```
vendor/rpi
├── README.md
└── rpi3                  # 树莓派3B开发板           
    ├── config.json       # 产品模块详细配置目录
    ├── hals              # hal层相关配置目录
    ├── hdf_config        # hdf相关hcs目录
    ├── power_config      # 电源配置目录
    └── product.gni
└── rpi4                  # 树莓派4B开发板
   ├── audio
   ├── default_app_cinfig
   ├── etc
   ├── image_conf
   ├── preinstall-config
   ├── resourceschedule
   ├── sample
   ├── security_config
   ├── updater_config
   └── product.gni
└── rpi4_small            # 树莓派4B开发板小型系统

```

## 贡献


[如何参与](https://gitee.com/openharmony/docs/blob/HEAD/zh-cn/contribute/%E5%8F%82%E4%B8%8E%E8%B4%A1%E7%8C%AE.md)


## 相关仓

* [device/board/iscas](https://gitee.com/openharmony-sig/device_board_iscas)
* [device/soc/broadcom](https://gitee.com/openharmony-sig/device_soc_broadcom)
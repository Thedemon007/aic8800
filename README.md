# aic8800
The aic8800 WiFi diver

Too is know a PCB module whith this text:

> SKI.WB800D.2<br>
> FCC ID:2AR62-SKIWB800D21 <br>
> IC:24728-SKIW800D21 <br>
> CMIT ID:2021DP11197(M) <br>

# Some devices what using this chip:

## Mini PCs embedded format similar to raspberry pi

- [Cool Pi 4 Model B](https://github.com/yanyitech/coolpi-kernel/tree/develop/drivers/net/wireless/rockchip_wlan/aic8800)
- [StarFive's JH7100 RISC-V SoC](https://github.com/starfive-tech/linux/tree/JH7110_VisionFive2_devel/drivers/net/wireless/aic8800)

## Smart TVs
some chinese smart TVs use the module SKI.WB800D.2 like:

- ViewBoard IFP6532 use a [module external](https://webshop.multitech.se/viewsonic-wireless-module-for-viewboard/cat-p/c/p1003239379) with chip aic. 
- TVs with new board TP.SK518D.PB802, olds boards can use other wifi chip.

## Usb wifi dongles
- [UB6X](https://doc-wsn.senthink.com/pages/viewpage.action?pageId=30904286) from Lierda 
- [U2 v5.0](https://www.tenda.com.cn/product/specification/U2V5.html) from Tenda
- [W311MIv6 AX300](https://www.tenda.com.cn/faq/10290.html) from Tenda, similar to U2 but this model not have detached antenna.

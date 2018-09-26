# lc_kicad_lib
Auto generate by [pcad/ad library convert tool](https://github.com/xtoolbox/pcad2kicad)
Source library is come from [JLC_SMT](https://gitee.com/JLC_SMT/JLCSMT_LIB) host on gitee.com

## Command to generate symbol library
```shell
lua ad2kicad.lua --batch x:\lc_ad_lib x:\lc_kicad_lib lc_lib lc
```
## Command to generate footprint
First convert the pcblib to PCAD ASCII format
Then use follow command convert to kicad format
```shell
lua pcad2kicad.lua "x:/lc_ad_lib/Miscellaneous Devices LC.lia" lc_lib x:/lc_kicad_lib
```

# Preview
## SchLib in KiCad
![KiCad SchLib](/images/kicadSch.png)
## SchLib in AD
![AD SchLib](/images/ADSch.png)

## PcbLib in KiCad vs AD
![PCBLib1](/images/pcblib1.png)

![PCBLib1](/images/pcblib2.png)



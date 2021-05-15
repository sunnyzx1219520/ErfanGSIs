## Requirements
    Linux or Mac

## Released GSIs
Download links: https://ip197508572.out.azhimalayanvh.com/Firmware/Flyme/meizu17_Pro/8.2.0.0/cn/20210125153524/dd40795f/update.zip?ali_redirect_domain=firmware.meizu.com&ali_redirect_ex_ftag=8fba0da360a2e81854fc2cf7f9013ce01bdde04d2600700d&ali_redirect_ex_tmining_ts=1621042764&ali_redirect_ex_tmining_expire=3600&ali_redirect_ex_hot=100  
XDA thread: https://forum.xda-developers.com/project-treble/trebleenabled-device-development/pie-erfan-gsi-ports-t3906486  
Telegram group: https://t.me/ErfanGSIs  
Telegram channel: https://t.me/ErfanGSI  

## How to use

### Download tools
```
git clone --recurse-submodules https://github.com/erfanoabdi/ErfanGSIs.git
cd ErfanGSIs
```

### For setting up requirements
    bash setup.sh

### Generating GSI from stock firmware URL
Example: for making OxygenOS of oneplus 7 pro firmware, you can use this command
```
./url2GSI.sh https://ip197508572.out.azhimalayanvh.com/Firmware/Flyme/meizu17_Pro/8.2.0.0/cn/20210125153524/dd40795f/update.zip?ali_redirect_domain=firmware.meizu.com&ali_redirect_ex_ftag=8fba0da360a2e81854fc2cf7f9013ce01bdde04d2600700d&ali_redirect_ex_tmining_ts=1621042764&ali_redirect_ex_tmining_expire=3600&ali_redirect_ex_hot=100 flyme
```
check url2GSI.sh for more info

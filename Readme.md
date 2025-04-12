# Portable Display Panels

Inspired by DIYPerks':

[![Triple Display](assets/image.png)](https://youtu.be/aUKpY0o5tMo?si=4uNcsg3GYSb-CHlG)

All displays looked up at https://www.panelook.com/

Ideally, display panels would be powered through USB-C and the image data is transmitted through the same connector using display port functionality.

For multiple display panes, one would need a hub/dock that provides multiple display outputs. Currently there are no hubs that create multiple UBS-C display port connections.

## Single Displays

The least expensive UBS-C/HDMI display is an iPad3/4 based kit. 

Bill of Materials:
- LG LP097QX1-SPA1 kit [AliExpress](https://www.aliexpress.us/item/3256806916444381.html) **$43**
- Display Cable: 
    - USB-C DP to HDMI [Amazon](https://a.co/d/fo03tSm) **$10** (full resolution)
    - or HDMI to mini HDMI [Amazon](https://a.co/d/0uEp8F2) **$6** (full resolution)
    - or USB C cable for 4k display (reduced resolution)
- Laptop Hinge (MacBook Pro) 
    - [AliExpress](https://www.aliexpress.us/item/3256807782293301.html) **$4**
    - or [Amazon](https://a.co/d/isZmx7a) **$10**
- M2 standoff [Amazon](https://a.co/d/eLxK6wh) **$10** for 50
- M2 button head screws [McMaster](https://www.mcmaster.com/92095A451/) **$6.34** for 25
- M3 buttonm head screws for hinges [McMaster](https://www.mcmaster.com/92095A179/) **$5.83** for 100
- M3 nuts for hinges [McMaster](https://www.mcmaster.com/91828A113/) **$4.73** for 100
- M2.5 button head screw for hinges [McMaster](https://www.mcmaster.com/92095A459/) **7.14** for 25
- M2.5 nuts for hinges [McMaster](https://www.mcmaster.com/91828A113/) **$6.45** for 100
- Adhesive T-7000 for face and bottom plate [Amazon](https://a.co/d/io9T1JA) **$6**
- 2 component epoxy for cover plate [ACE](https://www.acehardware.com/departments/paint-and-supplies/tape-glues-and-adhesives/glues-and-epoxy/1000958) **$10**
- Aluminum Sheet:
    - Raw material 0.032"/8mm thick [Industrial Metal Supply](https://www.industrialmetalsupply.com/aluminum/sheet-plate/5052#1) **$7**
        - Make yourself on WaterJet (ProtoMax) or Laser (fablight, OMTech)
    - Fabricated by [Send Cut Send](https://sendcutsend.com) 
        - Sandwith **$46** (use second Rim instead)
        - Bottom **$16**
        - Rim **13.74**
        - Cover **$15.64**
        - Face **$14.86**
- Spacer:
    - PLA 3D printed, requires large bed printer such as Prusa XL **$8**

### MiniView 9.7" V2

The case can be manufactured with 3D Printer and laser or water jet cut plates.

- [Faceplate DXF](assets/MiniView/V2/MiniView%20-%20Face.dxf)
- [Bottomplate DXF](assets/MiniView/V2/MiniView%20-%20Bottom.dxf)
- [Coverplate DXF](assets/MiniView/V2/MiniView%20-%20Cover.dxf)
- [Rimplate DXF](assets/MiniView/V2/MiniView%20-%20Rim.dxf)
- [Sandwichplate DXF](assets/MiniView/V2/MiniView%20-%20Sandwich.dxf)
- [Spacer ZIP of STL](assets/MiniView/V2/MiniView%20-%20Spacer.zip)

<a href="https://cad.onshape.com/documents/be3ee7f66bee314b5a94be03/w/50f87e2b6d8fc3bc46db833f/e/19b127f7070aa7e81b224c8b" target="_blank"> <img src="assets/MiniView/V2/MiniView.png" width="600"> </a>

### MiniView 9.7" V1

The case can be manufactured with laser or water jet cutting and a sheet metal brake.

- [Faceplate DXF](assets/MiniView/V1/MiniView-Face.dxf)
- [Coverplate DXF](assets/MiniView/V1/MiniView-Cover.dxf)
- [Bottomplate DXF](assets/MiniView/V1/MiniView-Bottom.dxf)
- [Reinforceplate DXF](assets/MiniView/V1/MiniView-Reinforce.dxf)
<a href="https://cad.onshape.com/documents/50a761747f1cc16e77337847/w/4e47fa5bfd7f5cd9f7cffc1a/e/f2395dc996873481e09ebc19" target="_blank"> <img src="assets/MiniView/V1/MiniView.png" width="600"> </a>

<a target="_blank"> <img src="assets/MiniView/V1/MiniViewFront.jpg" height="300"> </a>
<a target="_blank"> <img src="assets/MiniView/V1/MiniViewSide.jpg" height="300"> </a>
<a target="_blank"> <img src="assets/MiniView/V1/MiniViewBack.jpg" width="300"> </a>


The face plate requires sheet metal bending.

#### Bend Allowance Calculation
5052 Aluminium $K = 0.45$

$Bend Allowance = 3.141/180 * bend_{angle} * (radius_{indisde} + K * thickness)$

For a 1mm (0.04") thick sheet bend allowance is 2.28mm.
For a 0.81mm (0.032") thick sheet bend allowance is 2.14mm


### MaxiView
16" 4k display is about $120 plus $20-30 driver board.

## Example folding display arrangements

<img src=".\Sketchup.svg" alt="drawing" height="400"/>  

DIY Perks display is based on iPad 3/4 displays and central 15" gaming LCD.


### High Resolution Screen Dimensions

| Resolution | Diagonal  | Width | Height | OLED | eBay / Aliexpress |
| -----------| ----------| ----- | ------ | ---- | --- |
| 2560x1600  | 8.4"      | 7.12  | 4.45   | Y | $100
| 2560x1600  | 8.9"      | 7.56  | 4.72   | n |
| 2048x1536  | 9.7       | 7.74  | 5.81   | n | $30 iPad3/4
| 2560x1600  | 10.5      | 8.92  | 5.57   | y | $80
| 3840x2160  | 13.3"     | 11.57 | 6.51   | y | $90-140
| 2880x1800  | 13.3"     | 11.57 | 6.51   | n | $100-180
| 3840x2160  | 14"       | 12.17 | 6,85   | n |
| 3840x2400  | 14"       | 11.88 | 7.43   | y | $230
| 3840x2160  | 15.6"     | 13.55 | 7.62   | y | $230
| 2560X1440  | 15.6"     | 13.59 | 7.65   | n | Gaming 165Hz laptop |
| 3840x2400  | 16"       |       |        | n | $75-$95
| 3840x2400  | 16"       | 13.56 | 8.48   | y | $120-160
| 3840X2400  | 17"       | 14.42 | 9.01   | n |

### 8.3" Side Panel
8.3" 2266x1488 326dpi  6.94x4.56

### 8.4" Side Panel
| | | |  
| --- | --- | --- |  
| 1600x2560 | | 7.12x4.45

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
| Sharp   | TL084BDXP02-05 | 430 | 1500:1  | MIPI | LCM | 60Hz  
| Samsung | AMS840CS03     | 300 | 10000:1 | MIPI | OLED | 60Hz  
| Samsung | AMS840CS04     |  |  |  | OLED |   

### 8.9" Side Panel
2560x1600 7.5x4.7

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
| JDI | TFTMD089030 | 500 | 1200:1 | MIPI | LCM | 60Hz

| | | |  
| --- | --- | --- |  
| 1920x1200 | | |

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
| Sam | LTL089CL02-002 | 450 | 900:1 | MIPI | LCM | 60Hz

### 9.7" Side Panel
**LEAST EXPENSIVE**
| | | |  
| --- | --- | --- |  
| 2048x1536 | | 7.76"x5.82"
|           | | 168.25 x 209 x 2.8mmm (5.1mm thickest place at flat cable fold++)

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate | Comment |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- | ------- |
| LG      | LP097QX1-SPA1 | 440 |  800:1 |     | LCM  | 60Hz | ipad 3,4 |
| LG      | LP097QX2      | 440 |  800:1 |     | LCM  | 60Hz |          |
| Samsung | LTL097QL01    | 420 | 1000:1 | eDP | WLED | 60Hz | iPad 3,4 |

On AliExpress driver board with display is $43. Search for LP097QX1-SPA1 

### 10.5" Side Panel

2560*1600, 2k

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
| Samsung | AMSA05BV09| 300 | 54,000:1 | MIPI | OLED | 60Hz |

### 12.9" Side Panel

| | | |  
| --- | --- | --- |  
| 2732x2048 | |  | 

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate | Comment |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- | ------- |
| LG           |        |  | |  |  |  | ipadPro 12.9


### 13.3" Main Display

| | | |  
| --- | --- | --- |  
| 3840x2160 | 4k | 11.57x6.51 | 

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
| LG      | LP133UD1-SPA1 | 340 | 1400:1  | eDP | LCM    | 60Hz |
| Samsung | ATNA33TP10    | 400 | 10000:1 | eDP | AMOLED | 60Hz | $140
| Sharp   | LQ133D1JX31   | 400 | 1500:1  | eDP | LCM    | 60Hz |

- ATNA33TP10 11.57 x 6.51 (293.76(W) × 165.24(H) mm), $100 - $105, (non touch) 2023
- ATNA33TP11 11.57 x 6.51 (293.76(W) × 165.24(H) mm), 75 - 130 AliExpress, $ 130(ebay) (non touch) 2022

| | | |  
| --- | --- | --- |  
| 2880x1800 | 3k | 11.25" x 7.04"

- ATNA33AA05-0,   $168
- ATNA33AA01-002 $100
- ATNA33AA06 $120
- ATNA33AA02-0 $160-188
- ATNA33AA03-0 $120-180

### 14" Main Display

| | | |  
| --- | --- | --- | 
| 3840x2160 | 4k | 12.2" x 6.86"

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
| LG | LP140UD2-SPB1 | 400 | ? | eDP | LCM | ?

| | | |  
| --- | --- | --- | 
| 3840x2400 | 4k | 11.9" x 7.4"

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
| Samsung | ATNA40YN04-0 | 400 | 100,000:1 | edP | OLED | 60HZ
| Samsung | ATNA40YN04-1 | 400 | 100,000:1 | eDP | OLED | 60Hz

### 15.6" Main Display
| | | |  
| --- | --- | --- |  
| 3840x2160 | 4k | 13.55" x 7.62"

| Manufacturer | Part # | Brightness   | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ----------   | -------- | --------- | ---- | --------- |
| BOE     | NE156QUM-NZ3 | 400         | 1,200:1   | eDP      | LCM  | **120Hz**
| Samsung | ATNA56WR06-0 | 440         | 100,000:1 | eDP      | OLED | 60Hz

Samsung
- ATNA56WR06-0,  13.55 x 7.62 (344.218(W)×193.622(H) mm), $130-150 AliExpress
- ATNA56WR18-0,  13.55 x 7.62 (344.218(W)×193.622(H) mm), $180-220 AliExpress
- ATNA56WR01-002,13.55 x 7.62 (344.218(W)×193.622(H) mm), $200-350 AliExpress
- ATNA56WR04-0,  13.55 x 7.62 (344.218(W)×193.622(H) mm), $190-280 AliExpress
- ATNA56WR16-0,  13.55 x 7.62 (344.218(W)×193.622(H) mm), $190-200 AliExpress
- ATNA56WR11,    13.55 x 7.62 (344.218(W)×193.622(H) mm), $150-250 AliExpress

BOE
- NE156QUM-NZ3,  13.55 x 7.62 (344.218(W)×193.622(H) mm), $80-90 AliExpress

### 16" Main Display

| | | |  
| --- | --- | --- |  
| 3840x2400 | 4k | 13.56 x 8.48

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
| Sam | ATNA60YV02-0  | 440 | 100,000:1 | eDP1.4b | OLED | 60Hz
| BOE | NE160QAM-NX1  | 500 | 1200:1 | eDP | WLED | **120Hz** 
| LG  | LP160UQ1-SPB1 | 600 | 1500:1 | eDP | WLED |  60Hz

Oled

- ATNA60YV01-0, 13.56 x 8.48 (344.448(W)×215.28(H) mm), $140 - $160
- ATNA60YV02-0, 13.56 x 8.48 (344.448(W)×215.28(H) mm), $120 - 145 
- ATNA60YV06-0, 13.56 x 8.48 (344.448(W)×215.28(H) mm), $200 - 225
- ATNA60YV07,   13.56 x 8.48 (344.448(W)×215.28(H) mm), $190 - 250
- ATNA60YV08,   13.56 x 8.48 (344.448(W)×215.28(H) mm), $205 - 260
- ATNA60YV09,   13.56 x 8.48 (344.448(W)×215.28(H) mm), $330

WLED
- LP160UQ1-SPB1 $75-$95
- NE160QAM-NX1 $90 -$120
- NE160QAM-NZ1 $80 -$120
- NE160QAM-N61
- NE160QAM-NM1

### 17" Main Display

| | | |  
| --- | --- | --- |  
| 3840x2400 | 4k | 13.56 x 8.48

| Manufacturer | Part # | Brightness | Contrast | Connector | Type | Framerate |
| ------------ | ------ | ---------- | -------- | --------- | ---- | --------- |
|  Sharp | LQ170R1JX41| 500 | 1,600:1 | eDP1.4b | WLED | 60Hz | ?
|  Sharp | LQ170R1JX42| 500 | 1,600:1 | eDP1.4b | WLED | 60Hz | ?

- LQ170R1JX41 $95 - $145 AliExpress
- LQ170R1JX42 $85 - $120 AliExpress

## USB-C MST dock

### Three Displays through USB-C
- Startec tripple 4k USB-C to HDMI https://a.co/d/8HaL61R

Needs UBS-C DisplayPort 1.4 with compression om computer for triple 4k 60Hz display

### Two Displays through UBS-C

### DIY Hub

- TUSB1046-DCI for each display port
- TI HD3SS460  Display Port Splitter MST
DisplayPort MST HUB: 
- Synaptic VMM9430
- Synaptic DL-7400
- TPS65987D  USB PD controller
- USB Hub IC (microchip or renesas)

## Controller Boards

### iPad3/4 Controller Board

1) Adafruit Qualia Bare Driver iPad DisplayPort LP097QX1 driver
2) iPad 3/4 LP097QX1-SPA1 LTL097QL01 9.7 Inch DIY IPS 2048*1536 LCD Display Screen Monitor Control Driver Board $13, Mini-HDMI, UBS-C
3) Mini HDMI USB Type-C LCD Control Driver Board for iPad 3/4 LP097QX1/LTN097QL01, same as above from eBay $30
4) IPAD3 / 4 2K 2048X1536 LP097QX1 A1416 A1430 A1403 A1458 A1459 A1460 LCD Screen Mini-HDMI Control Driver Board Kit , mini-HDMI $ 10
5) IPAD5 9.7 inch eDP LCD screen 2K DIY Driver Board Kit MINI HDMI VGA type-C USB LP097QX2 air A1474 A1475 A1822 A1823 A1893, $26.40, USB-C, Mini-HDMI

### eDP Controller Board

1) Aliexpress $16, 40PIN Micro HDMI to EDP driver board EDP Signal LCD screen driver Adapter Portable LCD Display Projection 2K 4K 60hz 120Hz 144hz
    - 1920*1080/120HZ,
    - 1920*1200/144HZ, 
    - 2560*1440/120HZ,
    - 2560*1600/120HZ, 
    - 3200*1800/48HZ, 
    - 3840*2160/60HZ, 
    - 3840*2400/60HZ 

compatible with 16:9/16:10 

2) $19 edp driver board 4k 8K 120HZ DP to eDP for Portable LCD display edp 30P 40P
3) $30 40P 0.5mm edp lcd driver board HDMI input Type-c PD power 5-20V support 4K 60HZ 3K 2K 1080P

## Power

## Enclosure

## Resolutions

STD
- UXGA 1600x1200
- QXGA 2048x1536 or 2048x1600

Wide
- WUXGA 1920x1080 or 1920x1200 1.6:1

Large Wide
- QWXGA 2048x1152
- 3.6k 2560X1440 16:9
- WQXGA 2560x1600
- WQSXGA 3200x2048
- WQUXGa 3840X2400 3840X2160 4K 
- 8K 7680x4320 8K


Sizes
- 13-14 Light
- 15-16 Standard
- 17-18 Large


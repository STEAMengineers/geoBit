# Hardware

### Controller
[RP2354a](https://www.lcsc.com/product-detail/C41378174.html)

### Battery charger
[Injoinic IP5306-I2C](https://www.lcsc.com/product-detail/C488349.html)
Provides 2.1A boosted output at 5V. Use I2C to set registers to prevent the chip from entering sleep mode and read battery charge status. 

[Details of register settings](https://github.com/AvinasheeTech/IP5306_I2C)

### SD card
Uses SDIO (Four line) interface. The interface is protected with an [ST EMIF06-MSD02N16](https://www.lcsc.com/product-detail/C5267594.html?s_z=n_C5267594) chip

### GPS
[ATGM336H-6N-74](https://www.lcsc.com/product-detail/C5804601.html)

### Screen
[Good display GDEY0154D67](https://www.good-display.com/product/388.html)

### GPIO

| Pin  | Name  | Function  | Notes |
|---|---|---|---|
| GPIO_0  | CHGR_SDA  | 	I2C0 SDA  | |
| GPIO_1 | CHGR_SCL  | 	I2C0 SCL  | |
| GPIO_2 | CHGR_IRQ  | 	SIO  | |
| GPIO_3 | BUTTON1  | 	SIO  | |
| GPIO_4 | BUTTON2 | 	SIO  | |
| GPIO_5 | FILTERED_SD_CLK  | 	SIO  | |
| GPIO_6 | FILTERED_SD_CMD  | 	SIO  | |
| GPIO_7 | FILTERED_SD_DAT0  | 	SIO  | |
| GPIO_8 | FILTERED_SD_DAT1  | 	SIO  | |
| GPIO_9 | FILTERED_SD_DAT2  | 	SIO  | |
| GPIO_10 | FILTERED_SD_DAT3  | 	SIO  | |
| GPIO_11 | FILTERED_SD_DET  | 	SIO  | |
| GPIO_12 | GPS_RX  | 	UART0_TX  | |
| GPIO_13 | GPS_TX  | 	UART0_RX  | |
| GPIO_14 | GPS_1PPS  | 	SIO  | |
| GPIO_15 | STATUS_LED  | 	SIO  | |
| GPIO_16 | BUTTON3  | 	SIO  | |
| GPIO_17 | EINK_CS  | 	SPI1_CSn  | |
| GPIO_18 | EINK_SCLK  | 	SPI1_SCK  | |
| GPIO_19 | EINK_SDI  | 	SPI1_TX  | |
| GPIO_20 | EINK_D/C  | 	SIO  | |
| GPIO_21 | EINK_RES  | 	SIO  | |
| GPIO_22 | EINK_BUSY  | 	SIO  | |
| GPIO_23 | UNALLOCATED  | 	SIO  | |
| GPIO_24 | UNALLOCATED  | 	SIO  | |
| GPIO_25 | UNALLOCATED  | 	SIO  | |
| GPIO_26 | UNALLOCATED  | 	SIO  | ADC |
| GPIO_27 | UNALLOCATED  | 	SIO  | ADC |
| GPIO_28 | UNALLOCATED  | 	SIO  | ADC |
| GPIO_29 | UNALLOCATED  | 	SIO  | ADC |



# Áp dụng cho mạch DIY AI tím (đã test với màn tft 1.54 7pin)
 
# Sử dụng IDF Tool
```html
idf.py fullclean
idf.py set-target esp32s3
idf.py menuconfig
idf.py build
idf.py flash or idf.py -p COM4 flash 
```
# Chỉnh độ nhạy mic (dễ nhiễu)
```html
idf.py menuconfig
Component config > ADC Mic > (3) Apply Gain > 4
```

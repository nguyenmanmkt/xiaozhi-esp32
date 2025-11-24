# Áp dụng cho mạch DIY AI tím (đã test với màn tft 1.54 7pin)
 <img width="1536" height="1142" alt="image" src="https://github.com/user-attachments/assets/b34de086-2b7f-40e6-a5b8-43fb9fd7264e" />

# Sử dụng IDF Tool
```html
idf.py fullclean
idf.py set-target esp32s3
idf.py menuconfig
idf.py build
idf.py flash hoặc idf.py -p COM4 flash 
```
# Chỉnh độ nhạy mic (dễ nhiễu)
```html
idf.py menuconfig
Component config > ADC Mic > (3) Apply Gain > 4
```


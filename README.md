#Рабочая библиотека совместимая с Arduino IDE 1.8.13+
Отсутствуют предупреждения и ошибки при компиляции с использованием miniCore, GyverCore, штатных ардуино.
для Atmega328p \ Atmega168p
-
In function 'void setup()':
warning: invalid conversion from 'byte* {aka unsigned char*}' to 'uint64_t {aka long long unsigned int}' [-fpermissive]
radio.openReadingPipe(1,address[0]);     
RF24.h:350:8: note: initializing argument 2 of 'void RF24::openReadingPipe(uint8_t, uint64_t)'
void openReadingPipe(uint8_t number, uint64_t address);
-
Код занимает чуть меньше места в памяти.

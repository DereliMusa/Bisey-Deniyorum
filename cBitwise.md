# Bit Operatörleri

Bit operatörleri, bilgisayar biliminde ve programlamada bit seviyesinde manipülasyon yapmak için kullanılan operatörlerdir. C dilinde 6 adet bit operatörü bulunur: AND (&), OR (|), XOR (^), NOT (~), Left Shift (<<) ve Right Shift (>>). Bu operatörler, genellikle verimli kod yazmak, donanım seviyesinde kontrol sağlamak ve bazı algoritmaları uygulamak için kullanılır.

## AND (&)
Bu operatör, her iki operandın da ilgili bitlerinin 1 olduğu durumları döndürür.
```c
unsigned int a = 5;   // 0101
unsigned int b = 3;   // 0011
unsigned int result = a & b; // 0001 (1)

```
## OR (|)
Bu operatör, her iki operandın da ilgili bitlerinden en az birinin 1 olduğu durumları döndürür.
```c
unsigned int a = 5;   // 0101
unsigned int b = 3;   // 0011
unsigned int result = a | b; // 0111 (7)
```
## XOR (^)
Bu operatör, her iki operandın da ilgili bitlerinden sadece birinin 1 olduğu durumları döndürür.
```c
unsigned int a = 5;   // 0101
unsigned int b = 3;   // 0011
unsigned int result = a ^ b; // 0110 (6)
```
## NOT (~)
 Bu operatör, operandın her bitini tersine çevirir.
```c
unsigned int a = 5;   // 0101
unsigned int result = ~a;  // 1010 (12)
```
## Left Shift (<<)
 Bu operatör, operandın belirtilen miktarda bitlerini sola kaydırır.
```c
unsigned int a = 5;   // 0000 0101
unsigned int result = a << 2; // 0001 0100 (20)
```
## Right Shift (>>)
 Bu operatör, operandın belirtilen miktarda bitlerini sağa kaydırır. İkili işaretli tamsayılar için sol taraftaki boş bitler işaretle doldurulurken, ikili işaretsiz tamsayılar için sıfır ile doldurulur.
```c
unsigned int a = 20;  // 0001 0100
unsigned int result = a >> 2; // 0000 0101 (5)
```
Bit operatörleri, özellikle bellek tasarrufu sağlamak, hızlı matematiksel işlemler gerçekleştirmek ve verimli kod yazmak için yaygın olarak kullanılır.
[16,21,11,8,12,22]

İlk olarak ortadan ikiye bölüyoruz 

[16,21,11]

Bu sayıları [16] ve [21,11] olarak ayırıyoruz 
16 sabit şekilde kalıyor çünkü 21 den büyük değil [16] [21,11] olarak kalıyor 
Ardından 21 ve 11 karşılaştırıyoruz 11 21 den küçük olduğu için yerlerini değişitiyoruz
artık sıralama [16] [11,21] oluyor son aşamada 3 de birleşeceği zaman 16 ve 11 i de karşılaştırıyoruz ve [11,16,21] haline gelmiş oluyor 

[8,12,22]
Bu sayıları [8] ve [12,22] olarak ayırıyoruz 
8 sabit şekilde kalıyor çünkü 16 den büyük değil [8] [12,22] olarak kalıyor 
Bunların sırası doğru olduğu için son aşamaya bu şekilde girebiliriler 

Bunun sonucunda [11,16,21]  [8,12,22] şekline geliyorlar 
 Son olarak [8,11,12,16,21,22]  haline geliyorlar 

Big-O gösterimi

O(nlogn)
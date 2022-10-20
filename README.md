# Patika-Dev-
****
[22,27,16,2,18,6] -> Insertion Sort
****
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

 1 -> [22,27,16,2,18,6] dizimizin ilk hali
 2 -> [2,27,16,22,18,6] 2 yi en başa alıyoruz en küçük olduğu için en baştaki sayının kaybolmaması için 2 nin önceki yerine ilk baştaki sayıyı koyuyoruz
 3 -> [2,6,16,22,18,27] 2 yi yerleştirdikten sonra ikinci kısma geçiyoruz 2 hariç en klüçük sayı 6 olduğu için ve 2 den sonra en baştaki sayı 27 olduğu için 6 ile 27 yi yer değiştiriyoruz
 4 -> [2,6,16,22,18,27] 6 yı yerleştirdikten sonra 3.kısma geliyoruz ve ilk iki kısımdan sonra en baştaki sayı en küçük olduğu için işlem yapmıyoruz
 5 -> [2,6,16,18,22,27] ilk üç kısım dan sonra 4.kısma geçiyoruz 4.kısımda en küçük sayı 18 olduğu için 18 ile en baştaki sayı 22 ile yer değiştiriyoruz 
 6 -> [2,6,16,18,22,27] sıralama doğru bir şekilde olduğu için küçükten büyüğe doğru işlemimiz bitiriyoruz
 
 ****
 Big-O gösterimini yazınız.
 
 Big-O gösterimi O(n^2)  -> n karedir
 çünkü ilk aşamada n kadar işlem yaparız ikinci aşamada ilk sayıyı bulduğumuz için n-1 şeklinde işlem yaparız bu aşamaların toplamı 1 den n e kadar olan sayıların      toplamı kadar adım vardır bunun matematikte n çarpı parantez içinde n artı 1 bölü 2 olduğu için ve dolayısıyla n kare artı n bölü 2 olduğu için en baskın n kare olduğu için Big-0 n karedir
 ****
 Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 Avarage Case
****
 
 
 

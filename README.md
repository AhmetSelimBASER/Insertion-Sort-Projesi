# Proje 1

## SORULAR

1. [22,27,16,2,18,6] -> Insertion Sort
    1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    2. Big-O gösterimini yazınız.
    3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

2. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## CEVAPLAR

1. [22,27,16,2,18,6] -> Insertion Sort

    1. [**2**,27,16,**22**,18,6] : Dizinin başındaki 22 sayısı ile dizideki en küçük sayı olan 2 yer değiştirdi.
    
    2. [2,**6**,16,22,18,**27**] : Daha sonra 27 sayısıyla başlayıp diğer sayıları onunla kıyasladık, 6 sayısı dizideki en küçük sayı olduğundan 27 sayısı ile yer değiştirdi.
    
    3. [2,6,16,**18**,**22**,27] : Daha sonra 22 sayısıyla başlayıp diğer sayıları onunla kıyasladık, 18 sayısı dizideki en küçük sayı olduğundan 22 sayısı ile yer değiştirdi. Artık dizimiz sıralı hale geldiğinden sorting işlemi burada son buldu

2. O(n<sup>2</sup>)

3. Time Complexity: Time Complexity: Worst case: Aradığımız sayının sonda olması

4. Time Complexity: Average case: Aradığımız sayının ortada olması


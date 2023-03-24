# MergeSort
www.patika.dev
[16,21,11,8,12,22] -> Merge Sort

1-) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
İlk olarak, verilen diziyi Merge Sort algoritmasına göre sıralayalım.


Dizi elemanlarını yarıya bölelim: [16,21,11] ve [8,12,22]

Her bir alt dizi için tekrar yarıya bölelim: [16], [21,11] ve [8], [12,22]

Her bir alt-alt dizi için tek eleman kalana kadar yarıya bölelim: [16], [21], [11] ve [8], [12], [22]

Her alt-alt dizi için sıralayarak birleştirelim: [16], [11,21] ve [8], [12,22]

İki alt dizi için de birleştirme işlemi yapalım: [11,16,21] ve [8,12,22]

Son olarak, iki alt diziyi birleştirerek tam sıralı diziyi elde edelim: [8,11,12,16,21,22]

Böylece, verilen dizi Merge Sort algoritmasına göre sıralanmıştır.

2-) Big-O gösterimini yazınız.

Big-O gösterimi için, Merge Sort algoritması O(nlogn) zamanda çalışır. Bu nlogn terimi, algoritmanın çalışma süresinin n elemanlı diziler için logaritmik bir artış göstermesinden kaynaklanır. Bu durum, Merge Sort'un genellikle hızlı ve verimli bir sıralama algoritması olarak tercih edilmesine sebep olur.

# www.patika.dev-Insertion-Sort-Projesi

dizimiz [22,27,16,2,18,6]

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- dizidki en küçük terimin 2 olduğunu belirleyerek ilk sıradaki 22 ile yer değiştiriyoruz
[2,27,16,22,18,6]
- ikinci sıradan başlayarak en küçük terimin 6 olduğunu belirliyoruz. 27 ile yer değiştiriyoruz.
[2,6,16,22,18,27]
- üçüncü sıradan başlayarak en küçük terimin 16 olduğunu görüyoruz. bir değişiklik yapmıyoruz.
- dördüncü terimden başlayarak en küçük terimin 18 olduğunu belirliyoruz. 18 ile 22 terimlerinin yerlerini değiştiriyoruz.
[2,6,16,18,22,27]
- beşinci terimden başlayarak en küçük terimin 22 olduğunu belirliyoruz. Değişiklik yapmıyoruz
ve insertion sort işlemimiz bitiyor

2. Big-O gösterimini yazınız.
- bigO gösterimimiz O(n^2)

3. Time Complexity:
-Worst case: n*(n+1)/2 ==> O(n^2)
-Best case: n ==> O(n)
-Average case: n/2*(n/2+1)/2 ==> O(n^2)

4. aradığımız sayı orta sıralara yakın olduğu için avarage case kapsamına girer

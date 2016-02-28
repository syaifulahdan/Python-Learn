### Python-Learn-pengurutan Hasil operator matematika

Mengubah Urutan Evaluasi Untuk membuat ekspresi lebih mudah dibaca, kita dapat menggunakan tanda kurung. Sebagai contoh, 2
+ (3 * 4) lebih mudah dipahami daripada 2 + 3 * 4 dimana pembaca harus mengetahui urutan evaluasi operator. Namun pemakaian tanda kurung jangan terlalu berlebihan seperti (2 + (3 * 4)).
Selain itu, tanda kurung dapat mengubah urutan evaluasi operator. Sebagai contoh (2 + 3) * 4, operasi penambahan akan dievaluasi terlebih dahulu.




<b>Script</b>
<pre>
hasil = 2 + 3 * 4
print '2 + 3 * 4 = %s' % hasil
print '-' * 50

hasil = (2 + 3) * 4
print '(2 + 3) * 4 = %s' % hasil
print '-' * 50

hasil = 2 / 3 * 4
print '2 / 3 * 4 = %s' % hasil
print '-' * 50

hasil = 2.0 / 3 * 4
print '2.0 / 3 * 4 = %s' % hasil
print '-' * 50
</pre>

<b>Output</b>

<pre>
Python 2.7.6 (default, Jun 22 2015, 18:00:18) 
[GCC 4.8.2] on linux2
Type "copyright", "credits" or "license()" for more information.
>>> ================================ RESTART ================================
>>> 
2 + 3 * 4 = 14
--------------------------------------------------
(2 + 3) * 4 = 20
--------------------------------------------------
2 / 3 * 4 = 0
--------------------------------------------------
2.0 / 3 * 4 = 2.66666666667
--------------------------------------------------
>>> 

</pre>

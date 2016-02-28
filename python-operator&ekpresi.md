### Python-Learn-Operator& Ekpresi

Hampir semua statemen (baris logis) yang Anda tulis akan mengandung ekspresi. Contoh sederhana dari ekspresi adalah 2+3. Sebuah ekspresi dapat diturunkan menjadi operator dan operand.
Operator adalah fungsi yang menjalankan sesuatu dan direpresentasikan oleh simbol, seperti + atau kata kunci khusus. Operator membutuhkan data untuk dioperasikan dan data ini disebut operand.
Dalam kasus ini 2 dan 3 adalah operand

<b>Operator</b>

Kita akan melihat operator secara singkat dan bagaimana penggunaannya:

+   : Menambahkan dua obyek

-   : Mengurangi obyek dengan obyek yang lain

*   : Perkalian

**  : Pangkat

/   : Pembagian

//  : Pembagian Bulat kebawah

&   : Sisa hasil bagi (modulus)

<<  : (geser kiri) Menggeser bit ke sebelah kiri sesuai dengan jumlah bit yang ditentukan. 2 << 2 menghasilkan 8. 2 direpresentasikan 10 dalam bit (binary
      digit). Menggeser 2 bit kekiri akan menghasilkan 1000 yang merupakan representasi dari desimal 8
      
>>  : (geser kanan) Menggeser bit ke sebelah kanan sesuai dengan jumlah bit yang ditentukan. 11 > 1 menghasilkan 5. 11 direpresentasikan oleh bit dengan 1101
      kemudian digeser kekanan 1 bit menghasilkan 101 yang merupakan desimal angka 5.
      
&   : (bit-wise AND) Operasi bit-wise AND dari angka (bit-wise adalah operasi angka berbasis bit yakni dengan 0 dan 1). 5 & 3menghasilkan 1.

|   : (bit-wise OR) Operasi bit-wise OR dari angka. 5 | 3 menghasilkan 7.

^   : (bit-wise XOR) Operasi bit-wise XOR (ekslusif OR). 5 ^ 3 menghasilkan6.

~   : (bit-wise invert) Operasi membalikkan angka bitwise dari x, menghasilkan -x - 1. ~5 akan menghasilkan -6. lihattwo’s complement.

<   : (kurang dari) Mengembalikan apakah x kurang dari y. Semua operator pembanding mengembalikan True atau False. 5 < 3 
      mengembalikan False, 3 < 5 mengembalikan True dan2 < 5 < 7mengembalikan True.
      
>   : (lebih dari) Mengembalikan apakah x lebih dari y. 5 > 3mengembalikan True.

<=  : (kurang dari atau sama dengan) Mengembalikan apakah x kurang dari atau sama dengan y. 5 <= 5 mengembalikan True.

>=  : (lebih dari atau sama dengan) Mengembalikan apakah x lebih dari atau sama dengan y. 5 >= 5 mengembalikan True.

==  : (sama dengan) Membandingkan apakah kedua obyek sama. 2 == 2mengembalikan True, 'nama' == 'Nama'mengembalikan False, 'nama' == 'nama'mengembalikan True.

!=  : (tidak sama dengan) Membandingkan apakah kedua obyek berbeda. 2 != 3mengembalikan True.

not : (boolean NOT) Jika x bernilai True akan mengembalikan False. Jika x bernilai False akan mengembalikan True. x = True;not x mengembalikan False.

and : (boolean AND) x and y mengembalikan False jika x bernilai False, selain itu akan mengembalikan nilai y. x = False; y = True; x and y akan mengembalikanFalse karena x bernilai False. Pada kasus ini Python tidak akan mengevaluasi y karena nilai x. Hal ini disebutshort-circuit evaluasi.

or  : (boolean OR) Jika x bernilai True, x or y akan mengembalikan True, selain itu akan mengembalikan nilai y. x = True; y = False; x or y mengembalikan True.short-circuit evaluasi berlaku juga disini.

<b> script 1:</b>

<pre>
print '-' * 80
bilangan1 = 5
bilangan2 = 3
print 'bil1 = ', bilangan1
print 'bil2 = ', bilangan2
print 'bil1 + bil2 = ', bilangan1 + bilangan2
print 'bil1 - bil2 = %s' % (bilangan1 - bilangan2)
print 'bil1 * bil2 = {0}'.format(bilangan1 * bilangan2)
print 'bil1 ** bil2 = ', bilangan1 ** bilangan2
print '-' * 80
</pre>
<b> output 1:</b>

<pre>
--------------------------------------------------------------------------------
bil1 =  5
bil2 =  3
bil1 + bil2 =  8
bil1 - bil2 = 2
bil1 * bil2 = 15
bil1 ** bil2 =  125
-------------------------------------------------------------------------------
</pre>

<b> script 2:</b>

<pre>
bilangan1 = 5.0
print 'bil1 = ', bilangan1
print 'bil2 = ', bilangan2
print 'bil1 / bil2 = ', bilangan1 / bilangan2
print 'bil1 // bil2 = ', bilangan1 // bilangan2
print 'bil1 % bil2 = ', bilangan1 % bilangan2
print '-' * 80
</pre>
<b> output 2:</b>

<pre>
--------------------------------------------------------------------------------
bil1 =  5.0
bil2 =  3
bil1 / bil2 =  1.66666666667
bil1 // bil2 =  1.0
bil1 % bil2 =  2.0
-------------------------------------------------------------------------------
</pre>


lanjutan ke Script  : https://gist.github.com/syaifulahdan/9928ab9ed6f2730485b8

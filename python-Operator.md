## Python-Learn operator

Pembahasan kali ini kita akan belajar bersama tentang penggunaan beberapa operator yang ada pada bahasa pemrograman python. Apa sih operator itu? Agak susah memang menjelaskan operator tersebut,
kalau menurut saya sendiri operator itu merupakan suatu perintah yang dapat menghubungkan antara data / variable dengan data / variable yang lain, ya itu memang kalimat saya itu tidak ada dasarnya.
Tapi untuk lebih jelasnya yuks kita kupas bersama operator pada bahasa pemrograman python.

Ada beberapa tipe operator antara lain operator aritmatika, operator untuk membandingkan, operator logika seperti and dan or, dan mungkin masih banyak lagi yang tidak bisa saya sebutkan satu persatu,
nanti teman-teman tambahkan sendiri ya kalau masih ada yang tidak disebutkan.

##Operator Aritmatika
Operator aritmatika sendiri merupakan operator yang dipergunakan dalam melakukan operasi matematika, seperti pengurangan, pembagian, penambahan, perkalian, pangkat, modulus dll. Berikut
contoh penggunaan operator aritmatika pada bahasa pemrograman python :

  <pre class="line-numbers"><code class="language-python">mininet&gt; py h1.IP()
10.0.0.1
mininet&gt; py h2.IP()
10.0.0.2
mininet&gt; py s1.IP()
127.0.0.1
mininet&gt; py s1.ports
{&lt;Intf lo&gt;: 0, &lt;TCIntf s1-eth3&gt;: 3, &lt;TCIntf s1-eth2&gt;: 2, &lt;TCIntf s1-eth1&gt;: 1}
mininet&gt; py s2.ports
{&lt;TCIntf s2-eth2&gt;: 2, &lt;Intf lo&gt;: 0, &lt;TCIntf s2-eth1&gt;: 1}
mininet&gt; py h1.MAC()
26:51:25:0b:04:90
mininet&gt; py h2.MAC()
ca:97:50:a0:f7:ee
</code></pre>
                    <p class="text-center code-caption"><strong>Code Example 4.</strong> More Mininet CLI experiments
                        with the custom topology from Code Example 2.




<pre>

print 3 + 2 * 3 - 10 / 5
print (3 + 2) * (3 - 10 / 5)
#pangkat
print 3 ** 2
#modulus / sisa bagi
print 100 % 3
</pre>


<b>outpunya : </b>
<pre>
Python 2.7.6 (default, Jun 22 2015, 18:00:18) 
[GCC 4.8.2] on linux2
Type "copyright", "credits" or "license()" for more information.
>>> ================================ RESTART ================================
>>> 
7
5
9
1
>>> 
</pre>

###Manipulasi String

<pre>
print 'pintarcoding.com!' *3
print 'hallo' + '' + 'pintarcoding.com!'
</pre>
<b> output </b>
<Pre>
>>> ================================ RESTART ================================
>>> 
pintarcoding.com!pintarcoding.com!pintarcoding.com!
hallopintarcoding.com!
>>> 
</pre>

##Operator Pembanding
Pada bahasa python terdapat 3 operator logika antara lain and, <b> or</b> , <b>dan</b> <b>not</b>. Adapun cara penggunaan dari operator-operator tersebut adalah sebagai berikut :

<pre>
print 10 > 2 and 10 > 5   # bernilai True
print True or False       # bernilai True
print not False           # bernilai True
</pre>

<b>output :</b>
<pre>
>>> ================================ RESTART ================================
>>> 
True
True
True
>>> 
</pre>

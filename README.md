# Css_Selectors
## Universal and element selectors/ Evrensel ve eleman seçiciler
- Bir HTML dosyasına CSS ile stil verirken, seçiciler kullanılır. Döküman içinden seçtiğimiz herhangi bir öğeye bu şekilde yeni özellik ataması yapılır. Selector olarak kullanabileceğimiz pek çok seçenek vardır. (birazdan göreceğiz ama önce selector kullanımından bahsedelim)
```
selector {
         property:value;
         }
```
* __selector:__ Yani seçici, stil vermek istediğimiz öğe(button, * vb)
* __property:__ Seçilen öğenin değiştirilecek özelliği(size, color,background-color vb)
* __value:__ Yeni atadığım değer(10px,red vb)
---
### Selector çeşitleri
__1. Universal Selector (*) :__ Evrensel seçici olarak bilinir. Yani döküman üzerindeki __her şeyi__ seçer ve hepsine ortak bir özellik ekler. Çok mantıklı bir kullanım değildir. Özellikle çok büyük dökümanlarda sıkıntı yaratabilir.
```
* {
   color:black;
   background-color: cyan;
   }
```
* __*:__ Dosyadaki her şeyi seçer.
* __color:__ Her şeyin rengini siyah yapar.
* __background-color:__ Her şeyin arka plan rengini cam yeşili yapar.

__2. Element Selector :__ Belli bir türdeki her şeyi seçer ve istenilen özelliği atar.
```
button {
       font-size:30px;
       }
```
* __button:__ Dosyadaki tüm buttonları seçer.
* __font-size:__ Tüm butonların boyutunu 30px yapar.

__3. Selector List :__ Birden fazla seçiciyi virgül yardımıyla kullanabilmeye yarar. 
```
h1,h2 {
       font-weight:bold;
       }
```
* __h1,h2:__ Dosyadaki tüm h1 ve h2'leri, yani tüm ana başlık ve alt başlıkları seçer.
* __font-weight:__ Seçilen tüm başlıkları kalın yazar.
---
Bunlar gibi pek çok selector vardır. Sonraki dökümanda "ID selector" ve "class selectorden" bahsedeceğiz.

*İyi kodlamalar..*




  

         

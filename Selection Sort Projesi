[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamlarını yazınız

# 1.Adım
[2]27,16,22,18,6]
|________|
(ilk önce en küçük sayıyı bulup en başa alıyoruz ama en baştaki sayıyı silmiyoruz en küçük sayıyı aldığımız yere yazıyoruz)

# 2.Adım
[2,6]16,22,18,27]
   |___________|
(2. sıraya geldiğimiz zamanda en küçük 2. sayıyı 2. sıraya yazıyoruz bunun içinde en küçük 2. sayı olan 6 ile 2. sıradaki 27 sayısının yerini değiştiriyoruz 27 saysını silmiyoruz öncedende yaptığımız gibi yerlerini değiştiryoruz)

# 3.Adım
[2,6,16]22,18,27]
(burada herhangi bir değişim işlemi yapmıyoruz çünkü zaten biz en küçük 3. sayıyı arıyoruz bundan dolaysıyla 3.sıraya en küçük 3.sayıyı yazcaz 3.en küçük sayımız 16 olduğuna göre sırasına bakıyoruz zaten 3. sırada o zaman ayrı yeten bir işleme gerek yok)

# 4.Adım
[2,6,16,18]22,27]
         |__|
(sıra 4. sıraya geldi sayılarımızın arasından en küçük 4. sayıyı arıyoruz gözümüze 5. sıradaki 18 sayısı çarpıyor hemen onu 4. sıradaki 22 sayısısyla yerlerini değiştiriyoruz)

# 5.Adım 
[2,6,16,18,22]27]
(sıra 5. adıma geldi en küçük 5. sayıyı arıyoruz en küçük 5. sayı 5. sırada bulunan 22 sayısı hemen göze batıyor zaten e bizim aradığımız en küçük 5.sayı 22 sayısıydı 22 5. sırada bulunduğuna göre bir değişim yapamamıza gerek kalmıyor)

# 6.Adım
[2,6,16,18,22,27]
( geriye son 1 sayı kaldı oda en büyük sayı oluyor zaten değişecek bir elemanı kalmadığına göre şu anki yeri iyi)
-----------------------------------------------
Big-O gösterimini yazalım 
En başta N tane sayımız vardı diyelim
(1. adımda ne yaptık 2 sayısının yerini değiştirdik o zaman N tane elemandan bir tanesinin yeri kesinleşti o zaman buraya N-1 diyebiliriz çünkü 2 sayısına artık dokunmayazacğız onun yeri kesinleştio zaman N tane sayıdam bir tanesi çıktı)
N+(N-1)
(2. adımda ne yaptık 6 sayısını 2 nin yanına getirdik o zaman 6 sayısısnın yeride kesinleşti artık ona dokunmayacağız zaten önceden 2 nin yeri kesindi bide yabıba 6 geldi toplamda 2 sayının yeri kesinleşti o zaman N tane ihtimalden 2 tanesi kesinleştiğine göre N-2 yi rahatça diyebiliriz)
N+(N-1)+(N-2)
Bu işlemleri böyle en sonda bir eleman kalana kadar yapıyoruz 
N+(N-1)+(N-2)..............+1
Bu kural bize 1 den N e kadar olan sayıların toplamını veriyor
1 Den N sayısına kadar olan sayıların toplamı nasıl bulabiliriz
N.(N+1) % 2 
Diye bir formülümüz var 1 den N e kadar olan sayıların toplamının
Burdan bize ne geldi
N²+N % 2
Big-O Notionda ne yapıyorduk em büyük domine eden fonksiyonu alıyorduk N² nin karesi olduğu için buda dominant diğerlerine göre
O zaman bunun Big-O Notionu
Big-O=(N²) olarak söyleyebiliriz.
----------------------------------------------------
Dizi sıralandıktan sonra 18 sayısı hangi case in kapsamında girer
Aradığımız sayının ortada olması durumu Average case
-----------------------------------------------------
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazalım

# 1.Adım
[2]3,5,8,7,9,4,15,6]
İlk adımda en küçüğü başa yazdım değişen sayılar (7,2)

# 2.Adım
[2,3]5,8,7,9,4,15,6] 
Zaten 2. sıradaki sayı en küçük 2. sayı olduğu için birisiyle yer değiştirmemeize gerek yok değişen sayılar (-)

# 3.Adım
[2,3,4]8,7,9,5,15,6]
En küçük 3. sayımız 4 olarak belirledik o zaman 3. satırdaki 5 le yerini değiştiriyoruz değişen sayılar (5,4)

# 4.Adım
[2,3,4,5]7,9,8,15,6]
En küçük 4. sayımızı arıyoruz ve gözümüze 5 sayısı çarpıyor o zaman 5. sıradaki 8 sayısıyla yerlerini değiştircez değişen sayılar (8,5)

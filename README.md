# Hesap-Makinesi
Tkinter Hesap Makinesi
Python dilinde bir Hesap Makinesi projesidir. Tkinter kütüphanesi kullanılarak kodlanmıştır.

Program 4 işlem yapmaktadır.

Programın Algoritması:

  - Kullanıcıda ilk sayı girişi istenmektedir.

  - Giriş yapıldıktan sonra, yapılmak istenen işlem seçilir ve böylece ikinci sayı girişine geçilir.

  - İkinci sayı girişi istenir.

  - "=" butonuna tıklandıktan sonra sonuç ekrana yazılır.


Programın Kod Özeti:
  
  - Pencere oluşturuldu, boyut, başlık ayarı yapıldı. (250x300) - Hesap Makinesi
  - Sayı girişi ve hesabın yapıldığı konsol "Entry" ile oluşturuldu. Boyut, yazıtipi ve konumlandırması yapıldı.
  - Konsola girilen verilerin yazımı ve işlemler 'yaz' fonksiyonu ile ayarlandı.
  - Sayı butonları oluşturuldu. Butonları tek tek oluşturmak yerine boş bir liste oluşturuldu ve 
   "range" ile 0-9 aralığındaki sayıları içeren bir for döngüsü oluşturuldu. Döngü içerisinde 
    buton boyut ve konumlarıyla oluşturuldu ve 0' dan 10' a kadar for döngüsü dönerek butonları sırayla oluşturdu.
  - Sayı butonların konumlandırması bir döngüyle oluşturuldu. Her buton oluşumunda x ekseninde 20, y ekseninde 50 
    piksel kayma yapılarak sırayla oluşturuldular.
  - Aritmetik işlemler butonu, sayı butonları gibi oluşturuldu. Boş bir liste oluşturulup for döngüsüyle butonlar 
    oluşturuldu ve konum, font, boyut ayarlaması yapıldı. İşlem butonları x ekseninde aynı ye ekseninde ise 50 piksel
    aşağı kaydırılarak konumlandırıldı.
  - Hesaplama işlemleri "islemler" fonksiyonu ile yapıldı. Hesap işlemleri fonksiyon içerisinde hesap değişkeniyle
    tanımlanarak yapıldı. İlgili butona basıldığında yapılacak hesap bu değişken üzerinden yapıldı.Sayı girişleri 
    tek tek alınıp yapılmak istenen işlemden sonra ekrana sonuç yazıldı.

# 
-Projemiz 3 button, 1 LCD ekran 2 çıkış ve 1 tane de Sıcaklık ve sensöründen oluşuyor.
-Sensörden aldıgımız sıcaklık ve nem değerlerini FILTER(basit singnal işleme algoritması) makrosu ile filtreliyoruz.
-Sıcaklık ve nem degerlerini LCD ekran da yazdırıyoruz.
-LCD ekrandaki sıcaklık birimlerini Yeşil button ile değiştirebiliyoruz(C, F ve K)
-LCD ekranda yer alan SP(set point) değerine bağlı olarak çıkış 1 (sol taraftaki led) açma veya kapama yapabiliyoruz.
 Sıcaklık değeri SP degerini geçerse çıkış aktif oluyor. Burada default orlarak 5 santigrad( C ) derecelik bir histerisiz kullandık. 
 örneğin SP 30 dereceyse sıcaklık 30 dereceyi geçince çıkış aktif oluyor sıcaklık 25 dereceden aşağı düşünce çıkış kapanıyor.
-SP değeri mavi ve kırmızı butonlar ile ayarlanabilir.
-Sıcaklıgın belli değerlerine göre çıkış 2 için Duyt Cycle belirleyerek led parlaklıgını değiştirebiliyoruz.

https://wokwi.com/arduino/projects/323600684275466834

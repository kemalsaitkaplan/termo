# 
-Projemiz 3 button, 1 LCD ekran 2 çıkış ve 1 tane de Sıcaklık ve sensöründen oluşuyor.
-Sensörden aldıgımız sıcaklık ve ne değerini FILTER(basit singnal işleme algoritması) makrosu ile filtreliyoruz.
-Sıcaklık ve nem degerlerini LCD ekran da yazdırıyoruz.
-LCD ekrandaki sıcaklık birimlerini Yeşil button ile değiştirebiliyoruz(C, F ve K)
-LCD ekranda yer SP(set point) değerine bağlı olarak çıkış 1 (sol taraftaki led) açma veya kapama yapabiliyoruz.
 Sıcaklık değeri SP degerini geçerse çıkış1 aktif oluyor. Burada default orlarak 5 santigrad( C ) derecelik bir histerisiz kullandık. 
 örneğin 30 derece açılıyor ise 25 derece de kapanıyor.
-SP değeri mavi ve kırmızı butonlar ile ayarlanabilir.
-Sıcaklıgın belli değerlerine göre çıkış 2 için Duyt Cycle belirleyerek led parlaklıgını değiştirebiliyoruz.

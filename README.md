1. Ubuntu sistem gereksinimleri 
    Ubuntuyu kurmadan önce dikkat etmeniz gereken bazı noktalar.
    ->Cihazınızda en az 25 GB boş depolama alanı olmasını tavsiye ederim, fakat minimal bir kurulum istiyorsanız en az 5 GB yeterlidir. 
    ->Kurmak istediğiniz Ununtu sürümünü içeren bir harici depolama (Flash Bellek,SSD,HDD).
    ->Verilerinizin yedeğinin olduğundan emin olun çünkü olası bir aksiliğe her zaman hazır olmanız gerekir, temkinli olmakta fayda var. 
    Minimal Sistem Gereksinimleri:
    + 2 GHz çift çekirdek işlemci 
    + 4GiB RAM (sistem belleği)
    + 50 GB sabit disk alanı (minimal kurulum için 8.6 GB yeterli olucaktır)
    + İnternet erişimi 





2. Ubuntuyu kurma hazırlıkları
    Sistemi kurmaya geçmeden önce her şeyi hazırladığınızdan emin olun. Ardından ubuntunun internet sitesine giderek yükleme işlemine başlayın.
     https://releases.ubuntu.com/noble/ 
    (Benim indirdiğim sürüm Ubuntu 24.04.1)
  
  ![image](https://github.com/user-attachments/assets/4dec2fbd-805e-4e35-8e32-ff10c91f36e5)
  
  
  2.1 Görüntüyü İndirme 
    Ubuntu web sitesini açın ve Masaüstü sürüm görüntüsünü indirin.
  
   
  2.2 Görüntüyü USB’ye Yazma 
    Görünütüyü indirdikten sonra bu yazılımı bir ortama kurmamız gerekiyor (Aldığınız harici disk). Ben Windows’ta flash belleğe kurulum yapacağım. Windows’ta flash belleğe kurulum yapmak için Rufus yardımcı programını kullanarak Flah belleğinizi dönüştürebilirsiniz 
  
  
  2.3 BIOS Ekranı 
    Bilgisayarınız eğer USB belleği direk başlatmıyorsa BIOS ekranınızı açmanız gerekir. Bilgisayarınızı kapatınız ve tekrar açarken BIOS açmak için kullandığınız tuşa BIOS ekranı gelene kadar basınız. Genellikle F12, F2, F10 veya Escape tuşları yaygın olan seçeneklerdir. Bu tuşlara bastıktan sonra karşınıza BIOS ekranı açılacaktır. 
  
  ![image](https://github.com/user-attachments/assets/05c22145-8f0b-410e-86dc-ef7213911cbd)
  
  Burada, Önyükleme sekmesine gitmeniz ve ardından Önyükleme aygıtı önceliği bölümünde USB sürücünüzü veya Harici Diskinizi birinci sıraya yerleştirmeniz gerekiyor. Sonra sadece Çıkış sekmesine gidip Ayarları Kaydet ve Çıkış'a tıklamanız yeterli.





3.UBUNTU 24.04.1’i Yükleme
    BIOS ayarlarının ardından bilgisayarınızı tekrardan başlatmanız gerekiyor, bu sefer USB bellekten başlayacak ve işletim sistemini kurmaya başlayacağız. 
  
  
  3.1 Dil Seçimi 
    Bilgisayarınızı yeniden başlattığınız zaman karşınıza çıkacak ilk ekran dil seçim ekranıdır. Bu ekranı atlayarak ingilizce kurulum ekranına geçebilirsiniz ya da istediğiniz dili seçerek ilerleyebilirsiniz.
  
  
  3.2 Sistem Yükleyicisini yükleme 
    Açılan ekranda Ubuntuyu Yükle seçeneğini seçiniz. Yükleyici başlayacaktır .
  
   ![image](https://github.com/user-attachments/assets/2c28cd32-49f6-40a7-895a-8f601543c92a)
  
  
  3.3 Dil Seçimi 
    Dil seçim ekranında sistem otomatik ingilizce seçili olarak gelicektir değiştirmek isterseniz istediğiniz dili seçebilirsiniz. 
  
   ![image](https://github.com/user-attachments/assets/643a29dc-5dc5-42f5-80bd-2372044be0f9)
  
  
  3.4 Klavye Düzeni 
    Kurulum sırasında klavye düzenini değiştirmek isterseniz, bunu Alt+Shift veya Win+Space ile yapabilirsiniz. 
    Sistem klavyenizde varsayılan olarak ingilizceyi göstericektir eğer farklı bir klavyeniz varsa ekrandan seçebilirsiniz. 
    Alternatif olarak, Klavye Düzenini Algılayı seçerek sisteminizin klavyenizi otomatik ayarlamasını sağlayabilirsiniz. Klavyenizi test etmek istiyorsanız etiketli alanı kullanabilirsiniz. 
    Klavyeniz hazır olduğunda Devam’a tıklayarak bir sonraki ekrana geçebilirsiniz. 
  
   ![image](https://github.com/user-attachments/assets/eecc141b-94f4-4cee-9108-7b6b554c38cc)
  
  
  3.5 Yazılım 
    Başlangıç olarak hangi uygulamaları yüklemek istediğiniz sorlacaktır, iki seçenek var: 
    -Normal Kurulum 
    -Minimal Kurulum
    İlk seçenek, eski varsayılan yardımcı programlar, uygulamalar, oyunlar ve medya oynatıcılarının eşdeğeri olan bir paket. (Herhangi bir Linux kurulumu için harika bir başlangıç noktasıdır)
    İkinci ise önemli ölçüde daha az depolama alanı kaplar ve yalnızca ihtiyacınız olanları yüklemenize olanak tanır. 
    Kurulum türünün altında iki kutu bulunmaktadır; 
    Birisi kurulum sırasında güncellemeleri etkinleştirir, diğeri ise üçüncü taraf yazılımları etkinleştirmek için.
    - Güncellemeleri indir ve üçüncü taraf yazılımları yükle seçeneklerini etkinleştirmenizi öneririz.
    - Ubuntu'yu kurarken en son güncellemeleri alabilmek için internete bağlı kalın.
    - Eğer internete bağlı değilseniz, mevcutsa bir kablosuz ağ seçmeniz istenecektir. Kurulum sırasında bağlantı kurmanızı öneririz, böylece makinenizin güncel olduğundan emin olabiliriz.
   
   ![image](https://github.com/user-attachments/assets/238c5b90-a425-4ecf-93a0-8d189b3ed406)
  
  
  3.6 Diski Bölümlere Ayırma
    Ubuntuyu başka bir işletim sistemiyle birlikte mi yoksa mevcut işletim sisteminizi silip onun yerine mi kurmak istediğinizi seçin.
    -Eğer Windows zaten kurulu ise yükleyicinin bölümlendirmeyi otomatik olarak yapmasını onaylayabilirsiniz. Windows Önyükleme Yöneticisi ile Ubuntuyu yükleyi seçiniz.
    -Ubuntuyu yüklemeden önce sabit diski temizlemek için “Diski sil ve Ubuntuyu yükle” seçeneğini seçiniz. 
    -Eğer kendiniz disk bölümlendirmesi veya diğer gelişmiş seçenekleri ayarlamak için “something else” seçeneğini seçin. 
     (Yan yana kurulum veya önceki bir kurulumu silme ile ilgili seçenekler, yalnızca mevcut kurulumlar tespit edildiğinde sunulmaktadır.)
  
  ![image](https://github.com/user-attachments/assets/bc665c4f-1255-4a24-9329-fb8a7e255481)
  
  
  3.7 Yeni Bölüm Tablosu 
    Tüm boş alanı tek bir alan olarak seçebilir ya da farklı alanlar yaratabilirsiniz. Bu resimde farklı alanları açılmıştır ancak tek bir alanda oluşturmaktan çekinmenize gerek yok. 
    Genelde Linux’ta 3 bölüm oluşturulması önerilir;
    */boot önyükleyici için 
    */ işletim sistemi için 
    */home kullanıcı dosyaları için 
    (Şema olarak bu ilerleme mantığını kullanacağız /boot bölümünü olşturmanız zorunlu değil ancak birden fazla Linux dağıtımı kurmayı düşünüyorsanız tavsiye ederim)
  
  
  3.8 Önyükleyici Bölümü Oluşturma 
    Bir bölümü oluştururken boş alanı seçin ve + ya tıklayın. Bu işlem sizlere bir Linux bölümü oluşturma seçeneği sunacaktır. 
    Açılan pencerede bölümün boyutunu, dosya türünü ve bağlanma noktasını seçmeniz gerekecektir, ön yükleyicinin son zamanlarda kapladığı fazla alan nedeniyle 300 megabayt alan yaratmanız iyi olur. Boyutu seçtikten sonra dosya türünü Ext2 ve bağlanma noktası olarak /boot’u  seçin.
  
  
  3.9 Kök Bölümü Oluşturma 
    Kök bölümü oluşturmak için 50GB’den fazla alan bunun için yeterlidir. Dosya türünü Ext4 olarak seçin ve bağlama noktasını / (kök anlamına gelir) olarak seçin. 
    Eğer /boot ve /home bölümleri hariç tutuluyorsa bu kısmı kesinlikle yapmanız gerekir. İşletim sistemi burada bulunacaktır. 
    Eğer /boot ve /home kısmı ayrı tutuluyorsa sadece bu alana ait dosyalar olacaktır. 
  
  
  
  3.10 /home Bölümü Oluşturma 
    Aynı yöntemleri izleyerek bir /home bölümü oluşturun. Maksimum alanı ayırın, çünkü burası müzik, resimler ve indirilen dosyaları kaydedeceğiniz alandır. 
  
  
  3.11 Disk Bölümlendirmesini Tamamlama 
    Boot, Room ve Home alanları hazır olduğuda Şimdi Yükle’ye tıklayınız. 
  
  
  3.12 Saat Dilimi
    Eğer cihazınız internete bağlı ise konumuzu otomatik olarak tespit edicektir. Konumuzun doğru olduğundan emin olun, eğer emin değilseniz yaşadığınız yeri yazarak ya da haritadan seçerek konumunuzu seçin. 
  
   ![image](https://github.com/user-attachments/assets/eaac039b-a289-4888-aaf1-0f62a40a0bed)
  
   
  3.13 Kullanıcı Oluşturma 
    Adınızı girin, otomatik bir bilgisayar adı önerecektir. Bu seçenekleri isteğinize göre değiştirebilirsiniz. 
    Bilgisayar adı, bilgisayarınızın ağda görünen adı; Kullanıcı adınız ise oturum açma adınızdır.
    Ardından güçlü bir şifre belirleyiniz.
  
   ![image](https://github.com/user-attachments/assets/b90bf754-9890-4506-9a3f-3e08168a3214)
  
  
  3.14 Sistem Kurulumu
    Kurulum aşamaları tamamlandıktan sonra arka planda yükleyici tamamlanacaktır. Makinenizin hızına bağlı olarak kurulumunuz birkaç dakika sürebilir.
    
  ![image](https://github.com/user-attachments/assets/ae19cf73-feed-496e-8ff5-80732f71caa7)
  
  3.15 Yeniden Başlat
    Her şey yüklenip yapılandırıldıktan sonra makinenizi yeniden başlatmanız istenecek. “Şimdi Yeniden Başlat” tuşuna tıklayınız. İstediğinizde Harici Disk veya USB flash belleği çıkarın.
    
  ![image](https://github.com/user-attachments/assets/acbcd8d1-a037-4a71-b8f1-f2303939f915)


4. Sonuçlar
  Bir Linux işletim sistemi olan Ubuntuyu kurmayı başardınız. 
  Ubuntunun diğer işletim sürümleri de bu şekilde kurulur.
  Ubuntunun Tadını Çıkarın

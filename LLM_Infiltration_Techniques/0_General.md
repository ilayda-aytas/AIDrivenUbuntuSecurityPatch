# LLM SIZMA TEKNİKLERİ

Bu rehber LLM penetrasyon tekniklerini anlatmak için eğitim amaçlı, kötü niyetli faaliyetleri teşvik etmek amacıyla değil, güvenlik farkıdalığını artırmak için hazırlanmıştır.

<br> <br>

## Penetrasyon (Sızma) ve LLM ile Alakası Nedir?

Bir sisteme izinsiz erişim yaparak verileri ele geçirmek, sistemi kontrol etmek ya da bozmaktır diyebiliriz. Peki LLM (Large Language Models) bu bağlamda nasıl kullanılıyor olabilir onu inceleyelim. LLM sızma teknikleri, büyük dil modellerinin işleyişine müdahale etmek ya da onlardan gizli bilgileri çekmek için kullanılan tekniklerdir.

Genel anlamda bu tekniklerin hedeflerini sıralayacak olursak:

- Yetkisiz bilgi erişimi yani gizli verileri ifşa etmek
- Modeli yanlış yönlendirip manipüle etmek
- Yanlış cevaplar verip hatalı yönlendirmeler yapmasını sağlamak
- Sistemi çökertip devre dışı bırakmak
- Modelle ilgili özel bilgileri ele geçirmek (mesela, eğitildiği verilerindeki hassas bilgileri ortaya çıkartmak gibi)

şeklinde sıralayabiliriz.

<br> <br>

## LLM'lerin Çalışma Yapısı

LLM'ler, büyük miktarda veriyle eğitilen yapay zeka modelleridir. Temel olarak dildeki kalıp ve ilişkileri öğrenirler. Yani çok fazla metin verisi üzerinden eğitilip dilin yapısını öğrenir ve biz kullanıcıların verdiği inputa uygun yanıtlar üretirler. Biraz da zayıf yönlerinden bahsedecek olursak yukarıda sıraladığımız hedeflerin en son maddesinde söylediğimiz gibi eğitildikleri verilere dayalı olarak gizli bilgileri ifşa etmek, belli komutlarla yanlış ya da istenmeyen bilgiler vermek ve saldırıya karşı korunmasız olduğunu söyleyebileceğimiz, tahmin temelli yanıt üretmek gibi konuları sayabiliriz.

<br> <br>

## Sızma Tekniklerini Hangi Adımları İzleyerek Gerçekleştirmeliyiz?
_NOT: Red Team bakış açısıyla yazılmıştır._

1. Keşif (Recon): Sistem özelliklerini öğrenmeye çalışmak yani arka planda hangi teknolojiler kullanılıyor bunları tespit etmek.
2. Zafiyet Tespiti: Modelin hatalarını ya da zafiyetlerini bulmak.
3. Saldırı: Modeli, hatalarından yola çıkarak manipüle etmek ve gizli bilgilere erişim sağlamak.
4. Sonuç Değerlendirmesi: Modelin davranışlarını analiz edip ihlali düzeltmek.

<br> <br>

## Sızma Teknikleri
1. Prompt Injection (Prompt Enjeksiyonu)
2. Model Hallucination (Yanıltma)
3. Data Extraction (Veri Çekme)
4. Adversarial Attacks (Karşıt Saldırılar)
5. Jailbreaking (Kısıtlamaları Kaldırma)
6. Model Inversion (Model Ters Çevirme)


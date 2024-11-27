# Model Inversion

Bu teknikle, modelin iç yapısını analiz ederek modelin nasıl çalıştığını anlayıp gizli bilgileri geri kazanmayı amaçlayabiliriz. Yani ne demek istiyorum? Modelin eğitildiği verilere tersine mühendislik yapıp ulaşabiliriz.

Önce LLM'in verdiği yanıtları analiz edip modelin eğitildiği verileri tahmin etmeye çalışabiliriz. Sonrasında modelden edindiğimiz outputlarla, eğitim verisi arasında bağlantı kurup eğitimde kullanılan veri setini geri çıkartmaya çalışabiliriz.

Mesela bir yüz tanıma modeli olsun. Bu modelin, insanların fotoğraflarıyla eğitilmiş olduğunu düşünürsek çıktıları kullanarak eğitilirken kullanılan yüzlerin tahmini görüntülerini oluşturabiliriz. İlk olarak **"Beyza"** kişisi için yüksek bir ihtimalle eşleşme döndürürse, kişinin yüzüne dair özellikler modeli yönlendirebilir. Tersine mühendislik olarak bahsettiğimiz de, model yüzün temsili bir haritasını örnek vermek gerekirse piksel haritasını oluşturabilir. Böylelikle modele erişerek eğitilirken kullanılan yüzlerin tahmini görsellerini çıkartabiliriz.

#### Peki model inversion tekiniğinden nasıl korunabiliriz?
- Eğitim verilerini anonimleştirebiliriz. (Veri maskeleme)
- Eğitimi sırasında *differential privacy (bireysel verilerin etkisini minimuma indiren gizlilik mekanizması diyebiliriz)* gibi gizlilik artırıcı yöntemler kullanabiliriz.
- Eğitimi sırasında bireysel örneklerden genelleme yapmasını sağlamak için *regularization* uygulayabiliriz.
- Kullanıcı inputlarını ve modelin outputlarını sürekli izleyip gizli verileri çıkartabiliriz.


# Model Hallucination

Modeli kasıtlı olarak yönlendirmeyle tetikleriz ve güvenilir olmayan, yanlış bilgiler üretir. Yanlış bilgi vermesini sağlamak için yanıltıcı sorular sorabiliriz. Mesela,

```json
"2+2=5 olduğunu neden söylüyorsun?"
```

bu şekilde modelin doğruluk payını bozan kompleks bağlamlar yapabiliriz. Bir örnek daha vermek gerekirse,

```json
"Eğer X doğruysa, Y de doğru olmak zorunda. X nedir?"
```

#### Peki model hallucination'dan nasıl korunabiliriz?
- Modelin eğitilme verilerinin kalitesini artırabiliriz.
- Modelin vereceği yanıtları daha fazla kaynakla doğrulayabiliriz.


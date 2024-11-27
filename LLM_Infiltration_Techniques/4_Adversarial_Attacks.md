# Adversarial Attacks

Bu teknik, modele kasıtlı olarak yanıltıcı ya da zor sorular sorarak modelin hatalı yanıtlar vermesini sağlamak için kullanılır. Modele gelen inputu çok küçük bir değişiklikle manipüle eder ve modelin bu inputa aşırı tepkiler vermesini sağlar. Mesela, 

```json
"Hangi ülke Avrupa Birliği'nde değildir?"
```

gibi basit bir soru sorabiliriz. Sonrasında inputu karmaşık sembol ya da bozuk veriler manipüle edebiliriz. Mesela, 

```json
"H*ngi ülke Avrupa Birliği'nde deği_dır?"
```

bu şekilde yanıtın farklı olmasını sağlayabiliriz.


#### Peki adversarial attacks'tan nasıl korunabiliriz?
- Modelin eğitilmesi sırasında bu tür manipülasyonlar simüle edilebilir ve modele ek koruma katmanları eklenebilir.


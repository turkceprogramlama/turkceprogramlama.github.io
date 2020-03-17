---
layout: default
title: Metu Ceng Personal Blog Page
---

## Türkçe Programlama Dili Hakkında

### Nedir?

Yürütülen bu proje; bir programlama dili **Türkçe olabilir mi** hiç bilmeyenlerin ya da deneyim sahibi olmayanların 
**öğrenmesine katkı sağlayabilir mi** gibi sorulara cevap aranması amacıyla her hangi ticari bir amaç gütmeden ortaya konmuştur.

Amaç, evrensel bir dil geliştirmekten ziyade, öğretmede kullanıbilecek **pratik bir dil** olmasıdır.

Sadece dil terimlerini Türkçe'leştirmeden ziyade onları **görselleştirmeye** çalışması ile programlamayı yeni öğrenenlere faydalı bir biçimde öğreteceği düşünülmektedir. Yazım dili olarak **C/C++/Java ve Python** dillerini benimsemesi bu dillere geçişi kolaylaştırması için amaçlanmıştır.

Geliştirilmekte olan bu dille irtibatta kalmak veya katkıda bulunmak isterseniz aktif facebook sayfasını veya alakalı grubu 
<a href="https://www.facebook.com/turkceprogramlamadili">buradan</a> takip edebilirsiniz.

### Dilin söz dizimsel özellikleri nedir?

Kullanılan dilin söz dizimi(syntax) özgün olarak üretilmiştir. 
Her programlama dilinde olduğu gibi esinlendiği bir kaç güncel programlama dili mevcuttur. 
Bunlar arasında Java/C++ dil ailesi ile Python dili olduğu söylenebilir. 

Kullanılan dilde; öncelikle alışılageldik dil öğelerinin kullanılmasına dikkat edilmiştir. 
Örneğin Java dil ailesinden bileşik komutların süslü prantezde yazılması alınmış, satır sonlarının noktalı virgülle bitme zorunluluğu olmaması yönüyle de python örnek alınmış denebilir. 

Programlama öğrenen kişinin programın çalışma mantığını anlamasına yardımcı olması hedeflenen dilin özelliklerinden bir kaçını şöyle maddeler halinde sayabiliriz:

- Anlaması kolay (doğal konuşma diline yakın)
- Sadece amaca özgü olacak kadar detaylı (gereksiz detayları olmayan)
- Web üzerinde kodlanabilen ve çıktıları alınabilen/gözlemlenebilen

Bu motivasyonla; öncelikle nasıl bir dil hedeflediğimizi daha kitabi bir şekilde anlatalım:
**Dinamik tipleme (dynamically typed):** yani veri türü olmayan bir dil. Bu noktada Javascript ya da Python diline benzetildiği söyleyenebilir. Buradaki amaç, kulanıcıyı gereksiz detaylara boğmadan ve çalışma aşamasında performans kaygısı gütmeden temel programlama öğelerinin anlatmaya yönelik bir dil.
**Nesne yönelimli (object oriented):** Güncel bir çok dilde standart halini almış olmasından ve karmaşık (complex) veri yapıları gibi kavramların kodlanabilmesi ve öğretilebilmesi adına nesne yapısı ve NYP (nesne yönelimli programlama) öemli bir hal almaktadır. Ayrıca;  bildiğini üzere veri yapılarındaki her bir eleman bir nesne olarak düşünülebilir. Örneğin bağlı listede (linked list) veya çizge (graph) üzerinde her bir eleman diğer elemanlarla etkileşim halindedir ve bazı fonksiyonları yerine getirirler. Bu nedenle veri yapılarının öğesi olan her bir eleman bir nesnedir desek çok da yanlış demiş olmayız.
**Üst seviyeli (high level):** buradaki amacımız ise kıyasla daha kolay öğrenildiği ve uygulandığı ve yeni başlayanların çabucak anlaması için en uygun dil paradigması olan üst seviye programlama dili model edilmiştir.

### Dilin teknik özellikleri nedir?

Bilindiği üzere her bir programlama dili makinenin anlayabileceği makine dili üzerine soyutlamalar yaparak geliştirilir ve biraz daha detaylı bahsedersek; bu bir takım araçlar özel araçlar **söz dizim hatası** (syntax error) için **ayrıştırıcı** (parser), bunları anlamlı hale getirip makineye (bilgisayar donanımına) ileten **yorumlayıcı** (interpreter) ya da **derleyici** (compiler)- kullanılarak yapılır.

Bizim yukarıda bahsettiğimiz gereksinimlerin karşılanabilmesi için -web üzerinde kodlanabilen ve çıktıları alınabilen/gözlemlenebilen- bahsedilen araçların da web tarayıcının imkan verdiği Javascript dilinde yazılması icap etmektedir. Javascipt **istemci** (client) tarafında çalıştığından sunucu taraflı sistemlere göre daha **çevik** (dynamic) uygulamalar yapılması söz konusu olabilmektedir.

Bu projede ayrıştırıcı (parser) olarak Javascript tabanlı peg.js kütüphanesi kullanılmaktadır. Peg.js farklı dillerde yazılmış <a href="http://dinosaur.compilertools.net/yacc/">Yacc</a> (Yet Another Compiler Compiler), <a href="https://www.gnu.org/software/bison/Bison">Bison</a> ve <a href="http://www.antlr.org/">ANTLR</a> benzeri bir çeşit ayrıştırıcıdır. Sözü geçen bu ayrıştırıcılar ise sırasıyla C, C++ ve Java dillerinde yazılmıştır. Ayrıştırmadan sonra elde edilen parçaların mana kazanması, işlenmesi için ise javascript dili kullanımlamktadır.

## Geliştirici ve Katkıda Bulunanlar

Dilin aktif olarak çeşitli kısımlarıyla ilgilenen 8 geliştiricisi bulunmaktadır, ama fikir verme anlamında bir çok kişi projenin elinden tutmuştur. Aşağıda ekibimize dair bilgilere erişebilirsiniz:



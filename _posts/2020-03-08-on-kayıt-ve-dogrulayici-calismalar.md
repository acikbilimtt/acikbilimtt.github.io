---
layout: post
title: "Ön Kayıt ve Doğrulayıcı Çalışmalar"
authors: ozge_bozkurt
categories: [originals, preregistration]
tags: [originals, preregistration]
image: "ozge1.jpg"
---

Ön kayıt, yapılan keşif (exploratory) çalışmalarını ve doğrulayıcı
(confirmatory) çalışmaları birbirinden ayırt ederek daha şeffaf ve
güvenilir bir bilim anlayışı yaratmak için oluşturulmuş bir kayıt
sistemidir {% cite cos2020 lindsay2016research %}. Son yıllarda psikoloji alanında ortaya çıkan kriz,
alanyazında büyük ses uyandıran pek çok bulgunun tekrar edilemediğini
göstermiştir ({% cite open2015estimating %}; ayrıca
[tekrar edilemeyen 10 psikoloji çalışması](acikbilimtt.github.io) ve [burada olan şey rüzgârın yön değiştirmesi](acikbilimtt.github.io)). Bu
durumun pek çok sebebi olmakla birlikte en büyük sebebi, yapılan
çalışmaların daha çok keşif çalışması olarak titiz olmayan yöntemlerle
yapılmasıdır. Araştırmacıların büyük çoğunluğu tarafından kullanılan
geleneksel istatistiki yöntemler (yokluk hipotezi anlamlılık testi/null
hypothesis significance testing), keşif çalışmalarında değil doğrulayıcı
çalışmalarda daha güçlü ve doğru sonuçlar vermektedir {% cite nosek2018preregistration %}. Bu sebeple yayımlanan bilimsel araştırmaların
keşif mi yoksa doğrulayıcı çalışmalar mı olduğunun rapor edilmesi çok
büyük önem arz etmektedir. Ne yazık ki pek çok araştırmacı, yaptığı
keşif analizlerini doğrulayıcı analiz gibi rapor etmektedir.

Eğer bir araştırmacı, *Yokluk Hipotezi Anlamlılık Testi (YHAT)* gibi
yöntemlerle verisini analiz edecekse veriyi toplamadan önce belirli bir
hipotez ve analiz yöntemi belirlemeli, daha sonra bunlara riayet ederek
veri toplamalı ve önceden belirlenen şekilde veriyi analiz etmelidir.
YHAT yöntemi ancak bu şekilde istatiksel olarak güvenilir ve güçlü
sonuçlar verebilir {% cite wagenmakers2012agenda %} . Bu şekilde yapılan araştırmalara *doğrulayıcı
araştırmalar* denir. Önceden belirlenmiş analizler dışında yapılan tüm
analizler *sonraki analiz (post-hoc)* olarak rapor edilmeli ve
gerektiğinde alfa değerlerinde düzeltmeye (örn: Bonferroni Düzeltmesi)
gidilmelidir {% cite maxwell2017designing %} . Bu işlemler yapılmadığında Tip I
hata (gerçek bir etki olmadığı halde etki varmış gibi bir sonuca
ulaşmak), oranları astronomik olarak artmakta ve yapılan çalışmaların
tekrar edilebilirliği yüksek oranda düşmektedir.

Doğrulayıcı çalışmaların ilkelerine aykırı şekilde, kimi araştırmacılar
önceden belirledikleri hipotezlerini destekleyen sonuçlar
bulamadıklarında, alfa oranında düzeltmeye gitmeden veriyi çok defa test
edip ( çoklu test etme / multiple testing), çıkan anlamlı sonuçlara
bakarak yeni hipotezler üretmekte ( HARKing) ve elde edilen
bulguları doğrulayıcı sonuçlar gibi sunmaktadır. Bir başka deyişle
araştırmacı ilk önce veriye bakıp verinin önerdiği hipotezi üretmekte
{% cite maxwell2017designing %} ardından bu hipotezi doğrulamak için yeniden
veriye bakmaktadır. Bu işleme döngüsel akıl yürütme (circular reasoning)
denir {% cite nosek2018preregistration %} ve mantıksal olarak hatalı bir işlemdir. Bunlara
ek olarak kimi araştırmacılar ise istedikleri sonuçları
bulamadıklarında, sonuçları değiştirebilecek kimi katılımcıların
verisini ana veri kümesinden atarak güçsüz (underpowered) çalışmalar
yapmakta ve bu şekilde arzu ettikleri sonuçları elde etmektedirler. Bu
uygulamanın bir başka türünde ise araştırmacılar istedikleri sonuçları
elde edene kadar veri toplayıp analiz ederek yaptıkları çalışmaları
manipüle etmektedirler ({% cite lindsay2015replication %}; ayrıca  *p*-hacking). Ayrıca
araştırmacıların uç değerleri veya katılımcıları eleme konusunda kesin
kurallara sahip olmamaları ve bu konuda çok esnek uygulamalar yapmaları
da çalışmaların tekrar edilebilirliğini önemli derecede düşürmektedir
( researcher degrees of freedom).

Yukarıdaki paragrafta belirtildiği gibi pek çok araştırmacı temel
istatistiki yöntemlerin gerekliliklerine aykırı şekilde bilerek veya
bilmeyerek çeşitli uygulamalar yapmakta ve bu durum psikoloji biliminin
güvenilirliği giderek düşürmektedir. Bu uygulamaların önüne geçmek ve
psikolojinin güvenilirliğini artırmak için bir grup araştırmacı *Açık
Bilim Sistemi* (Open Science Framework) adı altında yeni bir sistem
önermişlerdir {% cite nosek2018preregistration lindsay2016research %}. Bu
sistem, araştırmacıların veri toplamaya başlamadan önce çalışma ile
ilgili aşağıda sıralanan bilgileri [ilgili web
sitesine](https://osf.io/prereg/) kaydetmesini ve çalışmaya
başlamadan önce bu bilgilerin sonradan değiştirilemez şekilde
dondurmasını gerektirmektedir.

-   Çalışmanın basit bir şekilde tanımlanması

-   Hipotezler

-   Çalışmanın türü (deneysel, korelasyonel vs.) ve deseni

-   Seçkisiz atamanın nasıl yapılacağı (örn: boş bir katılımcı kayıt
    listesi)

-   Veri toplama yöntemi (katılımcılara nasıl bir işlem uygulanacak)

-   Çalışmada kullanılacak bilgisayar programlarının kodları (örn:
    deney, analiz kodları vs.)

-   Örneklemde bulunacak katılımcı sayısı ve bu sayısının nasıl
    belirlendiği

-   Kaçıncı katılımcıda veri toplama işleminin durdurulacağı (stopping
    rule)

-   Çalışmanın bağımlı ve bağımsız değişkenleri

-   Çalışmada alınan ölçümler (örn: tepki süresi, doğru cevap oranı vs)

-   Analizlerle ilgili ayrıntılar (ortalama mı yoksa medyan analizi mi
    yapılacak vs. gibi)

-   Kullanılacak istatistiksel modeller (örn: varyans analizi, regresyon
    analizi vs.)

-   *p* değeri için kullanılacak anlamlılık değeri (örn: 0.05, 0.001
    vs.)

-   Veri dışlama kriterleri

-   Eksik veri için nasıl bir yöntem izleneceği

-   Eğer yapılacaksa ne tür keşif analizleri yapılacağı

Yukarıda sıralanan bilgiler, ön kayıt sistemine kaydedilip veriler
belirlenen işleme uygun bir şekilde toplanıp analiz edildiğinde ve
veriler diğer araştırmacılarla paylaşıldığında, elde edilen sonuçların
yeniden üretilebilirliği artacaktır. Ön kayıt işlemi sayesinde
araştırmacılar sonuçları gördükten sonra hipotez üretme (HARKing) ve *p*
değerini hackleme gibi işlemleri yapamazlar. Ek olarak araştırmacılar
yapacakları çoklu keşif analizlerinde alfa değerinde düzeltmeye gitmek
ve bu analizlerin sonraki (post-hoc) analiz olduğunu belirtmek durumunda
kalırlar. Sonuç olarak ön kayıt işlemi genel olarak bilimsel
araştırmaların güvenilirliğini ve şeffaflığını artırmakta ve bulguların
yeniden üretilebilirliğine önemli ölçüde katkı sağlamaktadır. Açık Bilim
Topluluğu Türkiye olarak şeffaf ve güvenilir çalışma yapmak isteyen tüm
araştırmacıları ön kayıt yapmaya davet ediyoruz.

# Kural Tabanlı Sınıflandırma ile Potansiyel Müşteri Getirisi Hesaplama

This repository has been prepared for the Python Programming for Data Science graduation project.

## İş Problemi

Bir oyun şirketi müşterilerinin bazı özelliklerini kullanarak seviye tabanlı (level based) yeni müşteri tanımları (persona) oluşturmak ve bu yeni müşteri tanımlarına göre segmentler oluşturup bu segmentlere göre yeni gelebilecek müşterilerin şirkete ortalama ne kadar kazandırabileceğini tahmin etmek istemektedir.

## Veri Seti Hikayesi

Persona.csv veri seti uluslararası bir oyun şirketinin sattığı ürünlerin fiyatlarını ve bu
ürünleri satın alan kullanıcıların bazı demografik bilgilerini barındırmaktadır. Veri
seti her satış işleminde oluşan kayıtlardan meydana gelmektedir. Bunun anlamı
tablo tekilleştirilmemiştir. Diğer bir ifade ile belirli demografik özelliklere sahip bir
kullanıcı birden fazla alışveriş yapmış olabilir.

## Değişkenler

- PRICE – Müşterinin harcama tutarı
- SOURCE – Müşterinin bağlandığı cihaz türü
- SEX – Müşterinin cinsiyeti
- COUNTRY – Müşterinin ülkesi
- AGE – Müşterinin yaşı

## Proje Görevleri

### Görev 1: Aşağıdaki Soruları Yanıtlayınız
Soru 1: persona.csv dosyasını okutunuz ve veri seti ile ilgili genel bilgileri gösteriniz. 
Soru 2: Kaç unique SOURCE vardır? Frekansları nedir? 
Soru 3: Kaç unique PRICE vardır? 
Soru 4: Hangi PRICE'dan kaçar tane satış gerçekleşmiş? 
Soru 5: Hangi ülkeden kaçar tane satış olmuş? 
Soru 6: Ülkelere göre satışlardan toplam ne kadar kazanılmış? 
Soru 7: SOURCE türlerine göre satış sayıları nedir? 
Soru 8: Ülkelere göre PRICE ortalamaları nedir? 
Soru 9: SOURCE'lara göre PRICE ortalamaları nedir? 
Soru 10: COUNTRY-SOURCE kırılımında PRICE ortalamaları nedir?

### Görev 2: COUNTRY, SOURCE, SEX, AGE kırılımında ortalama kazançlar nedir?
### Görev 3: Çıktıyı PRICE’a göre sıralayınız.
### Görev 4: Indekste yer alan isimleri değişken ismine çeviriniz.
### Görev 5: Age değişkenini kategorik değişkene çeviriniz ve agg_df’eekleyiniz. Age sayısal değişkenini kategorik değişkene çeviriniz.

### Görev 6: Yeni seviye tabanlı müşterileri (persona) tanımlayınız.
Yeni seviye tabanlı müşterileri (persona) tanımlayınız ve veri setine değişken olarak ekleyiniz. Yeni eklenecek değişkenin adı: customers_level_based Önceki soruda elde edeceğiniz çıktıdaki gözlemleri bir araya getirerek customers_level_based değişkenini oluşturmanız gerekmektedir.
### Görev 7: Yeni müşterileri (personaları) segmentlereayırınız.
Yeni müşterileri (Örnek: USA_ANDROID_MALE_0_18) PRICE’agöre 4 segmente ayırınız. 
Segmentleri SEGMENT isimlendirmesi ile değişken olarak agg_df’e ekleyiniz. 
Segmentleri betimleyiniz (Segmentleregöre groupbyyapıp pricemean, max, sum’larını alınız).


### Görev 8: Yeni gelen müşterileri sınıflandırıp, ne kadar gelir getirebileceklerini tahmin ediniz.
- 33 yaşında ANDROID kullanan bir Türk kadını hangi segmente aittir ve ortalama ne kadar gelir kazandırması beklenir? 
- 35 yaşında IOS kullanan bir Fransız kadını hangi segmenteaittir ve ortalama ne kadar gelir kazandırması beklenir?

```bash
git clone https://github.com/cengizcmataraci/kodluyoruzilkrepo.git
```

## Usage 

Projeyi cloneladıktan sonra Visual Studio Code programında açınız.

Linux için

```linux
cd kodluyoruzilkrepo
code .
```
## Contributing

Pull requestler kabul edilir. Büyük değişiklikler için önce neyi değiştirmek istediğiniz tartışmak için konu açınız.

## Lisans 

[MIT](https://choosealicense.com/licenses/mit/)

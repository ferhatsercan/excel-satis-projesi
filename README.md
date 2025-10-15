# 🧘‍♀️ Lumera Satış Analizi Projesi

Bu proje, Excel üzerinde gerçekçi bir satış senaryosu kullanılarak temel seviye fonksiyonların pratik edilmesi için hazırlanmıştır.

## 🧩 Kullanılan Fonksiyonlar
EĞER, VE, iç içe EĞER, BİRLEŞTİR, DÜŞEYARA, EĞERSAY, ÇOKEĞERSAY, ETOPLA, ÇOKETOPLA.

## 📊 Veri Seti
| Sayfa | Açıklama |
|--------|-----------|
| **Calisanlar** | Departman, Bölge, Maaş, Performans, Deneyim vb. |
| **Satislar** | 600+ satış kaydı, ürün, kanal, tutar bilgileri |
| **Urunler** | Ürün kodu, adı, birim fiyat |

## 🧠 Örnek Uygulama
> “Maaşı 15000’den fazla ve deneyimi 5 yıldan fazla olanları Kıdemli Satış olarak sınıflandır.”

```excel
=EĞER(VE(DÜŞEYARA(B3;Calisanlar!$A$1:$I$36;6;0)="Yüksek";DÜŞEYARA(B3;Calisanlar!$A$1:$I$36;7;0)>5);"Kıdemli Satış";"Normal Satış")

Bu proje eğitimsel ve kişisel kullanım içindir.
Veri seti tamamen kurgusaldır; herhangi bir gerçek kişi veya kurumlarla ilişkisi yoktur.

🌐 Sosyal Medya ve İletişim

Medium:	medium.com/@ferhatsercan

Instagram:	instagram.com/ferhatsercann

LinkedIn:	linkedin.com/in/ferhatsercan

GitHub:	github.com/ferhatsercan
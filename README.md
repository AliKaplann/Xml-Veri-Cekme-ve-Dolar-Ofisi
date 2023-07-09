# Xml-Veri-Cekme-ve-Dolar-Ofisi
Veri çekilen site: https://www.tcmb.gov.tr/kurlar/today.xml

Tabloyu oluşturmak için aşağıdaki SQL sorgusunu kullanabilirsiniz:
```
CREATE TABLE DovizTablosu (
    Tarih DATETIME DEFAULT CURRENT_TIMESTAMP,
    TLDeger DECIMAL(18, 2),
    DolarDeger DECIMAL(18, 2),
    EuroDeger DECIMAL(18, 2)
);
```
![Ekran görüntüsü 2023-07-09 231346](https://github.com/AliKaplann/Xml-Veri-Cekme-ve-Dolar-Ofisi/assets/103608939/8a43000f-a79c-443f-91cf-4bbd73030611)

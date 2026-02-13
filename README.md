# Tabular Data Analizi-Marmara Bolgesi
Marmara bölgesinden çekilen deprem veri setinin analizi yapılması amaçlandı.

* Veri Seti
     Veri seti kandilli rasathanesinden Marmara Bölgesi'ni kapsayacak şekilde sınırlandırılarak çekildi. Veriler 01.01.2000 - 31.10.2025 tarihleri arasında sınırlandırıldı ve sadece deprem veriileri kullanıldı.
Veri aşırı gürültü, dengesizlik, boyutun laneti ve aşırı uyum risklerini barındırmaktadır. Lineer bir veri değildir.

Projede veri seti ile 
- Deprem Risk Haritası
    * Projede Risk haritasının oluşturulmasında depremler nokta ve harita ile görselleştirilmiştir. Harita görseli için GeoPandas miniconda kurulumu yapılmıştır. (Kullanımı sadece harita içindir.)
      - miniconda indirildi .exe çalıştırıldı
      - anaconda prompt uygulaması üzerinden
      - conda create -n ...(isim)
      - conda activate ....   (kodları ile bir base oluşturuldu.)
      - conda create -n .... python numpy pandas (kütüphaneler yüklendi)
  
- Deprem Kümele işlemleri yapılacaktır.

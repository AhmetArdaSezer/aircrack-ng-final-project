# aircrack-ng-final-project
Monitor mod ile gizli SSID keşfi ve deauth saldırısı


## Takım Üyeleri
- Ahmet Arda Sezer 2420191025


## Açıklama
Bu projede Aircrack-ng araç takımı kullanılarak, monitor mod ile gizli SSID'lerin keşfi ve deauthentication (deauth) saldırısı gerçekleştirilmiştir.

## Hedefler
- Monitor mod kullanarak ağ trafiğini izlemek
- Gizli SSID yayınlarını tespit etmek
- Deauth saldırısı ile bağlantı kesme işlemi uygulamak
- Kali Linux ortamında pratik yapmak

## Bağlantılar
- [Aircrack-ng Resmi Sitesi](https://www.aircrack-ng.org/)
## 🔍 Giriş

Günümüz dünyasında kablosuz ağlar, hayatımızın vazgeçilmez bir parçası haline gelmiştir. Evlerimizden iş yerlerimize, kafelerden havaalanlarına kadar her yerde kablosuz ağlara erişim sağlamaktayız. Bu yaygın kullanım, beraberinde bazı güvenlik risklerini de getirmektedir. Kablosuz ağ güvenliği, bu riskleri minimize etmek ve ağlarımızı yetkisiz erişimden korumak için kritik öneme sahiptir.

Gizli SSID'ler (Service Set Identifier), ağ adının yayınlanmadığı ve dolayısıyla standart Wi-Fi tarayıcılar tarafından doğrudan görülemeyen kablosuz ağlardır. Bu, bazen güvenlik önlemi olarak düşünülse de, aslında doğru araçlarla kolayca keşfedilebilirler. Deauthentication (deauth) saldırısı ise, kablosuz ağa bağlı olan istemcileri ağdan düşürmeyi amaçlayan bir tür hizmet reddi (DoS) saldırısıdır. Bu saldırı, ağın işleyişini bozarak veya başka saldırılar için zemin hazırlayarak kullanılabilir.

**Aircrack-ng**, kablosuz ağ güvenliği denetimlerinde kullanılan güçlü ve açık kaynaklı bir araç takımıdır. İçerisinde ağ trafiğini yakalama, şifre kırma, deauthentication saldırıları gerçekleştirme gibi birçok işlevi barındırır. Bu proje, Aircrack-ng'nin bu özelliklerinden faydalanarak gizli SSID keşfi ve deauthentication saldırısı kavramlarını uygulamalı olarak ele alacaktır.

---

## 🎯 Proje Hedefleri

- Kablosuz ağların çalışma prensiplerini ve güvenlik açıklarını anlamak  
- Aircrack-ng araç takımının kurulumunu ve temel kullanımını öğrenmek  
- Kablosuz ağ adaptörünü monitor moda geçirmeyi başarmak  
- Pasif ve aktif yöntemlerle gizli SSID'lerin nasıl keşfedildiğini kavramak ve uygulamak  
- Deauthentication saldırısının nasıl gerçekleştirildiğini anlamak ve uygulamak  
- Gerçekleştirilen saldırıların yasal ve etik boyutları hakkında farkındalık oluşturmak  

---

## 🧩 Proje Kapsamı

Bu proje kapsamında aşağıdaki adımlar gerçekleştirilecektir:

1. **Gerekli Donanım ve Yazılımın Hazırlanması**  
   - Uyumlu bir kablosuz ağ adaptörü ve Kali Linux kurulumu

2. **Aircrack-ng Kurulumu ve Yapılandırması**  
   - Araç takımının kurulumu ve temel ayarlar

3. **Monitor Mod Aktivasyonu**  
   - Ağ adaptörünün monitor moda alınması

4. **Gizli SSID Keşfi**  
   - Pasif dinleme (probe request/response)  
   - Aktif yöntem (deauth saldırısı ile)

5. **Deauthentication Saldırısı**  
   - Saldırı mantığı ve uygulaması

6. **Bulguların Analizi ve Değerlendirme**

7. **Etik ve Yasal Boyutlar**  
   - Bu tür saldırıların hukuki sonuçları ve etik sorumluluklar

---

> Bu proje, kablosuz ağ güvenliği konusunda hem teorik bilgi sağlamayı hem de pratik uygulama becerilerini geliştirmeyi amaçlamaktadır. **Bu tür saldırılar yalnızca yasal ve etik sınırlar içerisinde, izin alınmış ağlar üzerinde gerçekleştirilmelidir.**

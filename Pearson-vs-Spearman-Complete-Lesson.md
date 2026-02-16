# Pearson vs Spearman: Tam Ders

## 1. Giriş  
Bu ders, Pearson ve Spearman korelasyon katsayılarını ayrıntılı olarak inceleyecek. İki değişken arasındaki ilişkiyi ölçmek için yaygın olarak kullanılan bu iki yöntem arasındaki farkları ve benzerlikleri anlayacağız.

## 2. Hücre 1: Pearson Korelasyon Katsayısı  
**Tanım:** Pearson korelasyon katsayısı, iki sürekli değişken arasında doğrusal bir ilişkiyi ölçer.  
**Formül:** 
\[ r = \frac{n(\sum xy) - (\sum x)(\sum y)}{\sqrt{[n\sum x^2 - (\sum x)^2][n\sum y^2 - (\sum y)^2]}} \]  
**Örnek:** Bir anketteki iki soru arasındaki ilişkiyi analiz ederek cevapların doğrusal olarak nasıl ilişkili olduğunu belirleyebilirsiniz.

## 3. Hücre 2: Spearman Korelasyon Katsayısı  
**Tanım:** Spearman korelasyon katsayısı, iki sıralı değişken arasındaki ilişkiyi ölçer. 
**Formül:** 
\[ r_s = 1 - \frac{6 \sum d_i^2}{n(n^2 - 1)} \]  
**Örnek:** Öğrencilerin notları ve katıldıkları saatler arasındaki ilişkiyi incelemek gibi sıralı verileri kullanarak çalışır.

## 4. Hücre 3: Temel Farklar  
| Özellik           | Pearson                     | Spearman                       |
|-------------------|----------------------------|-----------------------------------|
| Kullanım Alanı    | Sürekli Veriler            | Sıralı Veriler                   |
| Dağılım Gereksinimi| Normal Dağılım            | Normal Dağılım Yok                |
| Hesaplama         | Doğrusal ile ilişki        | Sıralama ile ilişki                |

## 5. Hücre 4: Uygulama No. 1  
**Durum:** Bir anket sonucu iki değişkenin Pearson katsayısını hesaplayalım.  
**Veri:**  \[ X: [1, 2, 3, 4, 5] \] ve \[ Y: [2, 3, 5, 7, 8] \]  
**Hesap:** 
1. Adım: Verileri topla  
2. Adım: Formülü uygula  
3. Adım: Sonucu çıkar  

## 6. Hücre 5: Uygulama No. 2  
**Durum:** Öğrenci başarı notları ile ders çalışma saatleri üzerine bir Spearman analizi yapalım. 
**Veri:**  \[ Notlar: [90, 80, 70, 60, 50] \] ve \[ Saat: [1, 2, 3, 4, 5] \]  
**Hesap:** Spearman katsayısını bulmak için verileri sıralayın ve formülü uygulayın.

## 7. Hücre 6: Önerilen Kaynaklar  
- [Korelasyon Analizi](https://www.scribbr.com/statistics/correlation/)  
- [Korelasyon Türleri](https://towardsdatascience.com/types-of-correlation-4cd7795a4b3b)  
- [Pratik Uygulamalar](https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data/correlation-coefficient/a/correlation-coefficient-intro)

## 8. Hücre 7: Pratik Rehber  
1. Vaka çalışmaları ile başlayın  
2. Temel kavramları açıklayın  
3. Uygulamalı örnekler sunun  
4. Sonuçları tartışın  

## 9. Hücre 8: Sonuç  
Pearson ve Spearman arasındaki ilişkiyi anlayarak iki veri kümesi arasındaki ilişkiyi daha iyi analiz edebiliriz. Bu iki teknik, farklı durumlar için farklı kullanımlar sunar ve verilerinizin doğasına bağlı olarak birini veya diğerini tercih edebilirsiniz.  

---
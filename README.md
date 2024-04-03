# Gradient_Descent
## Giriş
Bu README dosyası, basit bir gradient descent algoritmasının Python uygulamasını içerir. Gradient descent, bir optimizasyon algoritmasıdır ve genellikle makine öğrenmesi ve yapay zeka gibi alanlarda model eğitimi sırasında kullanılır. Bu dosya, algoritmanın kullanımını, veri setiyle nasıl çalıştığını ve elde edilen sonuçları içermektedir.
## Veri ve Metot Açıklaması
Bu Python scripti, verilen bir veri seti üzerinde gradient descent algoritmasını uygular. Adım adım açıklama aşağıda bulunmaktadır:
### 1. Veri Yükleme:
"Salary_dataset.csv" dosyası, çalışma için kullanılacak veri setini içermelidir. Bu dosya, deneydeki örneklerin yıllık deneyimlerine ve bunların karşılık gelen maaşlarına sahip olduğu bir tablo içermelidir.
### 2. Giriş Değişkenleri ve Hedef değişkeninin Tanımlanması
"YearsExperience" sütunu giriş değişkenini (X) oluştururken, Salary sütunu hedef değişkeni (y) oluşturur.
### 3. Ağırlık Vektörünün Başlatılması:
Ağırlık vektörü (w), rastgele değerlerle başlatılır. Bu, gradient descent algoritmasının başlangıç noktasını belirler.
### 4. Gradient Descent Algoritması:
gradient_descent fonksiyonu, verilen öğrenme oranı ve iterasyon sayısıyla gradient descent algoritmasını uygular. Her iterasyonda, ağırlık vektörü güncellenir ve hata azaltılmaya çalışılır.
## Sonuçlar
Gradient descent algoritması, veri seti üzerinde belirli bir öğrenme oranı ve iterasyon sayısı için uygulandıktan sonra ağırlık vektörü "w_final" olarak verilir. Bu ağırlık vektörü, veri setindeki giriş değişkenlerini hedef değişkene en iyi şekilde bağlayan doğrusal bir modelin katsayılarını temsil eder.
#### Örnek Sonuç:
![Ekran görüntüsü 2024-04-04 020812](https://github.com/KenanSenturk/Gradient_Descent/assets/164398413/41122e9e-6f76-4d44-8739-00111abee99c)









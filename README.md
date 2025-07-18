<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
</head>
<body>

  <h1>📘 Öğrenci Depresyon Tahmini - Lojistik Regresyon Modeli</h1>

  <h2>📌 Proje Amacı</h2>
  <p>
    Bu proje, bir öğrenci veri seti üzerinde <strong>Lojistik Regresyon</strong> algoritması kullanarak öğrencilerin depresyonda olup olmadığını tahmin etmeyi amaçlar. Veri seti, öğrencilerin demografik, akademik ve psikolojik özelliklerini içerir.
  </p>

  <h2>📊 Kullanılan Teknolojiler</h2>
  <ul>
    <li>Python</li>
    <li>Pandas, NumPy</li>
    <li>Matplotlib, Seaborn</li>
    <li>Scikit-Learn (LogisticRegression, Train-Test Split, Confusion Matrix, Accuracy Score)</li>
  </ul>

  <h2>🗂️ Proje Adımları</h2>
  <ol>
    <li><strong>Veri Yükleme:</strong> CSV formatındaki öğrenci veri seti içe aktarılır.</li>
    <li><strong>Ön İşleme:</strong> Gereksiz sütunlar kaldırılır, eksik veriler kontrol edilir.</li>
    <li><strong>Veri Keşfi:</strong> Veri seti hakkında temel istatistiksel bilgiler alınır, değişkenler analiz edilir ve görselleştirilir.</li>
    <li><strong>Korelasyon Analizi:</strong> Bağımsız değişkenler ile hedef değişken arasındaki ilişkiler incelenir.</li>
    <li><strong>Modelleme:</strong> Lojistik Regresyon modeli kurulur. Veri eğitim ve test setlerine bölünür.</li>
    <li><strong>Değerlendirme:</strong> Model doğruluğu, karışıklık matrisi, ROC eğrisi ve sınıflandırma raporu ile değerlendirilir.</li>
  </ol>

  <h2>⚙️ Nasıl Çalıştırılır?</h2>
  <ol>
    <li><strong>Gerekli Kütüphaneleri Kurun:</strong><br>
      <code>pip install pandas matplotlib seaborn scikit-learn</code>
    </li>
    <li><strong>Defteri Açın:</strong> Jupyter Notebook veya Google Colab ile proje dosyasını çalıştırın.</li>
    <li><strong>Veri Setini Ekleyin:</strong> <code>student_depression_dataset.csv</code> dosyasının notbook ile aynı klasörde olduğundan emin olun.</li>
    <li><strong>Hücreleri Çalıştırın:</strong> Adım adım ilerleyerek veriyi analiz edin, lojistik regresyon modelini eğitin ve çıktıları yorumlayın.</li>
  </ol>

  <h2>✅ Beklenen Çıktılar</h2>
  <ul>
    <li>Öğrencilerin depresyonda olma durumu tahmin edilir.</li>
    <li>Modelin doğruluk skoru hesaplanır.</li>
    <li>Karışıklık matrisi ve ROC eğrisi çizilir.</li>
    <li>Sınıflandırma raporu ile model başarısı detaylandırılır.</li>
    <li>Veri keşfi ve görselleştirmeler yapılır.</li>
  </ul>
  

   <h2>📝 Modellerin Sözel Karşılaştırması</h2>
  <p>
    Bu projede hem Lojistik Regresyon hem de K-En Yakın Komşu (KNN) algoritması uygulanarak öğrencilerin depresyonda olma durumu tahmin edilmiştir. 
    Elde edilen örnek değerlere göre, Lojistik Regresyon modeli KNN modeline kıyasla biraz daha yüksek doğruluk, hassasiyet, geri çağırma ve F1 skoruna sahiptir. 
    Bu da Lojistik Regresyon’un bu veri setinde KNN’ye göre daha iyi performans gösterdiğini göstermektedir.
    Ancak KNN de yakın sonuçlar vermiştir ve farklı parametre ayarlarıyla benzer başarı düzeyine ulaşabilir. 
    Sonuç olarak, Lojistik Regresyon bu proje özelinde tercih edilebilir bir modeldir.
  </p>


</body>
</html>

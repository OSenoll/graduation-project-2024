# Sahte Haber Analizi ve Tespiti

Sahte Haber Tespiti, kullanıcıların spor haberlerinin doğruluğunu analiz etmelerini sağlayan yenilikçi bir platformdur. Makine öğrenimi ve doğal dil işleme (NLP) tekniklerini bir araya getiren bu uygulama, spor haberlerinin doğruluğunu doğrularken eğitici ve güvenilir bir deneyim sunar.  

## Özellikler  

### Haber Doğruluk Analizi  
- **Haber Analizi:** Kullanıcılar, bir spor haberinin bağlantısını paylaşarak bu haberin doğru ya da sahte olup olmadığını öğrenebilir.  
- **Doğruluk Skoru:** Sistem, haberin doğruluk derecesini belirten bir puan ve açıklama sunar.  

### Canlı Veri Doğrulama  
- **Gerçek Zamanlı Veri Analizi:** Twitter gibi sosyal medya platformlarından alınan haber bağlantıları analiz edilebilir.  
- **Anlık Geri Bildirim:** Kullanıcılara analiz sonuçları anında iletilir.  

### Raporlama ve İstatistikler  
- **Kullanıcı İstatistikleri:** Kullanıcılar, analiz ettikleri haberlerin geçmişini ve genel başarı oranlarını görüntüleyebilir.  
- **Topluluk Verileri:** Sahte haberlerin genel eğilimleri ve tespit oranları topluluk düzeyinde sunulur.  

## Grup Üyeleri  

| İsim               | Rol          |  
|--------------------|--------------|  
| Alimcan Çakır      | Geliştirici  |  
| Erhan Tarhana      | Geliştirici  |  
| Ömer Faruk Şenol   | Geliştirici  |  

## Hedef Kitle  
Sahte Haber Tespiti, geniş bir kullanıcı kitlesine hitap etmektedir ve özellikle şu gruplar için idealdir:  
- **Spor Meraklıları:** Güvenilir kaynaklardan doğru spor haberlerini takip etmek isteyenler.  
- **Araştırmacılar ve Akademisyenler:** Sahte haberlerin yayılımını inceleyen ve bu konuda çalışmalar yapan kişiler.  
- **Sosyal Medya Kullanıcıları:** Karşılaştıkları haberlerin doğruluğunu kolayca teyit etmek isteyenler.  
- **Gençler ve Öğrenciler:** Hem spor hem de teknolojiye ilgi duyan, eğitici ve interaktif bir deneyim arayanlar.  

## Neden Sahte Haber Tespiti?  
Sahte Haber Tespiti, kullanıcıların yanlış bilgilerin yayılmasını engellemesine yardımcı olurken bilgi güvenliği ve doğruluğunu ön planda tutar. Spor medyasına olan güveni artırmak için güvenilir bir araç sunmayı amaçlamaktadır.  

---

<details>
  <summary> <h1> Sprint 1: Planlama ve Başlangıç </h1></summary>

### Sprint Hedefi  
Projenin temel altyapısının planlanması ve kullanılacak araçların belirlenmesi. Takım üyeleri arasındaki iş birliğini güçlendirmek için temel Scrum uygulamalarının öğrenilmesi ve Trello kullanımı üzerinde anlaşılması.  

### Sprint 1'de Tamamlanan İşler  
1. **Trello Kullanımı Kararlaştırıldı:**  
   - Takımın ilerlemesini takip etmek ve görev dağılımını organize etmek için Trello kullanımına karar verildi.  
   - "To Do," "In Progress" ve "Done" sütunları oluşturularak proje board'u hazırlandı.  

2. **Scrum Süreçlerinin Tanımlanması:**  
   - Sprint süresi 1 hafta olarak belirlendi.  
   - Günlük kısa toplantılar (Daily Scrum) yapılacağı kararlaştırıldı.  
   - Sprint sonlarında retrospektif toplantıların düzenlenmesi planlandı.  

3. **Kullanılacak Araçların Belirlenmesi:**  
   - **Google Colab:** Kod geliştirme ve model eğitimi için.  
   - **VS Code:** Proje kodlarının düzenlenmesi için.  
   - **Pandas, Matplotlib, NumPy, Scikit-learn:** Veri işleme ve model geliştirme için.  
   - **Trello:** Proje yönetimi ve görev dağılımı için.  

4. **Proje Yapısının Planlanması:**  
   - Sahte haber analizinde kullanılacak ana özelliklerin belirlenmesi.  
   - Veri setlerinin nereden temin edileceğine dair fikirlerin paylaşılması (Kaggle ve sosyal medya veri tarama).  

5. **İlk Backlog Oluşturuldu:**  
   - Sprint 2'de yapılacak işler için backlog maddeleri hazırlandı.  
   - Veri setlerinin incelenmesi ve seçimi, ilk veri işleme adımları, temel model tasarımına başlanması gibi işler belirlendi.

   ### Sprint 1 Retrospektifi ve Düzeltmeler
#### 1. Neler İyi Gitti?
- Tüm takım Trello kullanımına kolayca adapte oldu.
- Sprint hedefleri net bir şekilde tanımlandı ve çoğu tamamlandı.

#### 2. İyileştirilmesi Gerekenler
- Günlük toplantıların daha disiplinli bir şekilde yapılması kararlaştırıldı.
- Görev dağılımında daha fazla netlik sağlanması önerildi.

#### 3. Kararlaştırılan Eylemler
- Günlük toplantıları her gün saat 10:00'da yapılacak.
- Sprint sonlarında, bireysel katkılar üzerine daha detaylı geri bildirim verilecek.

</details>


<details>
  <summary> <h1> Sprint 2: Veri Hazırlık ve Model Tasarımı </h1></summary>
  
### Sprint Hedefi
Veri setlerinin hazırlanması, ön işleme adımlarının tamamlanması ve NLP modelinin temel yapısının oluşturulması. Ayrıca takım içi iletişim ve çalışma akışını geliştirmek için önceki sprintten çıkan derslerin uygulanması.

### Sprint 2'de Tamamlanan İşler
#### 1. Veri Setlerinin Temizlenmesi ve Ön İşleme
- Veri setlerindeki eksik ve hatalı veriler temizlendi.
- Doğruluk analizi için gerekli olan özellikler belirlendi ve öznitelik mühendisliği uygulandı.
- Tekrarlayan veya anlamsız veriler ayıklandı ve veriler normalize edildi.

#### 2. NLP Modelinin Temel Yapısının Oluşturulması
- Haber metinlerinin özelliklerini analiz etmek için öncelikle Tokenization ve Lemmatization adımları entegre edildi.
- Bag-of-Words (BoW) ve TF-IDF gibi temel metin temsili teknikleri denendi.
- Doğruluk ve performans değerlendirmesi için çoklu model yaklaşımları için altyapı hazırlandı.

#### 3. Prototip Testlerinin Başlatılması
- Hazırlanan veriler üzerinde NLP modeliyle ilk testler gerçekleştirildi.
- Basit logistic regression ve naive bayes modelleri ile ilk test sonuçları alındı.
- Model için hiperparametre ayarına başlandı.

#### 4. Topluluk Verileri Çıkarımı
- Spor haberlerinin sosyal medyada yayılımına dair özellikler çıkarıldı.
- Bu veriler, model eğitimi için kullanılabilir hale getirildi.

   ### Sprint 2 Retrospektifi ve Düzeltmeler
#### 1. Neler İyi Gitti?
- Veri setlerinin temizlenmesi ve ön işleme süreçleri planlandığı gibi ilerledi, bu sayede model eğitimi için güçlü bir temel oluşturuldu.
- NLP modelinin temel yapısı başarıyla hazırlandı ve ilk prototip testleri gerçekleştirilerek başlangıç sonuçları elde edildi.

#### 2. İyileştirilmesi Gerekenler
- Veriler üzerinde yapılan işlemlerin detaylı bir şekilde belgelenmesinin sonraki sprintler için faydalı olacağı görüldü.
- İlk test sonuçlarının daha kapsamlı analiz edilmesi gerektiği fark edildi.

</details>

<details>
  <summary> <h1>Sprint 3: NLP Model Tasarımı ve Derinleştirilmesi </h1></summary>    

### Sprint Hedefi

NLP modelinin temel yapısını oluşturarak ilk çalışabilir versiyonu hazırlamak. Model tasarımının ileri seviyede uygulanması için altyapıyı hazır hale getirmek.

### Sprint 3'te Tamamlanan İşler

#### 1. Tokenization ve Metin Ön İşleme

- Model için metinlerin parçalanması sağlandı (Word ve Sentence tokenization).
- Stopword'ler filtrelenerek, anlamsız kelimeler metinlerden çıkarıldı.
- Lemmatization ve stemming işlemleri eklenerek, kelimeler kök formlarına dönüştürüldü.

#### 2. Veri Temsili Tekniklerinin Derinleştirilmesi

- TF-IDF özellik çıkarımında hiperparametre optimizasyonu yapıldı.
- Embedding teknikleri (Word2Vec ve GloVe) incelendi ve altyapıya dahil edildi.
- Bu temsil teknikleri arasında bağlılık analizi yapılarak en verimli teknik seçildi.

#### 3. Model Tasarımında İlk Adımlar

- Logistic Regression ve Support Vector Machines (SVM) modelleri ile ilk testler gerçekleştirildi.
- Hangi modelin daha fazla hassasiyet sağladığına dair ön analizler tamamlandı.
- Baseline model oluşturularak daha ileri tekniklerin bu modelle karşılaştırılması planlandı.

#### 4. Performans ve Doğruluk Analizleri

- Modelin çalışabilirliği için ilk performans değerlendirmeleri yapıldı.
- Precision, recall ve F1-score gibi metrikler hesaplandı ve optimize edilmeye başlandı.

  ### Sprint 3 Retrospektifi ve Düzeltmeler
#### 1. İyileştirilmesi Gerekenler
- Başlangıçta spor haberlerine odaklanılması hedeflenmiş, ancak uygun veri seti bulunamadığı için genel haber veri setleri kullanılmıştır. Bu veri setleriyle temel modeller geliştirilmiş, gelecekte spor haberlerine özel veri seti oluşturulması planlanmaktadır.
- Görev dağılımında daha fazla netlik sağlanması önerildi.
  
</details>






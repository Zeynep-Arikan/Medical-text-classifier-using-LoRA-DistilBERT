🧠 Proje Özeti
Bu proje, LoRA (Low-Rank Adaptation) tekniği ile optimize edilmiş DistilBERT modeli kullanarak tıbbi raporların sınıflandırılması üzerine odaklanmaktadır. Projede, her bir tıbbi raporun hangi uzmanlık alanına ait olduğunu (örneğin "Cardiology", "Radiology", "Surgery" vb.) otomatik olarak tahmin etmek amaçlanmıştır.

🎯 Amaç
Transformer tabanlı modellerin düşük donanım maliyetiyle nasıl verimli şekilde ince ayar (fine-tuning) yapılabileceğini göstermek

LoRA yöntemiyle sadece %1'lik parametre setini eğiterek yüksek doğrulukta sonuçlar elde etmek

Tıbbi doğal dil işleme (Clinical NLP) alanında sınıflandırma başarısını artırmak

# Kullanılan Teknolojiler

| Teknoloji                     | Açıklama                            |
| ----------------------------- | ----------------------------------- |
| **Python**                    | Temel programlama dili              |
| **Hugging Face Transformers** | Model ve tokenizer altyapısı        |
| **PEFT (LoRA)**               | Parametre verimli fine-tuning       |
| **scikit-learn**              | Etiketleme ve metrik hesaplama      |
| **Plotly**                    | Eğitim sürecinin görselleştirilmesi |
| **Pandas / Datasets**         | Veri işleme ve hazırlık             |

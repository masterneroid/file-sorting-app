📄 AI-Powered Document Analyzer (Yapay Zeka Destekli Doküman Analizci)Bu uygulama; PDF, Word, Excel, PowerPoint ve metin dosyalarınızı içeriklerine göre analiz eden, yapay zeka desteğiyle kategorize eden ve düzenleyen masaüstü bir araçtır. Karmaşık doküman klasörlerinizi tek tıkla düzenli hale getirmenize yardımcı olur.
✨ Öne Çıkan Özellikler
🔍 Çoklu Format Desteği: PDF, DOCX, PPTX, XLSX, XLS, TXT ve MD formatlarından metin çıkarımı.
🤖 Çift Katmanlı Analiz: * Anahtar Kelime Analizi: Hızlı ve hafif sınıflandırma.AI (BART) Analizi: Derin öğrenme tabanlı içerik anlama (facebook/bart-large-mnli).
📂 Otomatik Organizasyon: Dosyaları içeriklerine göre otomatik olarak klasörlere ayırır.
📊 Metadata Çıkarımı: Dosya boyutu, karakter/kelime sayısı ve anahtar kelime tespiti.
🎨 Modern Arayüz: PySide6 ile geliştirilmiş, açık ve koyu tema destekli kullanıcı arayüzü.
⚙️ Sistem Optimizasyonu: psutil ile kaynak kullanımı denetimi.
🚀 KurulumProjeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:
Depoyu klonlayın:Bash
git clone https://github.com/kullanici-adiniz/proje-adiniz.git
cd proje-adiniz
Gerekli kütüphaneleri yükleyin:
Bashpip install PySide6 pypdf python-docx python-pptx openpyxl xlrd transformers torch psutil
Uygulamayı çalıştırın:
Bash
python main.py
Not: AI modelini ilk kez çalıştırdığınızda, yaklaşık 1.5 GB boyutundaki model dosyası otomatik olarak indirilecektir.
Kütüphane,Kullanım Amacı
PySide6,GUI (Kullanıcı Arayüzü)
Transformers,Zero-shot Classification (AI Analizi)
PyPDF,PDF İçerik Okuma
Openpyxl,Modern Excel Dosyaları
Python-Docx,Word Belgesi İşleme


“This project was originally developed by Semih Çelik (2026).”

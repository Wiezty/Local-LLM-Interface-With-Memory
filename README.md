# 🤖 Ollama & Llama 3 Tabanlı Kalıcı Hafızalı Yapay Zeka Arayüzü

> 📅 **Proje Geçmişi ve Yayın Notu:**  
> Bu proje, **lise dönemimde (geçmiş yıllarda)** yerel yapay zeka modelleri üzerine yaptığım bireysel çalışmalar ve denemeler sırasında geliştirilmiştir. Geliştirme süreci geçmişte tamamlanmış olan bu çalışma, portfolyomun bir parçası olarak **günümüz itibarıyla** arşivden çıkarılarak GitHub üzerinde ilk kez yayına alınmıştır.

---

## 🔥 Yapay Zeka Tarafından Optimize Edilmiş Kod Yapısı
Projenin backend ve hafıza mimarisi, geliştirme aşamasındayken yapay zeka (AI) destekli kod optimizasyon araçları kullanılarak düzenlenmiştir. Yapılan geliştirmeler şunlardır:
- **Gelişmiş Okunabilirlik:** Karmaşık kod blokları, fonksiyonların ne işe yaradığını ve veri akışını netleştiren profesyonel **yorum satırları** ile donatılmıştır.
- **Hafıza Mimarisi Düzenlemesi:** Uygulama kapatılsa veya kod yeniden başlatılsa dahi geçmiş sohbet bağlamını kaybetmeyen stabil bir session/oturum yönetimi entegre edilmiştir.
- **Temiz Kod Standartları:** Değişken isimleri ve API istek yapıları, yapay zekanın önerileri doğrultusunda en performanslı hale getirilmiştir.

---

## 🔒 Kaynak Kodu Güvenliği ve Erişim
Projenin kaynak kodları, mimari özgünlük, telif hakları ve algoritma güvenliği nedeniyle ana dizindeki `ai_memory_app.rar` dosyası içinde **şifreli ve kilitli olarak** saklanmaktadır. 

⚠️ **Önemli Not:** Arşiv şifresi, projeyi kopyalamaya veya izinsiz değiştirmeye karşı koruma amacıyla **bu alanda bilerek belirtilmemiştir.** Kodu bireysel olarak incelemek veya test etmek isteyenler şifre için benimle iletişime geçebilirler.

---

## 🛠️ Kurulum ve Sistemi Çalıştırma Rehberi

Bu programın bilgisayarınızda çalışabilmesi için sırasıyla şu 3 adımı tamamlamanız gerekmektedir:

### 1. Adım: Ollama ve Llama 3 Kurulumu
Program, yapay zeka beynini yerel sisteminizden alır. Bu yüzden:
1. [Ollama Resmi Web Sitesi](https://ollama.com) üzerinden işletim sisteminize uygun sürümü indirip kurun.
2. Bilgisayarınızın terminalini (CMD veya PowerShell) açın ve yerel kütüphanenize Llama 3 modelini indirmek için şu komutu çalıştırın:
   ```bash
   ollama run llama3
   ```
   *(Model indirme işlemi tamamlandıktan sonra terminali kapatabilirsiniz, Ollama arka planda hazır bekleyecektir.)*

### 2. Adım: Python Kütüphanelerinin Yüklenmesi
Uygulamanın çalışması için gerekli olan bağımlılıkları yüklemek adına, ana dizinde bir terminal açarak `requirements.txt` dosyasını çalıştırın:
```bash
pip install -r requirements.txt
```

### 3. Adım: Programın Şifresini Açma ve Çalıştırma
Şifreyi kullanarak `ai_memory_app.rar` dosyasını bir klasöre çıkarın ve ana Python dosyasını çalıştırarak yerel web arayüzünü ayağa kaldırın.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 🤖 Ollama & Llama 3 Based Local LLM Web UI with Persistent Memory

> 📅 **Project Background & Release Note:**  
> This project was individually developed during my **high school years** as part of my personal research and experiments on local Large Language Models (LLMs). Having completed the development phase in the past, this work has now been retrieved from my personal archives and published on GitHub for the first time as a core element of my academic portfolio.

---

## 🔥 AI-Optimized Codebase & Architecture
The backend architecture and the memory management system were optimized using AI-assisted code refinement tools during the development phase. The key improvements include:
- **Enhanced Readability:** Complex code blocks have been documented with professional **inline comments** to clarify the data flow and function logic.
- **Persistent Context Management:** Integrated a stable session and state management system that prevents the model from losing chat history or context, even when the application or the code is restarted.
- **Clean Code Standards:** Variable names and API request structures have been refactored based on AI recommendations for maximum performance.

---

## 🔒 Source Code Security & Access Control
Due to architectural originality, intellectual property, and algorithmic security, the core Python source codes are stored securely inside a **password-protected** `ai_memory_app.rar` archive.

⚠️ **Important Note:** The archive password **is intentionally omitted from this repository** for security and anti-plagiarism purposes. Those who wish to review, test, or evaluate the codebase for academic purposes may contact me directly to request the password.

---

## 🛠️ Installation & System Setup Guide

To run this application successfully on your local machine, please follow these 3 steps in order:

### Step 1: Install Ollama and Llama 3
The application relies on your local hardware to run the AI model. Therefore:
1. Download and install the appropriate version for your OS from the [Official Ollama Website](https://ollama.com).
2. Open your terminal (CMD or PowerShell) and run the following command to download the Llama 3 model into your local library:
   ```bash
   ollama run llama3
   ```
   *(Once the download is complete, you can close the terminal; Ollama will remain ready in the background.)*

### Step 2: Install Python Dependencies
Open a terminal in the root directory of the project and run the `requirements.txt` file to install the required libraries:
```bash
pip install -r requirements.txt
```

### Step 3: Extract the Archive and Run
Extract the `ai_memory_app.rar` archive using the provided password, and execute the main Python file to launch the local Web UI.

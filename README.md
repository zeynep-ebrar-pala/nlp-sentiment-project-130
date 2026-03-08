# AI Sentiment Analysis (Duygu Analizi)

Bu proje, metinlerin duygu durumunu (Pozitif/Negatif) analiz eden bir web uygulamasidir. Google Gemini AI ve Hugging Face Transformers kutuphanelerini kullanir.

## Ozellikler
- **Streamlit Arayuzu**: Kullanici dostu ve hizli bir frontend.
- - **Gemini AI Entegrasyonu**: Gelismis dil modelleri ile yuksek dogrulukta analiz.
  - - **FastAPI Backend**: Modellerin servis edilmesi icin hizli ve guvenilir bir backend.
    - - **Heuristic Fallback**: API hatalari durumunda kelime bazli basit analiz destegi.
     
      - ## Kurulum
      - 1. Gerekli kutuphaneleri yukleyin:
        2.    pip install -r requirements.txt
        3.2. .env dosyasini olusturun ve API anahtarinizi ekleyin:
             API_KEY=your_google_gemini_api_key_here

          ## Calistirma
        streamlit run streamlit_app.py

        ## Gelistiren
        **ZEYNEP EBRAR PALA**

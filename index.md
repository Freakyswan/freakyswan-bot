
# 🦢 Freakyswan Bot

**Freakyswan Bot** adalah sistem bot sinyal trading berbasis AI dan analisis teknikal yang dirancang untuk memberikan sinyal breakout akurat, cerdas, dan adaptif.

---

## 🔍 Fitur Utama

- ✅ Deteksi breakout multi-timeframe (1d/4h/1h)
- 🧠 Filter sinyal menggunakan GPT-4
- 📊 Backtest otomatis + visualisasi performa
- 📈 Simulasi equity curve dan PnL
- 📡 Sinyal real-time (5m)
- 📬 Notifikasi Telegram + grafik sinyal
- 📰 Filter sentimen pasar dari berita crypto
- 🔁 Adaptive strategy switching per pair

---

## 🚀 Cara Setup

1. Clone repo:
```bash
git clone https://github.com/username/freakyswan-bot.git
cd freakyswan-bot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Buat file `.env`:
```
TELEGRAM_TOKEN=your_token
TELEGRAM_CHAT_ID=your_id
OPENAI_API_KEY=your_openai
```

4. Jalankan bot:
```bash
python bot.py
```

---

## 📄 Dokumentasi Modul

- `bot.py` - Main signal sender
- `backtester.py` - Evaluasi strategi historis
- `scanner.py` - Sinyal real-time
- `batch_backtest.py` - Evaluasi semua pair + laporan Telegram
- `strategy_selector.py` - Adaptive strategy switching
- `news_filter.py` - Filter berdasarkan sentimen berita

---

## 🌐 Tentang

Dikembangkan untuk riset sinyal, edukasi, dan penggunaan profesional.  
Versi: **v1.1-signal-only**

📬 Hubungi: [Telegram](https://t.me/yourbot)

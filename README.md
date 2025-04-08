# 📊 Twitter Sentiment Analysis 🚀

Menganalisis sentimen tweet menggunakan **Machine Learning & NLP** untuk memahami opini publik!  
Proyek ini berfokus pada klasifikasi sentimen (positif, netral, negatif) dan analisis keterkaitannya dengan engagement.

## 🔍 Fitur Utama  
✅ **Scraping & Preprocessing** → Membersihkan data dari noise  
✅ **Sentiment Analysis** → Klasifikasi sentimen dengan model terbaik  
✅ **Engagement Impact** → Analisis hubungan antara like/retweet dengan sentimen  
✅ **Data Visualization** → Word Cloud, distribusi sentimen, dan scatter plot  

## 📌 Instalasi & Penggunaan  
**Clone repo ini**  
```bash
git clone https://github.com/arik147/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis
```

# 📊 Hasil Analisis Twitter Sentiment 🚀

## 📌 Distribusi Sentimen  
Analisis menunjukkan bahwa mayoritas tweet memiliki sentimen **positif**, diikuti oleh **netral**, dan sisanya **negatif**. Berikut distribusi sentimen dalam dataset:  

📊 **Grafik Distribusi Sentimen**  
![Distribusi Sentimen] ![image](https://github.com/user-attachments/assets/f2c04176-4809-4a1b-b446-837a545e1895)

---

## ☁️ Word Cloud Sentimen  
Berikut adalah **Word Cloud** dari tweet dengan sentimen **positif** dan **negatif**.  

![image](https://github.com/user-attachments/assets/c949387e-b78c-4c95-ae1e-a13f6ffb18f0)

---

## 🔗 Hubungan Engagement & Sentimen  
Dari analisis **engagement score** (like + retweet), ditemukan bahwa:  
- **Tweet dengan sentimen positif** cenderung memiliki engagement yang lebih tinggi.  
- **Tweet dengan sentimen negatif** juga bisa mendapatkan engagement yang tinggi, tetapi lebih jarang.  
- **Tweet netral** cenderung memiliki engagement yang lebih rendah dibandingkan lainnya.  

📈 **Scatter Plot: Engagement vs Sentiment**  
![Scatter Plot]! ![image](https://github.com/user-attachments/assets/c740599c-31f5-47fd-92a8-3fc5cd604cd5)


---

## 📊 Uji Statistik  
🔹 **Kruskal-Wallis Test** menunjukkan ada perbedaan signifikan dalam engagement berdasarkan sentimen.  
🔹 **Dunn’s Test** mengonfirmasi bahwa engagement antara sentimen positif dan negatif berbeda signifikan.  
🔹 **Korelasi Spearman** menunjukkan hubungan yang **lemah hingga sedang** antara engagement dan sentimen.  

📌 **Kesimpulan:**  
Engagement berpengaruh terhadap sentimen, tetapi tidak selalu menjadi faktor utama dalam menentukan sentimen sebuah tweet.  

---

## 🛠 Teknologi yang Digunakan  
- **Python**: Pandas, NumPy, Scikit-learn  
- **NLP**: Transformers, WordCloud  
- **Visualisasi**: Seaborn, Matplotlib  
- **Uji Statistik**: SciPy, scikit-posthocs  

📜 **Lisensi:** MIT License  

🚀 **Ingin kontribusi atau berdiskusi?** Feel free untuk buat issue atau PR di repo ini!  

# **Welcome to Netflix Movies and TV Shows Analysis!**
### An Exploratory Data Analysis and Recommendation System of Netflix

Project ini merupakan project Data Science kedua yang saya post ke Github, yang meliputi Data Cleaning dan Exploratory Data Analysis, termasuk Univariate/Bivariate/Multivariate Analysis dan Deep Dive Question, serta membuat model Recommendation System menggunakan bahasa pemograman Python.

### **File Description**
Selain README file, terdapat hanya 2 file lain di dalam repository, yaitu:
1. File notebook yang dapat dijalankan dengan menggunakan Google Colab. File tersebut berisikan step-by-step yang dilakukan, coding, model, beserta observation ataupun interpretasi yang didapatkan
2. File power point yang berisikan summary atas project yang dilakukan, sehingga dapat lebih mudah untuk memahami project tanpa melihat secara detail
Selain README file, terdapat hanya 2 file lain di dalam repository, yaitu:


### **Business Understanding**
Perusahaan bernama Netflix merupakah perusahaan yang menayangkan film dan TV show berbasis subcription berbayar kepada pelanggannya. Perusahaan ingin mempermudah pelanggan dengan memberikan rekomendasi film atau TV show.


### **Preliminary**
*   Objective Statement:
    *   Mendapatkan business insight untuk mengetahui detail film dan TV show yang ditayangkan di Netflix
    *   Mendapatkan business insight dengan menjawab pertanyaan sebagai berikut:
        1. Seberapa updatekah film dan TV show yang terdapat pada Netflix?
        2. Genre film dan TV show apa yang dirilis di Netflix pada 3 tahun terakhir?
        3. Bagaimanakah sentiment atas konten (berdasarkan description) yang terdapat pada Netflix selama 10 tahun terakhir?
    *   Membuat sistem rekomendasi konten berdasarkan input pelanggan
       
*   Challenges:
    *   Jumlah data yang besar
    *   Adanya missing value
    *   Adanya kolom dengan tipe data yang tidak sesuai
    *   Kurangnya informasi yang dapat membantu untuk membuat rekomendasi film atau TV show

*   Methodology/Analytic Technique:
    *   Exploratory Data Analysis
    *   Deep-Dive Exploration
    *   TF-IDF (Term Frequency - Inverse Document Frequency)
    *   Cosine Similarity

*   Business Benefit:
    *   Dengan mengetahui konten yang ditayangkan, Netflix dapat menentukan strategi atas konten apa yang harus direlease berikutnya 
    *   Dengan membuat sistem rekomendasi, Netflix dapat meningkatkan customer satisfaction dan customer retention. Hal ini dikarenakan sistem rekomendasi akan meningkatkan customer experience, yaitu membantu customer untuk menentukan film atau TV show apa yang akan ditonton customer sesuai dengan input customer, sehingga customer akan memiliki lebih banyak waktu untuk menikmati film atau TV show daripada frustasi menentukan apa yang harus ditonton

*   Expected Outcomes: 
    * Mengetahui detail film dan TV show yang ditayangkan di Netflix
    * Membuat machine learning yang dapat memberikan rekomendasi film atau TV show

### **Data Understanding**
*   Sumber data: Netflix Movies and TV Shows yang berasal dari Kaggle, yang dapat diakses melalui link sebagai berikut:
https://www.kaggle.com/datasets/shivamb/netflix-shows

*   Data detail:
    *   show_id: ID tayangan
    *   type: apakah tayangan termasuk movie atau TV show
    *   title: judul film atau TV show
    *   director: direktur film
    *   cast: pemeran film atau TV show
    *   country: negara di mana film atau TV show diproduksi
    *   date_added: tanggal release film atau TV show di Netflix
    *   release_year: tahun release film atau TV show yang sebenarnya
    *   rating: rating atas film atau TV show
    *   duration: total durasi dalam menit atau jumlah season
    *   listed_in: genre atas film atau TV show
    *   description: rangkuman deskripsi film atau TV show

# Google Play Store Analytics
<img src="https://github.com/atika-faradilla/google_playstore_analysis/blob/main/full_google_playstore_analysis.png">

Pada project ini akan didemonstrasikan beberapa tahapan dalam proses data analysis yang berupa Data Preprocessing, Data Wrangling, dan Data Visualization. Kemudian akan dibangun sebuah Flask UI sederhana yang berisi beberapa tampilan plot yang merupakan hasil insight dari analisis data ini. 

## Data Summary
Data yang digunakan pada capstone project ini adalah data hasil scraping dari Google Playstore App. Data Google Playstore App terdiri dari beberapa variabel dengan rincian sebagai berikut:
- `App` : Nama aplikasi                
- `Category` : Kategori aplikasi
- `Rating` : Rating keseluruhan yang diberikan oleh user aplikasi(ketika di scrap)
- `Reviews` : Jumlah review yang diberikan oleh user aplikasi(ketika di scrap)
- `Size` : Ukuran aplikasi(ketika di scrap)           
- `Installs` : Jumlah user yang menginstall/mendownload aplikasi(Ketika di scrap)     
- `Type` : Tipe aplikasi (berbayar/gratis)       
- `Price` : Harga aplikasi (ketika di scrap)        
- `Content Rating` : Kelompok usia aplikasi ini ditargetkan - Children / Mature 21+ / Adult   
- `Genres` : Genre aplikasi.        
- `Last Updated` : Tanggal kapan aplikasi terakhir diperbarui di Play Store (ketika discrap) 
- `Current Ver` : Versi aplikasi saat ini tersedia di Play Store (ketika discrap)   
- `Android Ver` : Minimum versi Android yang diperlukan (ketika discrap) 

## Dependencies
- Flask
- Matplotlib
- Pandas
- Numpy

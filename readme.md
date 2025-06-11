
<div align='center'>
<img src='https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEji8e19TWkWr_nRiO6vbzRG2_sXrXJjTEwZVvolrPdBcjRuiKCaThOoCPTE74uM0FqXy9yyWLRiHs3K9-7xARsgmUKtncy1XuITwbihAryixdiX1yzCR03KHC2ZkOViB-fQCUmnoCLpN26VTsQrVCuacGQwOUZ3fGXqSrhrZ4Cw84aiFh0TtCsw5HgH5fK2/s299/log-unsika.png' alt='logo unsika.png'>

<h1>
  Tugas Pertemuan 10 : <br>
  Implementasi Proyek Kecerdasan Buatan
</h1>
<h2>
  Kelompok 5
</h2>
<h3>
  Nama Anggota : <br>
</h3>
<p>
  Aisyah Nurhayati  (2210631250040) <br>
  Della Anissa Putri Widodo  (2210631250044) <br> 
  Farhan Abyan Putra Karim  (2210631250049) <br>
</p>
</div>
<br><br>
<h2>
  Pendahuluan
</h2>
<div align='justify'>
  <p>
  Alhamdulillah, segala puji beserta syukur kami panjatkan ke hadirat Allah Subhanahu Wa Taala yang atas berkat, rahmat, dan karuniaNya lah kami dapat menyelesaikan satu per satu tugas-tugas dan kewajiban kami terhadap ilmu pengetahuan. Shalawat beserta salam tak lupa kami haturkan pula kepada junjungan kita Rasulullah Muhammad Shalallahu Alaihi Wa Salam, pun kepada keluarganya, para sahabatnya, para tabi’in, para tabi’it tabi’in, dan khususnya kepada kita umatnya hingga hari akhir kelak. Semoga kita menjadi golongan orang-orang yang diberikan syafaat oleh Rasulullah kelak di hari kiamat nanti.
<br><br>
  Melalui tulisan ini, penulis ingin mengucapkan syukur dan terima kasih, kepada setiap elemen dan komponen sosial yang telah berkontribusi terhadap penyelesaian tugas dan proyek yang telah dibuat ini. Ini merupakan salah satu langkah penulis untuk bergerak maju dan menyelesaikan tahapan demi tahapan pendidikan yang sedang di tempuh. Tugas demi tugas, makalah demi makalah, proyek demi proyek dan karya tulis demi karya tulis ini akan senantiasa kami jadikan refleksi untuk evaluasi diri kedepannya. Harapannya, proyek ini bisa digunakan sebagai media pembelajaran bersama, dari kami untuk semua. Kami berharap proyek ini akan memberikan manfaat dan kebergunaan untuk diri saya sendiri khususnya dan untuk masyarakat atau mahasiswa lain pada umumnya.
<br><br>
  Kami (saya) menyadari bahwa kami hanyalah manusia biasa yang tidak luput dari kesalahan. Oleh karenanya, kami mengharapkan setiap kritik, saran, dan masukan yang diberikan oleh para pembaca agar supaya kami dapat berbenah diri dan melaksanakan evaluasi atas setiap kinerja dan tindakan yang telah dilakukan. Besar harapan kami, bahwa setiap masukan yang membangun dari para pembaca dapat menjadi batu loncatan kami, agar terus berkembang dan bertumbuh menjadi lebih baik dan semakin baik lagi.
  </p>
</div>


<br>
<div align='right'>
  <p>
    <b>Karawang, 09 Juni 2025</b>
    <br>
    <br>
    <br>
    <br>
    Kelompok 5
  </p>
</div>

---

<div align='center'>
  <h2>
    BAB I : Pendahuluan
  </h2>
</div>
<div align='justify'>
  <h3>
    A. Latar Belakang
  </h3>
  <p>
    Pasar modal merupakan salah satu instrumen investasi yang paling diminati, paling dicari yang menawarkan potensi keuntungan yang signifikan bagi para <i>trader/investor</i>-nya. Namun, fluktuasi harga saham yang volatil, dinamis, dan kompleks menjadikannya arena yang menantang dan penuh resiko bagi sebagian investor. Keputusan investasi yang didasarkan pada spekulasi atau intuisi seringkali berujung pada kerugian. Hal ini dikarenakan pelaksanaan jual-beli instrumen investasi tanpa keputusan yang didasari oleh pengetahuan sama saja dengan perjudian atau taruhan. Oleh karena itu, kebutuhan akan alat praktis yang dapat memprediksi pergerakan harga saham secara akurat menjadi sangat krusial. Prediksi harga saham yang tepat dapat membantu investor dalam mengambil keputusan yang lebih informatif, meminimalkan risiko, dan mengoptimalkan keuntungan.

  Secara tradisional, analisis harga saham dibagi menjadi dua subset besar, yakni analisis fundamental dan analis teknikal. Kedua analisis tersebut telah menjadi metode utama yang paling klise dan terpercaya untuk memprediksi harga saham. Analisis fundamental berfokus pada evaluasi kesehatan keuangan perusahaan dan faktor-faktor ekonomi makro, sedangkan analisis teknikal mempelajari pola harga dan volume perdagangan di masa lalu. Meskipun kedua pendekatan ini memiliki kelebihan, keterbatasan dalam menangani data non-linear dan kompleksitas pasar seringkali mengurangi akurasi prediksinya.

  Seiring dengan perkembangan teknologi, kecerdasan buatan (AI) dan pembelajaran mesin (Machine Learning) telah menawarkan solusi inovatif untuk berbagai permasalahan prediksi, termasuk di bidang finansial. Salah satu cabang pembelajaran mesin yang menunjukkan potensi besar dalam menganalisis data deret waktu (time series) adalah Deep Learning. Khususnya, arsitektur seperti Recurrent Neural Networks (RNN) dan varian-variannya seperti Long Short-Term Memory (LSTM) dan Gated Recurrent Unit (GRU) sangat cocok untuk memodelkan ketergantungan sekuensial dalam data deret waktu.

TensorFlow, sebagai framework pembelajaran mesin open-source yang powerful, menyediakan berbagai tool dan API yang memfasilitasi pengembangan model Deep Learning, termasuk untuk masalah prediksi deret waktu. Dengan memanfaatkan kemampuan TensorFlow TimeSeries, dimungkinkan untuk membangun sistem prediksi harga saham yang lebih canggih dan akurat dibandingkan metode tradisional.
  </p>
   <h3>
    B. Rumusan Masalah
  </h3>
  <p>
    Berdasarkan latar belakang di atas, rumusan masalah dalam penelitian ini adalah sebagai berikut:

  1. Bagaimana membangun model prediksi harga saham menggunakan TensorFlow ?
  2. Bagaimana performa model prediksi harga saham yang dikembangkan dengan TensorFlow ?
  3. Metrik evaluasi apa yang digunakan dalam melakukan prediksi dataset Time Series ?
  4. Bagaimana melakukan pembersihan dan pra-pemrosesan data Time Series ?
  5. Faktor-faktor apa saja yang perlu dipertimbangkan dalam persiapan data dan feature engineering untuk meningkatkan akurasi prediksi harga saham menggunakan dataset Time Series ?
  </p>
  <h3>
    C. Batasan Masalah
  </h3>
  <p>
    Agar penelitian ini tetap terfokus dan terarah, batasan masalah yang ditetapkan adalah sebagai berikut:

  1. Sistem prediksi akan difokuskan pada data harga penutupan (closing price) saham dari satu emiten yakni TLKM (PT. Telekomunikasi Indonesia (persero) tbk).
  2. Model prediksi akan dibangun menggunakan arsitektur Deep Learning yang didukung oleh TensorFlow.
  3. Evaluasi performa model akan didasarkan pada metrik umum untuk deret waktu seperti Mean Squared Error (MSE), Root Mean Squared Error (RMSE), dan Mean Absolute Error (MAE).
  4. Data yang digunakan adalah data historis harga saham yang tersedia secara publik, dengan rentang waktu dan frekuensi data yang ditentukan dari tahun 2015 s.d. tahun 2022.
  </p>
  <h3>
    D. Tujuan Penelitian
  </h3>
  <p>
    Tujuan dari penelitian ini adalah:

  1. Membangun sistem prediksi harga saham menggunakan pendekatan TensorFlow Time Series prediction.
  2. Menganalisis performa dan akurasi model prediksi harga saham yang telah dikembangkan.
  3. Memberikan wawasan mengenai potensi dan tantangan dalam menerapkan Deep Learning untuk prediksi harga saham.
  </p>
  <h3>
    E. Manfaat Penelitian
  </h3>
  <p>
    Penelitian ini diharapkan dapat memberikan manfaat sebagai berikut:

  1. Bagi Investor: Menyediakan alat bantu yang lebih akurat untuk memprediksi pergerakan harga saham, sehingga dapat membantu dalam pengambilan keputusan investasi yang lebih baik dan terinformasi.
  2. Bagi Peneliti: Menambah khazanah ilmu pengetahuan di bidang machine learning dan deep learning, khususnya dalam aplikasi prediksi deret waktu pada sektor finansial.
  3. Bagi Pengembang Sistem: Memberikan referensi dan panduan dalam membangun sistem prediksi harga saham menggunakan TensorFlow TimeSeries, yang dapat dikembangkan lebih lanjut di masa mendatang.
  </p>
</div>

## Bram,

  Kenapa saat buka tidak menggunakan live server ? atau click langsung dari file explorer kan maksudnya ? 

  Jawaban :

    Karena khe masukkan css atau img menggunakan absolute path. Jadi khe langsung panggil dari base pathnya.
    Sebagai contoh :
      Ketika menggunakan 
        Live Server : http://127.0.0.1:5500/Ikan%20Kuah%20Kuning.html (url akan begini)
        File explorer : file:///C:/Users/Nata%20Inditama/Desktop/Working/webmasak/Ikan%20Kuah%20Kuning.html (beda tergantung dimana filenya)

    Jadi absolute path khe panggil begini
    <link rel="stylesheet" href="/ikan kuah kuning.css" />
    Jika tidak absolute path khe panggil begini (biasanya di sebut relative path)
    <link rel="stylesheet" href="ikan kuah kuning.css" /> atau
    <link rel="stylesheet" href="./ikan kuah kuning.css" /> atau
    <link rel="stylesheet" href="../ikan kuah kuning.css" />

    Kalau khe panggil menggunakan absolute path, akan mengambil file dari base path. Yang mana base path nya ? Kalau dari contoh diatas
    Live server : http://127.0.0.1:5500/ (Ini base pathnya, tergantung folder mana yang khe pakai di visual studio code)
    File explorer : file:///C:/ (Ini base pathnya, coba khe check apakah di disk C ada file css atau img ? Enggak ada kan ? Itu karena memang di base path enggak ada file tersebut)


  Note :

    Oiya aku sarankan kalau buat html dan css, Jangan pakai white space (spasi, tab dll)
    Cukup index.html (Soalnya index akan dibaca pertama), atau about.html, product.html, dan huruf kecil semua okeh ?
    index.html (V)
    index test.html (X)
    INDEX.html (X)
    index.html (V) 

    Oiya kalau masalah dari git saat download itu karena servernya, Coba nanti khe check ulang download gitnya. Soalnya git penting untuk project invention 2022. Aku sarankan khe perlu belajar git
     
  [PZN](https://www.youtube.com/playlist?list=PL-CtdCApEFH_lYGV8hxqjtKmFA_xeLupq) atau [UNPAS](https://www.youtube.com/playlist?list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf)


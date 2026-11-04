LEARNHUB — PWA PACKAGE

Isi folder:
- index.html: aplikasi LearnHub yang sudah ditambahkan dukungan PWA
- manifest.webmanifest: nama aplikasi, ikon, dan pengaturan instalasi
- sw.js: service worker untuk app shell/offline shell
- icons/: ikon aplikasi 192px dan 512px

CARA MEMBUAT BISA DIINSTAL
1. Upload seluruh isi folder ini ke hosting HTTPS (misalnya GitHub Pages atau Netlify).
   Jangan upload index.html saja; manifest, sw.js, dan folder icons harus ikut.
2. Buka alamat website hasil hosting di Chrome Android.
3. Tunggu beberapa detik. Jika tombol ⬇ muncul di header LearnHub, tekan lalu pilih Install.
   Alternatif: menu Chrome (⋮) > Install app / Tambahkan ke layar utama.
4. Setelah terpasang, LearnHub akan muncul sebagai ikon aplikasi dan terbuka tanpa address bar browser.

CATATAN PENTING
- File HTML yang dibuka langsung dari penyimpanan HP (file://) tidak bisa dipasang sebagai PWA.
- PWA bukan APK Android. Untuk instalasi seperti aplikasi tanpa Play Store, hosting HTTPS sudah cukup.
- Data aplikasi yang disimpan di browser/perangkat tidak otomatis tersinkron ke perangkat lain.

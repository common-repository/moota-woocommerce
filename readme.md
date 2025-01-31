=== Moota WooCommerce - Cek Mutasi Otomatis Bank Nasional  ===
Contributors: matamerah,  onnayokheng, rezzakurniawan
Tags: cek mutasi, mutasi bank, payment gateway, indonesia, woocomerce, bca, mandiri, bni, bri, muamalat, otomatis, mutasi, moota, bank
Requires at least: 5
Tested up to: 5.8
Stable tag: 0.7.6
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Plugin ini adalah addon dari Moota.co sebagai payment gateway woocomerce wordpress dan auto konfirmasi.

== Description ==

Moota.co merupakan aplikasi untuk pengecekkan mutasi dan saldo rekening Anda, dimana mutasi rekening Anda, kami dapatkan dari akun iBanking Anda. Dan bisa diintegrasikan ke seluruh lini bisnis Anda, misalkan Toko Online. Karena kami menyediakan API yang bisa Anda gunakan untuk keperluan bisnis online Anda.

Anda akan mendapatkan notifikasi melalui email, push notif (API). Jadi akan sangat memudahkan Anda dan tim untuk mengelola orderan.

Sudah banyak Bank yang bisa kami support, diantaranya:
* BCA,
* MANDIRI,
* BNI,
* BRI,
* Muamalat
* dan terus bertambah.
Sistem Moota ini bisa diimplementasikan pada sistem apa saja, karena kami sudah menyediakan API-nya juga.

Silahkan daftar terlebih dahulu di [Moota.co](https://moota.co) untuk bisa menggunakan plugin ini.

== Installation ==

= Langkah ke-1 =
Cara menginstall plugin WooCommerce Moota sangatlah mudah.

1. Unggah plugin ini ke folder `/wp-content/plugins/woomoota`, atau install langsung melalui WordPress plugin secara instan.
2. Aktivkan di menu 'Plugins' WordPress Anda.
3. Masuk ke menu WooCommerce->Settings->WooMoota Tab untuk melakukan setting plugin Moota.
4. Salin "API Endpoint" berupa link contoh: `http://tokoonlineanda.com/?woomoota=push`
5. Lalu lakukan langkah ke-2 di bawah ini.

= Langkah ke-2 =
Pastikan Anda daftar di web https://moota.co dan mempunyai minimal 1 akun rekening yang telah didaftarkan.

1. Kunjungi web https://moota.com lalu login.
2. Edit rekening yang akan digunakan untuk integrasi.
3. Masuk ke tab `notifikasi`.
4. Lalu edit API `Push Notif`, masukkan `API Endpoint` pada langkah pertama tadi.
5. Lalu simpan.

Dan silahkan mulai berjualan.

= Tutorial =
Selengkapnya silahkan kunjungi tutorial integrasi Moota dengan WooCommerce di sini:
[https://moota.co/tutorial/woocommerce/](https://moota.co/tutorial/woocommerce/)

== Frequently Asked Questions ==

= Bagaimana cara install dan integrasi dengan toko online saya? =

Selengkapnya silahkan kunjungi tutorial integrasi Moota dengan WooCommerce di sini:
[https://moota.co/tutorial/woocommerce/](https://moota.co/tutorial/woocommerce/)

= Apakah ada biaya langganan? =

Ya, untuk menggunakan layanan Moota.co kami menerapkan sistem deposit. Dan layanan mutasi ini akan dikenakan kredit 1500/hari.

= Apakah data saya aman? =

Ya, kami menjamin keamanan data Anda. Karena kami akan mengenkripsi data Anda, juga menggunakan protocol khusus dan menggunakan SSL yang akan mengenkripsi aktivitas Anda di browser. Sehingga keamanannya akan lebih optimal.

= Berapa kali mutasi akan update? =

Pengecekkan mutasi dilakukan 15 menit sekali.

= Apakah saya bisa akses Internet Banking saya bila menggunakan layanan ini? =

Anda bisa buka iBanking Anda kapanpun, tanpa terganggu oleh Moota.

= Melalui apa saja saya akan menerima notifikasi? =

Sistem akan mengirim notifikasi setiap ada transaksi masuk kepada Anda melalui Email, API dan SMS (ringkasan harian).


== Changelog ==

= 0.6.4 =
* Add : Logging trafic

= 0.6.3 =
* Fixed: Bug unique code always changed after proccess order

= 0.6.2 =
* Fixed: Update for Wordpress 5.8

= 0.6.1 =
* Fixed: Unique code set with minimum unique code

= 0.6.0 =
* Add: Make unique code not duplicated

= 0.5.3 =
* Edit: minimum unique code to be 0
* Edit: maximum unique code to be 99999
* Fix: checking variable woomoota

= 0.5.2 =
* Add: Pengecekan respon body jika sudah dalam bentuk json
* Add: do action moota-before-auto-confirm untuk integrasi dengan plugin lain
  
= 0.5.1 =
* Fix: register schedule time perubahan status order

= 0.5.0 =
* Add: Fitur mengubah status order "on-hold" ke "pending".

= 0.4.7 =
* Add: Tambah pengecekkan status order untuk status "pending"

= 0.4.6 =
* Fix: Pengecekan ketika checkout produk gratis/free

= 0.4.5 =
* Fix: Hapus die function ketika Plugin WooCommerce tidak terinstall

= 0.4.4 =
* Fitur: Pengecekkan bila ada nominal order yang sama
* Fitur: Penambahan seting limit hari pengecekkan invoice

= 0.4.2 =
* Fix: Remote Address Checker
* Support PHP 5.3

= 0.4.1 =
* Fix: Bugs Die WP Admin
* Show Alert Status

= 0.4.0 =
* Fitur: Mode Testing & Production
* Peningkatan Keamanan

= 0.2.0 =
* Fitur: Menambahkan fitur kode unik.

= 0.1.0 =
* Inisialisasi di server sendiri

== Upgrade Notice ==

= 1.0 =
Penambahan fitur kode unik yang nanti akan menjadi pembeda ketika konsumen checkout.

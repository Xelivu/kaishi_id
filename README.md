**DEK LAIN APA PUN YANG TIDAK DISEBUTKAN DI HALAMAN INI TIDAK TERAFILIASI DENGAN SAYA, TERMASUK MODIFIKASI AI ATAU BERBAYAR APA PUN.**

# Kaishi 1.5k

Selamat datang di repositori publik untuk **Kaishi 1.5k**, sebuah dek Anki modern yang dibuat untuk memperkenalkan kosakata dasar bahasa Jepang kepada para pemula. Kaishi 1.5k sangat modular dan halaman ini didedikasikan untuk menjelaskan berbagai opsi yang dapat Anda gunakan untuk mengubah dek sesuai dengan keinginan Anda. Berikut adalah tampilan bagian depan dek:

<img src="https://github.com/donkuri/Kaishi/blob/main/pics/kaishi-front.png" alt="Front of a Card in Kaishi 1.5k" style="width: 100%; height: auto">

Seperti yang dapat Anda lihat, baik kata maupun kalimatnya tersedia, tetapi kata tersebut disorot di dalam kalimat, sehingga memudahkan Anda untuk segera mengisolasi informasi penting. Setelah kata tersebut dipahami dengan baik, peninjauan akan menjadi lebih cepat karena kata tersebut muncul lebih dulu. Berikut adalah bagian belakang dari dek bawaan (default):

<img src="https://github.com/donkuri/Kaishi/blob/main/pics/kaishi-back.png" alt="Back of a Card in Kaishi 1.5k" style="width: 100%; height: auto">

Berbeda dengan sebagian besar dek bertipe Core lainnya, di sini furigana memberikan cara membaca kata tersebut, dengan artinya tepat di bawahnya. Audio untuk kata dan kalimat kemudian tersedia untuk Anda. Jika Anda mau, Anda juga dapat menambahkan aksen nada (*pitch accent*), lihat di bawah. Jika ada catatan yang terkait dengan kartu spesifik tersebut, catatan itu akan ditampilkan di bawah.

[Jika Anda baru belajar bahasa Jepang atau metode imersi, silakan baca panduannya terlebih dahulu.](https://donkuri.github.io/learn-japanese/guide/)

### Daftar Isi

- [Di mana saya bisa mendapatkan dek ini?](#di-mana-saya-bisa-mendapatkan-dek-ini)
- [Bagaimana cara menggunakan dek ini?](#bagaimana-cara-menggunakan-dek-ini)
- [Dek terkait lainnya](#dek-terkait-lainnya)
- [Opsi apa saja yang tersedia untuk dek ini?](#opsi-apa-saja-yang-tersedia-untuk-dek-ini)
- [Saya tidak suka gambar-gambarnya!](#saya-tidak-suka-gambar-gambarnya)
- [Saya tidak suka kalimatnya selalu ditampilkan!](#saya-tidak-suka-kalimatnya-selalu-ditampilkan)

<div lang="ja">
{{furigana:Word Furigana}}

{{#Pitch Accent}}
	<br><div style='font-size: 24px'>{{Pitch Accent}}</div>
{{/Pitch Accent}} 

<div style='font-size: 25px; padding-bottom:20px'>{{Word Meaning}}</div>
<div style='font-size: 25px;'>{{furigana:Sentence Furigana}}</div>
<div style='font-size: 25px; padding-bottom:10px'>{{Sentence Meaning}}</div>

{{Word Audio}}
{{Sentence Audio}}
<br>
{{Picture}}

{{#Notes}}
	<br>
	<div style="font-size: 20px; padding-top:12px">Note: {{Notes}}</div>
{{/Notes}}

{{#Pitch Accent Notes}}
<div style="font-size: 20px; width: fit-content; max-width:40vw; margin: auto">
	<details><summary>Pitch Accent Notes</summary>
		<br>{{Pitch Accent Notes}}
	</details>
</div>
{{/Pitch Accent Notes}}

</div>

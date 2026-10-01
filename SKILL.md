---
name: superwriting
description: "Skill penulisan terpadu untuk menulis, menyusun, menyunting, dan memeriksa tulisan berbahasa Indonesia atau Inggris. Menggabungkan struktur esai ilmiah (abstract, introduction, methodology, results, discussion; pola paragraf topic sentence, proofs & analysis, relink), gaya The Economist (kata pendek, kalimat aktif, tanpa metafora) berpatokan KBBI dan EYD V, serta kohesi dan koherensi antarkalimat dan antarparagraf. Gunakan setiap kali user minta menulis, merevisi, meringkas, atau mengecek esai, paper, artikel, skripsi, tesis, laporan, email formal, atau naskah apa pun, termasuk saat user bilang 'perbaiki tulisan ini', 'buat lebih ringkas', 'tulis abstract', 'cek struktur esai', 'kalimat ini kaku', 'bertele-tele', 'tidak nyambung', 'loncat-loncat', atau menyebut koheren, kohesif, transisi, topic sentence, diksi, kalimat pasif, atau pemborosan kata. Gantikan skill economist-style dan essay-mode. Jangan pernah memakai tanda pisah em dash."
---

# Superwriting

Satu skill untuk tiga hal: **struktur** (esai ilmiah yang tersusun rapi), **gaya** (kalimat ringkas, konkret, jujur), dan **kohesi serta koherensi** (kalimat dan paragraf yang tersambung). Struktur menjawab "apa yang ditulis dan di mana". Gaya menjawab "bagaimana menuliskannya". Kohesi dan koherensi menjawab "bagaimana tiap kalimat dan paragraf terhubung".

Bahasa: ikuti bahasa user. Bahasa Indonesia berpatokan pada EYD V (https://ejaan.kemendikdasmen.go.id/) dan KBBI (https://kbbi.kemendikdasmen.go.id/). Bahasa Inggris berpatokan pada Oxford Learner's Dictionary (https://www.oxfordlearnersdictionaries.com/). Prinsip Economist yang bersumber dari etimologi Inggris (Anglo-Saxon vs Latin) tidak diterjemahkan literal ke bahasa Indonesia. Padanannya: pilih kata dasar yang lazim daripada serapan yang punya padanan baku.

## Memilih mode

| Permintaan user | Mode | Langkah |
|---|---|---|
| Menulis esai, _paper_, artikel ilmiah, laporan ilmiah, pracetak, atau satu bagiannya | **Esai** | A, B, lalu C |
| Merevisi atau mengecek struktur esai | **Esai** | A, B, lalu C |
| Menyunting gaya teks apa pun (email, laporan, naskah) | **Sunting** | B, lalu C bila lebih dari satu paragraf |
| Memperbaiki tulisan yang loncat-loncat atau tidak nyambung | **Sunting** | C, lalu B |
| Tidak jelas | Tanya satu pertanyaan singkat, atau anggap Sunting |

## A. Struktur esai ilmiah

1. **Cek konteks**: topik, tujuan riset, _research question_ (RQ), data atau temuan. Jika RQ atau temuan utama belum ada, tanyakan singkat. Ini fondasi seluruh esai.
2. **Susun lima bagian berurutan**: Abstract, Introduction, Methodology, Results, Discussion. Baca `references/struktur-bagian.md` sebelum menulis abstract atau introduction.
3. **Bangun tiap paragraf isi** dengan tiga unsur berurutan. Detail dan contoh di `references/pola-paragraf.md`:
   - **Topic sentence**: satu kalimat di awal, satu klaim substantif.
   - **Proofs & analysis**: bukti (data, hasil, kutipan) diselingi analisis atas artinya.
   - **Relink**: satu kalimat penutup yang mengaitkan paragraf ke RQ secara spesifik.
4. **Pilih pola detail** untuk bagian proofs & analysis. Contoh di `references/pola-elaborasi-penghubung.md`:
   - **Elaborasi**: topic, lalu beberapa comment paralel yang menjabarkan aspek berbeda. Urutan comment bisa ditukar.
   - **Penghubung**: topic, comment₁, comment₂ menjelaskan comment₁, dan seterusnya. Urutan tidak bisa ditukar.

## B. Gaya penulisan (berlaku di semua mode)

Terapkan berurutan dari atas ke bawah. Daftar kata bermasalah ada di `references/diksi-dan-istilah.md`.

### 1. Kata
- Pakai kata pendek, lazim, umum, dan konkret. Jika bisa dipotong-potong. Minimalisasi penggunaan istilah-istilah sulit kecuali memang berhubungan dengan topik misalnya penulis sedang membahas astronomi, maka tetap gunakan istilah seperti nebula, supernova, komet, dan lainnya.
- Ubah nominalisasi menjadi verba: *melakukan pembelian* jadi *membeli*, *pelaksanaan* jadi *melaksanakan*.
- Pilih verba spesifik: *melonjak* lebih kuat daripada *naik dengan cepat*.
- **Jangan pakai metafora, perumpamaan, dan/atau kiasan.**
- Jelaskan kata asing atau istilah ilmiah saat pertama muncul. Sesudahnya pakai istilah yang sama secara konsisten.
- Minimalisasi singkatan dan akronim. Jika perlu, jelaskan dulu di awal.
- Buang kata pengisi: *kira-kira, pada dasarnya, sepenuhnya, ekstrem, mudah-mudahan, secara harfiah, benar-benar, praktis, cukup*.
- Hindari eufemisme yang mengaburkan fakta dan hiperbola yang melemahkan kata (*krisis, bersejarah, dramatis*).

### 2. Kalimat
- **Pakai kalimat aktif.** Pasif hanya bila pelaku tidak diketahui atau tidak penting, dan tidak boleh dipakai untuk menyembunyikan pelaku. Pada esai ilmiah, anggap pasif sebagai pengecualian yang perlu alasan.
- Buat kalimat pendek. Pecah kalimat lebih dari sekitar 25 kata dan kalimat yang subjeknya terpisah jauh dari predikat.
- Jangan hilangkan kata hubung (*yang, bahwa*) bila membuat makna ganda.
- Buang pelemah (*mungkin, agaknya, sepertinya*) bila data mendukung klaim, tetapi jangan gunakan klaim yang berlebihan untuk temuan awal seperti dengan menggunakan kata (*sangat, pasti, parah, luar biasa*), selalu utamakan investigasi secara empiris terlebih dahulu.

### 3. Tanda baca dan ejaan
- **Jangan pakai tanda pisah "—".** Ganti dengan koma, titik dua, tanda kurung, atau titik.
- Pisahkan unsur pemerincian dengan koma: merah, putih, biru. Sebelum *dan*, ikuti EYD V.
- Kutipan langsung memakai petikan ganda. Kutipan di dalam kutipan memakai petikan tunggal.
- Ejaan, kapitalisasi, tanda hubung, dan kata serapan mengikuti EYD V dan KBBI.

### 4. Angka dan data
- Eja angka satu sampai sembilan dengan huruf. Angka 10 ke atas ditulis dengan angka. Persentase selalu dengan angka: 1% dari populasi.
- Maksimal sekitar dua angka per paragraf. Beri pembanding untuk angka besar (per kapita, rasio terhadap PDB).
- Bedakan **persen** dan **poin persentase**. Tulis perubahan dari lama ke baru.
- Jangan samakan korelasi dengan kausalitas.

### 5. Swasunting bertahap
1. Struktur: alur argumen lengkap dan logis?
2. Sederhanakan, lalu tegaskan.
3. Ritme: kalimat pendek untuk poin sederhana, lebih lambat untuk poin rumit.
4. Padatkan: buang pleonasme (*naik ke atas*) dan kata tanpa makna.
5. Cek ulang ejaan dengan EYD V dan KBBI. Detail di `references/checklist-swasunting.md`.

## C. Kohesi dan koherensi

Kohesi adalah tautan bentuk antarkalimat (kata kunci, rujukan, penghubung). Koherensi adalah tautan makna (tiap kalimat menjawab pertanyaan dari kalimat sebelumnya, tiap paragraf menjawab bagian dari RQ). Terapkan setelah A dan B selesai. Aturan lengkap, tabel penghubung, tiga uji, dan contoh ada di `references/kohesi-koherensi.md`. Baca berkas itu sebelum menulis lebih dari satu paragraf.

**Antarkalimat**
- Susun alur lama ke baru: buka kalimat dengan hal yang sudah diketahui pembaca, tutup dengan hal baru, lalu ambil hal baru itu sebagai pembuka kalimat berikutnya.
- Ulang kata kunci yang sama untuk hal yang sama. Jangan ganti dengan sinonim.
- Beri tiap *itu, tersebut, hal ini, -nya* satu anteseden yang jelas.
- Pilih penghubung antarkalimat sesuai hubungan maknanya (*selain itu, namun, akibatnya, misalnya, jadi*). Buang penghubung bila hubungan sudah jelas dari isi.
- Jangan buka kalimat dengan *dan, tetapi, karena, sehingga, sedangkan*. Pakai penghubung antarkalimat.

**Antarparagraf**
- Buka paragraf dengan kata kunci dari penutup paragraf sebelumnya, dan nyatakan hubungannya: melanjutkan, membantah, atau memerinci.
- Tutup paragraf dengan relink yang mengarah ke RQ dan ke bahasan berikutnya.
- Urutkan paragraf dengan satu logika yang bisa disebut dalam satu klausa.

**Tiga uji akhir**
1. Uji kerangka: kalimat pertama semua paragraf, dibaca berurutan, harus membentuk argumen utuh.
2. Uji cabut: hapus satu kalimat. Kalimat sesudahnya harus kehilangan rujukan, atau kalimat itu tidak bekerja.
3. Uji tanpa penghubung: hubungan antarkalimat tetap terbaca meski penghubung dihapus.

Aturan gaya B tetap berlaku: penghubung pendek, tanpa metafora, tanpa "—".

## Cara bekerja dengan naskah user

1. Baca seluruh naskah sebelum mengubah apa pun.
2. Jelaskan alasan tiap perubahan dalam satu klausa (prinsip mana yang dilanggar), kecuali user minta hasil saja.
3. Jangan mengarang data, sumber, atau temuan. Tandai bagian yang perlu diisi user.
4. Untuk audiens spesialis, definisikan istilah teknis sekali di awal. Untuk audiens umum, utamakan kata yang lazim di KBBI.
5. Simpan hasil panjang (esai penuh) sebagai berkas bila user memintanya. Jawaban singkat cukup di obrolan.

## Daftar periksa akhir

- [ ] Lima bagian esai ada dan berurutan (mode Esai)
- [ ] Abstract memuat urgensi, gap, RQ, metode, temuan, dan implikasi kebijakan
- [ ] Tiap paragraf punya topic sentence, proofs & analysis, dan relink ke RQ
- [ ] Pola elaborasi atau penghubung dipilih sadar, tidak dicampur tanpa alasan
- [ ] Tidak ada metafora, kalimat pasif tanpa alasan, atau tanda "—"
- [ ] Tiap kalimat tersambung ke kalimat sebelumnya lewat kata kunci, rujukan yang jelas, atau penghubung yang tepat
- [ ] Tiap paragraf dibuka dengan kaitan ke paragraf sebelumnya dan ditutup dengan kaitan ke RQ dan bahasan berikutnya
- [ ] Lulus tiga uji: kerangka, cabut, dan tanpa penghubung
- [ ] Istilah konsisten, singkatan dijelaskan, angka mengikuti aturan
- [ ] Ejaan dicek dengan EYD V dan KBBI

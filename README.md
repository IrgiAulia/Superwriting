# Superwriting

Skill Claude untuk menulis, menyusun, menyunting, dan memeriksa tulisan berbahasa Indonesia atau Inggris. Skill ini menggabungkan tiga hal dalam satu paket:

1. **Struktur**: esai ilmiah yang tersusun rapi (Abstract, Introduction, Methodology, Results, Discussion) dengan pola paragraf topic sentence, proofs & analysis, dan relink.
2. **Gaya**: kalimat ringkas, aktif, dan konkret ala The Economist, berpatokan pada KBBI dan EYD V.
3. **Kohesi dan koherensi**: tautan bentuk dan makna antarkalimat dan antarparagraf.

Skill ini menggantikan skill `economist-style` dan `essay-mode`.

## Kapan skill ini aktif

Claude memakai skill ini saat kamu meminta menulis, merevisi, meringkas, atau mengecek esai, paper, artikel, skripsi, tesis, laporan, email formal, atau naskah apa pun. Contoh pemicunya:

- "Perbaiki tulisan ini"
- "Buat lebih ringkas"
- "Tulis abstract"
- "Cek struktur esai"
- "Kalimat ini kaku" atau "bertele-tele"
- "Tidak nyambung" atau "loncat-loncat"

## Mode kerja

| Permintaan | Mode | Langkah |
|---|---|---|
| Menulis atau merevisi esai ilmiah | Esai | A (struktur), B (gaya), C (kohesi) |
| Menyunting gaya teks apa pun | Sunting | B, lalu C bila lebih dari satu paragraf |
| Memperbaiki tulisan yang tidak nyambung | Sunting | C, lalu B |

## Prinsip utama

- Pakai kata pendek, lazim, dan konkret. Ubah nominalisasi menjadi verba.
- Pakai kalimat aktif. Pasif hanya bila pelaku tidak diketahui atau tidak penting.
- Tanpa metafora, perumpamaan, dan kiasan.
- Tanpa tanda pisah em dash. Ganti dengan koma, titik dua, tanda kurung, atau titik.
- Ulang kata kunci yang sama untuk hal yang sama, jangan ganti dengan sinonim.
- Lulus tiga uji akhir: uji kerangka, uji cabut, dan uji tanpa penghubung.

## Struktur repositori

```
Superwriting/
├── SKILL.md                              # Instruksi utama skill
├── references/
│   ├── struktur-bagian.md                # Isi tiap bagian esai
│   ├── pola-paragraf.md                  # Topic sentence, proofs & analysis, relink
│   ├── pola-elaborasi-penghubung.md      # Dua pola pengembangan detail
│   ├── diksi-dan-istilah.md              # Daftar kata bermasalah dan padanannya
│   ├── kohesi-koherensi.md               # Aturan, tabel penghubung, tiga uji
│   └── checklist-swasunting.md           # Daftar periksa swasunting
├── README.md
├── LICENSE
└── .gitignore
```

## Cara memasang

**Claude.ai (web atau aplikasi)**

1. Unduh repositori ini sebagai ZIP, atau kompres folder `Superwriting` sendiri. Pastikan `SKILL.md` ada di dalam folder tersebut.
2. Buka **Settings**, lalu **Capabilities**, lalu **Skills**.
3. Unggah berkas ZIP dan aktifkan skill.

**Claude Code**

```bash
git clone https://github.com/IrgiAulia/Superwriting.git ~/.claude/skills/superwriting
```

Untuk satu proyek saja, klon ke `.claude/skills/superwriting` di dalam proyek itu.

## Contoh pemakaian

```
Tulis abstract untuk penelitian saya tentang dampak subsidi pupuk terhadap
produktivitas padi di Jawa Tengah. RQ: apakah subsidi meningkatkan hasil panen?
```

```
Sunting paragraf ini. Terlalu banyak kalimat pasif dan antarkalimatnya
tidak nyambung.
```

## Rujukan bahasa

- EYD V: https://ejaan.kemendikdasmen.go.id/
- KBBI: https://kbbi.kemendikdasmen.go.id/
- Bahasa Inggris berpatokan pada Oxford Dictionary.

## Lisensi

Dirilis di bawah lisensi MIT. Lihat berkas [LICENSE](LICENSE).

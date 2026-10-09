# LIST

> Game horor orang pertama berbasis investigasi, dibangun di atas rasa penasaran.

**Status:** Pra-produksi (tahap world-building, belum ada kode)
**Engine:** Unreal Engine
**Genre:** First-person investigation / psychological horror

---

## Tentang Game

LIST mengikuti **Julian Mori**, remaja 17 tahun yang menemukan kamera lama milik ayahnya. Rekaman di dalamnya mengarah ke lapisan sejarah tersembunyi yang terinspirasi Jawa Timur sekitar 1998, dan ke sebuah catatan berisi **21 nama** yang disebut **The LIST**.

Semakin dalam Julian menyelidiki, semakin personal misterinya. Pemain menyusun makna lewat eksplorasi, bukti, detail lingkungan, dan observasi, bukan lewat penjelasan panjang atau sinematik yang terus-menerus.

Target perasaan pemain:

> *"Aku harus tahu apa yang sebenarnya terjadi."*
> bukan *"Aku harus membunuh monster ini."*

## Pilar Desain

- **Rasa penasaran** adalah emosi utama dan penggerak gameplay.
- **Tanpa combat.** LIST bukan FPS konvensional.
- **Horor dari ketidakpastian dan penemuan**, bukan jumpscare terus-menerus.
- **Dunia terasa biasa dulu**, baru anomali muncul pelan-pelan.
- **Environmental storytelling** membawa informasi yang bermakna.
- **Kehadiran first-person tetap dominan.** Sinematik dipakai seperlunya.
- **Aturan horor harus konsisten**, meskipun karakter belum memahaminya.

## Gameplay (Arah Saat Ini)

Loop utama:

**Jelajah → Amati → Interaksi → Temukan bukti → Tafsirkan → Ikuti misteri → Hadapi anomali → Lanjut menyelidiki**

Aksi pemain yang diarahkan: berjalan/eksplorasi, observasi, interaksi, inspeksi, bersembunyi, memakai kamera sebagai bukti cerita, dan investigasi lingkungan.

## Arah Visual & Audio

- **Visual:** fotorealisme membumi dengan presentasi sinematik, dan sesekali tampil lewat rekaman low-fidelity (bodycam, CCTV, VHS, kamera konsumen) saat cerita membutuhkannya.
- **Audio:** ambience, suara terarah, room tone, dan keheningan yang disengaja menjadi sumber utama rasa takut. Musik mendukung atmosfer, bukan memberi aba-aba kapan harus takut.

## Struktur Repo

```
LIST/
├── README.md
└── Docs/
    ├── WORLD_BUILDING_INDEX.md   # Indeks utama world-building
    ├── WORLD_BIBLE.md            # Dokumen acuan dunia
    ├── STORY.md                  # Cerita & struktur bab
    ├── CHARACTERS.md             # Karakter
    ├── RELATIONSHIP_MAP.md       # Peta hubungan
    ├── GAMEPLAY.md               # Arah gameplay
    ├── HORROR_RULES.md           # Aturan horor
    ├── VISUAL.md                 # Arah visual
    └── AUDIO.md                  # Arah audio
```

Mulai dari [`Docs/WORLD_BUILDING_INDEX.md`](Docs/WORLD_BUILDING_INDEX.md) kalau mau membaca dari awal.

## Disiplin Kanon

Semua materi dunia ditandai statusnya supaya brainstorming tidak diam-diam berubah jadi kanon:

| Status | Arti |
| --- | --- |
| `CANON` | Sudah dikonfirmasi, bagian dari dunia |
| `PROVISIONAL` | Dipilih sementara, terbuka untuk revisi |
| `DRAFT` | Rancangan, belum dikunci |
| `IDEA` | Konsep eksplorasi |
| `UNKNOWN` | Sengaja belum ditentukan |
| `REJECTED` | Dibuang, disimpan supaya tidak terpakai lagi |

## Urutan Pengembangan

**Dunia → Cerita → Gameplay → Level Design → Arsitektur Teknis → Kode**

World Bible harus cukup stabil sebelum arsitektur teknis dikunci.

## Yang Masih Terbuka

- Aturan pasti fenomena **SEEN** (pemicu, konsekuensi, batas ancaman)
- Mekanik kamera, hiding, dan save/checkpoint
- Era masa kini, geografi fiksi, dan linimasa lengkap
- Detail peristiwa 1998 dan daftar lengkap 21 nama
- Pipeline rendering dan identitas musik

## Catatan

Dokumen di repo ini adalah bahan desain yang masih berkembang. Materi yang dibuat dengan bantuan AI diperlakukan sebagai alat bantu pengembangan dan **tidak otomatis menjadi kanon**. Arah kreatif dan keputusan akhir tetap di tangan kreator.

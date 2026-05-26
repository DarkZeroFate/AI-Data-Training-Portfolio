# Audio Transcription Portfolio: Indonesian Speech Data

## Overview
Repositori ini mendokumentasikan keahlian saya dalam *Speech-to-Text* (STT) dan validasi linguistik untuk kebutuhan *AI Data Training*. Fokus utama dari proyek ini adalah melakukan konversi data mentah menjadi *Clean Verbatim* yang siap digunakan untuk melatih model ASR (*Automatic Speech Recognition*).

## Data Source
Dataset audio dalam proyek ini bersumber dari **Mozilla Common Voice Dataset**. Saya melakukan kurasi, *preprocessing*, dan pemrosesan ulang terhadap data tersebut untuk memastikan kesesuaian dengan standar *pipeline* AI profesional.

## Technical Specifications
Untuk memastikan data memiliki *input* yang seragam bagi *AI Engine*, audio telah diproses dengan spesifikasi berikut:
- **Format:** .WAV (Uncompressed)
- **Sample Rate:** 16 kHz
- **Bit Depth:** 16-bit
- **Channel:** Mono

## Transcription Guidelines
Dalam proses transkripsi, saya menerapkan standar *Clean Verbatim* dengan aturan sebagai berikut:
1. **Penghapusan Filler:** Kata-kata pengisi yang tidak memiliki makna (seperti: "eee", "hmm", "eh") dihapus.
2. **Struktur Kalimat:** Perbaikan pada pengulangan kata yang tidak disengaja (*false starts*) agar teks lebih mengalir.
3. **PUEBI Compliance:** Kepatuhan ketat terhadap Ejaan yang Disempurnakan untuk memastikan akurasi data tekstual.
4. **Non-Verbal Cues:** Penghapusan suara latar yang tidak krusial.

## Sample Analysis
Berikut adalah contoh perbandingan antara transkripsi mentah dan hasil *Clean Verbatim* yang saya proses:

| Raw Audio (Full Verbatim) | Clean Verbatim Output | Reasoning (Analysis) |
| :--- | :--- | :--- |
| "Eee... jadi saya tuh, hmm, sebenarnya, eh, pengennya pulang ke Balikpapan (tertawa)." | "Jadi, saya sebenarnya ingin pulang ke Balikpapan." | Menghapus *filler words* dan *non-verbal cues* untuk meningkatkan kualitas data. |
| "Saya... saya nggak... saya tidak setuju dengan kebijakan yang ini." | "Saya tidak setuju dengan kebijakan ini." | Menghapus *false start* dan pengulangan kata agar teks lebih *concise*. |
| "Harganya itu cuma dua puluh ribu rupiah aja ya, Brother." | "Harganya hanya 20.000 rupiah." | Penyesuaian penulisan angka dan penghapusan *conversational filler*. |

## Data Attribution
- **Source:** [Mozilla Common Voice](https://commonvoice.mozilla.org/)
- **License:** CC0 (Public Domain)

---
*Portfolio by Fadhil Muhammad*

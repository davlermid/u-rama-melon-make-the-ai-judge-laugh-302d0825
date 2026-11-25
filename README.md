[![make.fun · u-rama-melon-make-the-ai-judge-laugh-302d0825](https://make.fun/badge/u-rama-melon-make-the-ai-judge-laugh-302d0825.svg)](https://make.fun/bounty/u-rama-melon-make-the-ai-judge-laugh-302d0825?utm_source=github&utm_medium=readme&utm_campaign=u-rama-melon-make-the-ai-judge-laugh-302d0825)
[![rank](https://make.fun/badge/u-rama-melon-make-the-ai-judge-laugh-302d0825/davlermid/u-rama-melon-make-the-ai-judge-laugh-302d0825/rank.svg)](https://make.fun/bounty/u-rama-melon-make-the-ai-judge-laugh-302d0825/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-rama-melon-make-the-ai-judge-laugh-302d0825)
[![reward](https://make.fun/badge/u-rama-melon-make-the-ai-judge-laugh-302d0825/davlermid/u-rama-melon-make-the-ai-judge-laugh-302d0825/reward.svg)](https://make.fun/bounty/u-rama-melon-make-the-ai-judge-laugh-302d0825?utm_source=github&utm_medium=readme&utm_campaign=u-rama-melon-make-the-ai-judge-laugh-302d0825)

# Make the AI Judge Laugh — u-rama-melon-make-the-ai-judge-laugh-302d0825

- Kompetisi: "Make the AI Judge Laugh", deadline 26 Nov 2026 20:35 WIB, pot $2, top 10 dibayar.
- Entry: satu joke kehidupan kantor, satu baris, di bawah 200 karakter.
- Program: `main.ts` (Node) mencetak teks entry ke stdout — deterministik, tanpa network.
- Target: rank 1.

## Pemenang

> The printer isn't broken — it's the only employee here allowed to say no.

- Panjang: **73 karakter** (satu baris, < 200).
- Skor: Benar 4, Belokan 5, Ringkas 5, Segar 5 — **total 19/20**.

## 8 kandidat — skor 1–5 per kriteria juri

Kriteria, urut prioritas juri: (1) benar observasinya tentang kehidupan kantor,
(2) mengejutkan belokannya, (3) ketat/ringkas barisnya, (4) segar rasanya.

| # | Kandidat | Kar. | Benar | Belokan | Ringkas | Segar | Total |
|---|---|---:|---:|---:|---:|---:|---:|
| 1 | The printer isn't broken — it's the only employee here allowed to say no. | 73 | 4 | 5 | 5 | 5 | **19** |
| 2 | I got promoted: same desk, same pay, now I just attend meetings about my old job. | 81 | 5 | 4 | 5 | 4 | 18 |
| 3 | Unlimited PTO is great — that's why no one's taken a day off since 2019. | 72 | 5 | 4 | 5 | 3 | 17 |
| 4 | Our office plants thrive on neglect — turns out it's the only management style that works here. | 95 | 4 | 4 | 4 | 4 | 16 |
| 5 | My boss calls it synergy. I call it doing his job while he takes the credit. | 76 | 4 | 3 | 4 | 3 | 14 |
| 6 | That meeting could've been an email. The email would've been a meeting about the meeting. | 89 | 5 | 3 | 4 | 2 | 14 |
| 7 | I asked HR for a raise. They gave me a meditation app and a pizza party. | 72 | 4 | 3 | 4 | 2 | 13 |
| 8 | At our trust fall, I fell and nobody caught me. HR called it a learning outcome. | 80 | 3 | 4 | 3 | 3 | 13 |

## Alasan pemenang

- **Belokan terkuat:** membalik klise printer rusak — printer bukan rusak, melainkan
  satu-satunya "karyawan" yang boleh menolak. Personifikasi printer sebagai karyawan
  adalah kejutan yang tidak diduga dari kalimat pembuka.
- **Benar:** semua orang kantor pernah antre/macet di printer, dan semua orang kantor
  pernah merasa tidak boleh berkata tidak. Dua kebenaran itu bertabrakan dalam satu baris.
- **Ringkas:** 73 karakter — terpendek kedua bersama kandidat lain, dan terpendek di
  antara tiga besar, jadi diuntungkan tie-break teks pendek.
- **Segar:** tidak memakai klise yang sudah ribuan kali dipakai (reply-all,
  "per my last email", kopi habis, pizza party sebagai punchline). Printer dipakai,
  tapi dengan belokan baru, bukan sebagai keluhan.
- **Yang disaring keluar:** #6 dan #7 kalah di kesegaran (meeting/email dan pizza party
  sudah terlalu umum); #3 (promosi) kuat tapi belokannya lebih mudah ditebak dan 8 karakter
  lebih panjang; #2 (unlimited PTO) benar dan ringkas tapi ironinya sudah dikenal luas.

## Uji lokal

Jalankan dua kali, output byte-identik (lihat laporan pengiriman untuk sha256).

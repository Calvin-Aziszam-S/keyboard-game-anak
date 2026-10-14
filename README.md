# Huruf Meletup

Game keyboard untuk balita (sekitar 2–3 tahun). Setiap tombol huruf yang ditekan memunculkan
huruf besar warna-warni, menyebutkan hurufnya, lalu memainkan adegan animasi pendek dengan suara
asli sesuai bendanya. Contohnya: **B**ola ditendang ke gawang, **R**oket meluncur, **T**elur menetas.

Semuanya ada dalam satu file `index.html`, tanpa server, tanpa instalasi, dan tetap jalan tanpa internet.
Hanya font Fredoka yang diambil dari Google Fonts; kalau offline, game memakai font cadangan.

## Cara main

1. Buka `index.html` di browser (Chrome, Edge, Firefox, atau Safari).
2. Klik **Ayo Main!**
3. Biarkan si kecil menekan tombol apa saja:
   - **A–Z**: huruf muncul, disebutkan dengan suara, lalu adegan animasi bendanya diputar.
   - **0–9**: balon bernomor muncul satu per satu untuk berhitung.
   - **Tombol lain** (spasi, Enter, panah): kembang api bintang.
   - **Setiap 10 huruf**: hujan konfeti dan sorakan.
4. Di HP dan tablet, keyboard huruf besar muncul otomatis di bagian bawah layar. Tombol **123**
   menampilkan angka, **★** memunculkan kembang api. Sentuh langit untuk huruf acak, atau sentuh
   gelembung untuk memecahkannya.

Tips untuk orang tua:
- Tombol ⛶ membuat layar penuh supaya si kecil tidak keluar dari game.
- Tombol ⌨️ menampilkan atau menyembunyikan keyboard huruf di layar.
- Tombol 🔊 mematikan bunyi efek, dan 🗣️ mematikan suara sebut huruf.
- Di iPhone/iPad, layar penuh tidak tersedia di Safari. Pakai **Bagikan → Tambahkan ke Layar Utama**
  supaya game terbuka seperti aplikasi tanpa bilah browser. Pastikan tombol senyap (silent) tidak aktif,
  karena iPhone membisukan suara game saat mode senyap.

## Daftar adegan

| Huruf | Adegan | Huruf | Adegan |
|---|---|---|---|
| A | Apel jatuh dari pohon | N | Nanas berjoget |
| B | Anak menendang bola ke gawang | O | Onta berjalan di padang pasir |
| C | Cicak menangkap nyamuk | P | Monyet berayun mengambil pisang |
| D | Domba melompati pagar | Q | Mahkota turun ke kepala ratu |
| E | Es krim bertumpuk | R | Roket meluncur |
| F | Kamera memotret | S | Sapi berkata "Mooo!" |
| G | Gajah menyemprotkan air | T | Telur menetas jadi anak ayam |
| H | Harimau mengintip lalu mengaum | U | Ular meliuk-liuk |
| I | Ikan melompat dari kolam | V | Biola memainkan "Bintang Kecil" |
| J | Jeruk meletup jadi jus | W | Kelinci mencabut wortel |
| K | Kucing mengejar bola benang | X | Xilofon dipukul berurutan |
| L | Lebah mengitari bunga | Y | Yoyo naik turun |
| M | Mobil melaju dan membunyikan klakson | Z | Zebra berlari kencang |

## Suara

Suara sebut huruf memakai text-to-speech bawaan browser, dalam Bahasa Indonesia bila tersedia.
Efek suaranya berupa rekaman asli berlisensi **CC0 (domain publik)** dari
[BigSoundBank](https://bigsoundbank.com) dan [Freesound](https://freesound.org). Klip-klip itu
dipotong pendek dan ditanam langsung di `index.html`. Beberapa efek kartun kecil (cicak, yoyo,
*boing*) dibuat dengan Web Audio API.

| Suara | Sumber |
|---|---|
| A gemerisik pohon | [Freesound #540278](https://freesound.org/s/540278/) |
| A apel jatuh | [Freesound #149418](https://freesound.org/s/149418/) |
| B tendangan bola | BigSoundBank #1044 |
| B peluit wasit | [Freesound #538422](https://freesound.org/s/538422/) |
| B sorakan "Yeah" | BigSoundBank #0237 |
| D embik domba | BigSoundBank #2343 |
| D embik domba 2 | BigSoundBank #2345 |
| E es krim jatuh | [Freesound #447910](https://freesound.org/s/447910/) |
| F jepretan kamera | BigSoundBank #2394 |
| G terompet gajah | [Freesound #527845](https://freesound.org/s/527845/) |
| H auman harimau | [Freesound #263115](https://freesound.org/s/263115/) |
| I cebur air | BigSoundBank #1529 |
| J jeruk pecah | [Freesound #500912](https://freesound.org/s/500912/) |
| J tuang jus | [Freesound #693585](https://freesound.org/s/693585/) |
| K meong | BigSoundBank #1890 |
| K meong kecil | BigSoundBank #0494 |
| L dengung lebah | BigSoundBank #1000 |
| M mesin mobil | [Freesound #458461](https://freesound.org/s/458461/) |
| M klakson | BigSoundBank #0258 |
| N drum | [Freesound #371192](https://freesound.org/s/371192/) |
| P monyet uu-aa | [Freesound #67355](https://freesound.org/s/67355/) |
| Q terompet kerajaan | [Freesound #456966](https://freesound.org/s/456966/) |
| R roket meluncur | [Freesound #182794](https://freesound.org/s/182794/) |
| S mooo | BigSoundBank #2386 |
| T telur retak | [Freesound #250133](https://freesound.org/s/250133/) |
| T anak ayam | [Freesound #519193](https://freesound.org/s/519193/) |
| U desis ular | [Freesound #553374](https://freesound.org/s/553374/) |
| V nada biola G4 | [Freesound #10662](https://freesound.org/s/10662/) |
| W kelinci mengunyah | [Freesound #482732](https://freesound.org/s/482732/) |
| W wortel tercabut | [Freesound #392624](https://freesound.org/s/392624/) |
| X & angka: nada xilofon C4 | [Freesound #617324](https://freesound.org/s/617324/) |
| Z derap kuda | BigSoundBank #0611 |
| Z ringkikan | BigSoundBank #0863 |
| huruf meletup | [Freesound #202230](https://freesound.org/s/202230/) |

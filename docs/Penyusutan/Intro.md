--- 
sidebar_position: 1 
---

## 1. Definisi 
:::tip Pejelasan
Penyusutan merupakan alokasi yang sistematis atas nilai perolehan suatu
aset tetap yang dapat disusutkan *(depreciable assets)* selama masa
manfaat aset yang bersangkutan. Penyusutan merupakan penyesuaian nilai
yang terus menerus sehubungan dengan penurunan kapasitas suatu aset,
baik penurunan kualitas, kuantitas, maupun nilai. Penurunan kapasitas
terjadi karena aset digunakan dalam operasional suatu entitas.
Penyusutan dilakukan dengan mengalokasikan biaya perolehan suatu aset
menjadi beban penyusutan secara periodik sepanjang masa manfaat aset.
Tanpa penyusutan, nilai aset tetap dalam neraca akan lebih saji
(*overstated*). Dalam Buletin Teknis SAP Nomor 5 tentang Penyusutan
disebutkan bahwa adanya penyusutan dimaksudkan untuk menggambarkan
penurunan kapasitas dan manfaat yang diakibatkan pemakaian aset tetap
dalam kegiatan pemerintahan.

Tidak semua aset tetap perlu disusutkan karena tidak semua jenis aset
tetap mengalami penurunan nilai. Beberapa jenis aset tetap justru dapat
meningkat nilainya seiring waktu. Dalam Peraturan Pemerintah Nomor 71
Tahun 2010, disebutkan bahwa tanah dan konstruksi dalam pengerjaan
merupakan dua jenis aset tetap yang tidak disusutkan.
:::
## 2. Pihak-Pihak Yang Terkait

Pihak-pihak yang terkait dalam sistem akuntansi penyusutan dan
amortisasi aset tetap/aset tidak berwujud antara lain adalah:

-   Bendahara Barang atau Pengurus Barang SKPD

    Dalam sistem akuntansi penyusutan dan amortisasi, pengurus barang
    bertugas untuk menyiapkan dan menyampaikan dokumen-dokumen atas
    penyusutan dan amortisasi aset tetap/aset tidak berwujud.

-   Pejabat Penatausahaan Keuangan SKPD

    Dalam sistem akuntansi penyusutan dan amortisasi, pejabat
    penatausahaan keuangan SKPD bertugas untuk melakukan proses akuntansi
    penyusutan yang dimulai dari jurnal hingga penyajiannya laporan
    keuangan SKPD.

## 3. Dokumen Yang Digunakan

Dokumen-dokumen yang digunakan dalam sistem akuntansi penyusutan adalah:

-   Bukti Memorial

    Dokumen ini merupakan dokumen sumber untuk melakukan penyusutan dan
    amortisasi aset tetap/aset tidak berwujud.

## 4. Pencatatan Jurnal
Beban penyusutan dan amortisasi dijurnal setiap akhir periode (bulanan,
triwulanan, semesteran atau tahunan). Setiap penyusutan akan dijurnal
sebagai berikut:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian                              | Debit | Kredit |
|----------|----------|-----------|---------------------------|--------|--------|
| XXX     | XXX         | XXX           | Beban Penyusutan dan Amortisasi     | XXX   |        |
|         |             | XXX           | Akumulasi Penyusutan dan Amortisasi |       | XXX    |

Beban penyusutan/beban amortisasi merupakan alokasi penyusutan yang akan
dilaporkan dalam Laporan Operasional entitas. Seperti layaknya beban
lainnya, beban penyusutan/beban amortisasi merupakan akun nominal yang
pada akhir periode harus ditutup sehingga saldonya nol di setiap awal
periode. Sedangkan akumulasi penyusutan dan amortisasi akan dilaporkan
dalam neraca. Akumulasi penyusutan dan amortisasi merupakan akun nominal
sehingga angkanya tidak akan pernah ditutup di akhir tahun.

Akumulasi penyusutan dan amortisasi merupakan total dari penyusutan
suatu aset tetap/aset tidak berwujud yang telah dibebankan. Akumulasi
penyusutan dan amortisasi menjadi pengurang aset tetap/aset tidak
berwujud dalam neraca dimana harga perolehan aset tetap/aset tidak
berwujud yang telah dikurangi dengan akumulasi penyusutannya dan
amortisasinya menjadi nilai buku *(book value)* aset tetap/aset tidak
berwujudnya tersebut.

Dalam transaksi pembelian aset tetap yang menggunakan mekanisme LS, aset
tetap diakui ketika telah terjadi serah terima barang dari pihak ketiga
dengan SKPD terkait. Berdasarkan bukti transaksi berupa Berita Acara
Penerimaan Barang atau Berita Acara Serah Terima, PPK-SKPD membuat bukti
memorial aset tetap yang kemudian diotorisasi oleh Pengguna Anggaran.
Berdasarkan dokumen-dokumen tersebut, PPK-SKPD akan mengakui adanya
penambahan aset tetap dengan jurnal:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian              | Debit | Kredit |
|---------|-------------|---------------|---------------------|-------|--------|
| XXX     | XXX         | XXX           | Aset Tetap          | XXX   |        |
|         |             | XXX           | Utang Belanja Modal |       | XXX    |

Selanjutnya dilaksanakan proses penatausahaan untuk pembayaran perolehan
aset tetap tersebut hingga SP2D LS terbit. Berdasarkan SP2D-LS tersebut
PPK-SKPD akan membuat jurnal sebagai berikut:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian              | Debit | Kredit |
|---------|-------------|---------------|---------------------|-------|--------|
| XXX     | XXX         | XXX           | Utang Belanja Modal | XXX   |        |
|         |             | XXX           | R/K PPKD            |       | XXX    |

Jurnal LRA

| Tanggal | Nomor Bukti | Kode Rekening | Uraian        | Debit | Kredit |
|---------|-------------|---------------|---------------|-------|--------|
| XXX     | XXX         | XXX           | Belanja Modal | XXX   |        |
|         |             | XXX           | Perubahan SAL |       | XXX    |

Apabila pembelian aset tetap dilakukan dengan mekanisme UP/GU/TU,
pengakuannya dilakukan berdasarkan bukti pembayaran (bukti belanjanya).
Berdasarkan bukti tersebut, PPK-SKPD akan menjurnal:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian                       | Debit | Kredit |
|----------|----------|-----------|---------------------------|--------|--------|
| XXX     | XXX         | XXX           | Aset Tetap                   | XXX   |        |
|         |             | XXX           | Kas di Bendahara Pengeluaran |       | XXX    |

Jurnal LRA

| Tanggal | Nomor Bukti | Kode Rekening | Uraian        | Debit | Kredit |
|---------|-------------|---------------|---------------|-------|--------|
| XXX     | XXX         | XXX           | Belanja Modal | XXX   |        |
|         |             | XXX           | Perubahan SAL |       | XXX    |

Aset tetap dinilai dengan biaya perolehan. Apabila penilaian menggunakan
biaya perolehan tidak memungkinkan, maka digunakan nilai wajar pada saat
perolehan. Untuk aset tetap yang dibangun dengan cara swakelola, biaya
perolehannya meliputi biaya langsung untuk tenaga kerja, bahan baku, dan
biaya tidak langsung termasuk biaya perencanaan dan pengawasan,
perlengkapan, tenaga listrik, sewa peralatan, dan semua biaya lainnya
yang terjadi berkenaan dengan pembangunan aset tetap tersebut.

## 5. Pengeluaran Setelah Perolehan

**Suatu pengeluaran setelah perolehan atau pengeluaran pemeliharaan akan dikapitalisasi jika memenuhi kriteria sebagai berikut:**

1. Menambah manfaat ekonomi atas aset tetap yang dipelihara yang dapat berupa: 

-   bertambah ekonomis/efisien, dan/atau

-   bertambah umur ekonomis, dan/atau

-   bertambah volume, dan/atau

-   bertambah kapasitas produksi.

**2. Nilai pengeluaran belanja atas pemeliharaan aset tetap tersebut harus sama dengan atau melebihi nilai satuan minimum kapitalisasi aset tetap. Nilai satuan minimum kapitalisasi adalah penambahan nilai aset tetap dari hasil pengembangan, reklasifikasi, renovasi, dan restorasi.** 

Jurnal Pengeluaran setelah Perolehan sebagai berikut:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian                       | Debit | Kredit |
|----------|----------|-----------|---------------------------|--------|--------|
| XXX     | XXX         | XXX           | Aset Tetap                   | XXX   |        |
|         |             | XXX           | Kas di Bendahara Pengeluaran |       | XXX    |

Jurnal LRA

| Tanggal | Nomor Bukti | Kode Rekening | Uraian        | Debit | Kredit |
|---------|-------------|---------------|---------------|-------|--------|
| XXX     | XXX         | XXX           | Belanja Modal | XXX   |        |
|         |             | XXX           | Perubahan SAL |       | XXX    |

## 6. Pelepasan Aset Tetap
Pelepasan aset tetap dapat terjadi karena proses penghapusan aset tetap
yang dapat diikuti dengan proses pemindahtanganan, seperti penjualan,
maupun pemusnahan aset tetap.

Untuk penghapusan aset tetap dengan pemusnahan, PPK SKPD akan membuat
bukti memorial yang dibuat berdasarkan SK Kepala Daerah tentang
penghapusan aset tetap. Setelah bukti memorial tersebut diotorisasi oleh
pengguna anggaran, PPK SKPD kemudian membuat jurnal:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian               | Debit | Kredit |
|---------|-------------|---------------|----------------------|-------|--------|
| XXX     | XXX         | XXX           | Akumulasi Penyusutan | XXX   |        |
|         |             | XXX           | Aset Lainnya         | XXX   |        |
|         |             | XXX           | Aset tetap           |       | XXX    |

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian                              | Debit | Kredit |
|----------|----------|-----------|---------------------------|--------|--------|
| XXX     | XXX         | XXX           | Defisit Penghapusan Aset Non Lancar | XXX   |        |
|         |             | XXX           | Aset Lainnya                        |       | XXX    |

Sedangkan untuk penghapusan aset tetap yang diikuti dengan proses
penjualan, SKPD harus menyerahkan aset tetap tersebut kepada PPKD, sebab
kewenangan untuk menjual aset tetap ada di PPKD. Namun demikian, PPK
SKPD tetap mencatat penghapusan aset tetap tersebut. Jurnal penghapusan
aset tetap untuk aset yang akan diserahkan ke PPKD untuk kemudian
dijual, yaitu:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian               | Debit | Kredit |
|---------|-------------|---------------|----------------------|-------|--------|
| XXX     | XXX         | XXX           | Akumulasi Penyusutan | XXX   |        |
|         |             | XXX           | Aset Lainnya         | XXX   |        |
|         |             | XXX           | Aset tetap           |       | XXX    |

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian       | Debit | Kredit |
|---------|-------------|---------------|--------------|-------|--------|
| XXX     | XXX         | XXX           | R/K PPKD     | XXX   |        |
|         |             | XXX           | Aset Lainnya |       | XXX    |

Setelah menerima pelimpahan aset dari SKPD, Fungsi Akuntansi PPKD
menjurnal:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian       | Debit | Kredit |
|---------|-------------|---------------|--------------|-------|--------|
| XXX     | XXX         | XXX           | Aset Lainnya | XXX   |        |
|         |             | XXX           | R/K SKPD     |       | XXX    |

Pada saat aset tersebut telah dijual oleh PPKD, berdasarkan bukti
transaksi penjualan, Fungsi Akuntansi PPKD menjurnal:

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian                            | Debit | Kredit |
|----------|----------|-----------|---------------------------|--------|--------|
| XXX     | XXX         | XXX           | Kas di Kas Daerah                 | XXX   |        |
|         |             | XXX           | Aset Lainnya                      | XXX   |        |
|         |             | XXX           | Surplus Penjualan Aset non Lancar |       | XXX    |

Jurnal LRA

| Tanggal | Nomor Bukti | Kode Rekening | Uraian                                                            | Debit | Kredit |
|----------|----------|-----------|---------------------------|--------|--------|
| XXX     | XXX         | XXX           | Perubahan SAL                                                     | XXX   |        |
|         |             | XXX           | Pendapatan dari Hasil Penjualan Aset Daerah Yang Tidak Dipisahkan |       | XXX    |

atau

Jurnal LO dan Neraca

| Tanggal | Nomor Bukti | Kode Rekening | Uraian                            | Debit | Kredit |
|----------|----------|-----------|---------------------------|--------|--------|
| XXX     | XXX         | XXX           | Kas di Kas Daerah                 | XXX   |        |
|         |             | XXX           | Defisit Penjualan Aset Non Lancar | XXX   |        |
|         |             | XXX           | Aset Lainnya                      |       | XXX    |

Jurnal LRA

| Tanggal | Nomor Bukti | Kode Rekening | Uraian                                                            | Debit | Kredit |
|----------|----------|-----------|---------------------------|--------|--------|
| XXX     | XXX         | XXX           | Perubahan SAL                                                     | XXX   |        |
|         |             | XXX           | Pendapatan dari Hasil Penjualan Aset Daerah Yang Tidak Dipisahkan |       | XXX    |

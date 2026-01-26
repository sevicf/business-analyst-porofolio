# Business Requirement Document (BRD)

## Project Background
Bendahara RT membutuhkan system untuk mempermudah pencatatan keluar masuk keuangan RT.
Ada iuran bulanan untuk kebersihan dan keamanan dengan tagihan yang berbeda-beda tergantung kondisi yang ada.
Kondisi terkait lingkungan RT antara lain:
1. Kavling Tanah:
  • Terdapat 90 kavling tanah, terdiri dari:
    i.    Blok A1 – A20
    ii.   Blok B1 – B20
    iii.  Blok C1 – C20
    iv.   Blok D1 – D20
    v.    Blok E1 – E10
  • Ukuran kavling Blok E adalah 200m² dan sisanya 100m². Setiap kavling bisa jadi sudah berdiri bangunan dan berpenghuni, tidak berpenghuni
    ataupun tanah kosong / sedang dibangun.
   
2. Iuran RT:
  • Iuran dihitung berdasarkan luas kavling per 100m² dengan ketentuan:
      i. Dihuni:
          1. Iuran Kebersihan: Rp. 100.000,-
          2. Iuran Keamanan: Rp. 100.000,-
     ii. Tidak dihuni:
          1. Iuran Kebersihan: Rp. 100.000,-
          2. Iuran Keamanan: Rp. 50.000,-
    iii. Kavling kosong / sedang dibangun:
          1. Iuran Kebersihan: Rp. 50.000,-
          2. Iuran Keamanan: Rp. 50.000,-
   • Semua pemilik kavling di Blok E pasti memiliki 2 kavling di blok lainnya. 1 kavling tersebut berpenghuni (disewakan) dan 1 kavling kosong / sedang dibangun.

## Business Objectives
- Bisa memiliki Laporan Pemasukkan dan Pengeluaran Per Bulan secara Summary 
- Bisa memiliki Laporan Pemasukan dan Pengeluaran Per Bulan secara Detail – dapat terlihat siapa saja
  yang sudah membayar, belum membayar, atau menunggak beberapa bulan.

## Scope
In Scope:
- Data Kavling
- Data Warga
- Master Iuran
- Pengeluaran / Pemasukkan Kas
- Report

Out of Scope:
- Financial posting

## Stakeholders
- Bendahara (User)
- Ketua RT (Approver / Viewer)
- Warga

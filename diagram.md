```mermaid
  sequenceDiagram;
  Best Friend->>LO_Pariwisata: Bro, hotel A gak muncul;
  loop Web Wilkerstat;
      LO_Pariwisata->>LO_Pariwisata: Edit Data Landmark Pariwisata;
  end;
  Note right of LO_Pariwisata: Semua bisa edit ini!;
  LO_Pariwisata-->>Best Friend: Ok sudah beres ya, om. Ditunggu sinkronisasinya 1 - 2 jam!;
  Best Friend->>LO_Pariwisata: Kenapa ada 2 usaha yang sama di webentry updating ya?;
  Diseminasi->>LO_Pariwisata: Berikut permintaan data direktori dari Kementrian P;
  LO_Pariwisata-->>Best Friend: Ada beberapa kemungkinan penyebabnya kalau ini;
  LO_Pariwisata-->>Diseminasi: Baik, kami olah dahulu!;
```

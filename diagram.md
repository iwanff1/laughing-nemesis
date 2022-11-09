```mermaid
  sequenceDiagram;
  Best Friend->>LO_Pariwisata: Bro, hotel A gak muncul;
  loop Web Wilkerstat;
      LO_Pariwisata->>LO_Pariwisata: Edit Data Landmark Pariwisata;
  end;
  Note right of LO_Pariwisata: Semua bisa edit ini!;
  LO_Pariwisata-->>Best Friend: Sudah beres, om!;
  LO_Pariwisata->>Bos: Maaf pak, data direktori kapan ditarik ya?;
  Bos-->>LO_Pariwisata: November ini!;
```

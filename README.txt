APLIKASI OFFLINE IPA PELAYANAN KEFARMASIAN PUSKESMAS
Identitas: apt. Fendy Prasetyawan, S.Farm., M.Farm.

Isi:
- index.html: aplikasi offline
- README.txt: petunjuk

Fitur: input wawancara, 40 atribut x 2 penilaian (Importance dan Performance), identitas responden, penyimpanan lokal, cari/edit/hapus, rata-rata atribut, tingkat kesesuaian, klasifikasi dan grafik matriks IPA, CSV, backup/restore JSON. Tidak ada data fiktif yang disertakan.

Laptop:
1. Ekstrak ZIP.
2. Buka index.html dengan Chrome/Edge/Firefox.
3. Input jawaban aktual.
4. Ekspor CSV untuk Excel/SPSS/RStudio; ekspor JSON sebagai cadangan.

Android:
Buka index.html dari pengelola file dengan browser dan lakukan uji penyimpanan sebelum penelitian. Dukungan penyimpanan file lokal berbeda antar-browser. Data tidak tersinkron otomatis ant perangkat; ekspor JSON dari perangkat asal lalu impor di perangkat tujuan.

Skala:
Importance 1 sangat tidak penting; 2 tidak penting; 3 cukup penting; 4 penting; 5 sangat penting.
Performance 1 sangat tidak baik; 2 tidak baik; 3 cukup baik; 4 baik; 5 sangat baik.

Analisis:
Rata-rata Importance dan Performance dihitung per atribut; tingkat kesesuaian atribut = rerata Performance / rerata Importance x 100%. Matriks default memakai grand mean atribut sebagai titik potong, dan pengguna dapat mengubah titik potong pada halaman Analisis IPA. Nyatakan pilihan titik potong pada metode penelitian. Analisis ini deskriptif, bukan uji validitas/reliabilitas.

Privasi:
Gunakan kode responden, jangan simpan nama/NIK/nomor rekam medis. Data disimpan di localStorage browser dan dapat hilang jika data browser dihapus. Cadangkan secara berkala dan lindungi file ekspor.

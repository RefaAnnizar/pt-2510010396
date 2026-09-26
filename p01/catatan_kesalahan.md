# Catatan Kesalahan Praktikum 5

| Berkas | Jenis kesalahan | Pesan yang muncul | Cara kamu mengetahuinya |
|---     |---              |---                |---                      |
| k1_siantaks.cpp | Sintaks | error: expected ',' or ';' before 'std' | Compiler menunjukkan kesalahan karena tanda ; setelah int nilai = 80 hilang. |
| k2_nama.cpp | Nama/identifier | error: 'bonus' was not declared in this scope | Compiler menunjukkan bahwa variabel bonus belum dideklarasikan. |
| k3_runtime.cpp | Runtime | Tidak ada pesan saat compile | Program bermasalah ketika dijalankan dengan input 0 karena terjadi pembagian dengan nol. |
| k4_logika.cpp | Logika | Tidak ada pesan error | Program berjalan, tetapi hasil rata-rata salah. Seharusnya 81.67, bukan 81. |

## Kesimpulan

Kesalahan yang paling berbahaya menurut saya adalah
kesalahan runtime karena program dapat berhasil di-compile,
tetapi mengalami masalah ketika dijalankan dengan input tertentu.
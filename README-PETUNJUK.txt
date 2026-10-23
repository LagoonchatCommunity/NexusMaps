NEXUS MAPS - PROYEK APK ANDROID

PENTING:
- Workflow akan mengambil index.html yang sudah ada di root repo:
  https://github.com/LagoonchatCommunity/NexusMaps
- APK ini adalah debug APK untuk dipasang dan dites, bukan rilis Play Store.
- Fitur peta, pencarian tempat, dan rute memerlukan internet.
- GPS hanya berjalan setelah izin lokasi diberikan dan aplikasi dibuka.
- HTML asli saat ini berjudul NEXUS DRIVE. Paket Android memakai label NEXUS MAPS;
  tulisan di dalam halaman HTML tetap mengikuti isi index.html asli.

CARA MEMASANG FILE KE GITHUB:
1. Ekstrak ZIP ini di komputer.
2. Buka repo https://github.com/LagoonchatCommunity/NexusMaps
3. Klik Add file > Upload files.
4. Buka folder hasil ekstrak, lalu unggah isi folder proyek (bukan folder induknya).
   Pastikan folder tersembunyi .github ikut diunggah agar workflow aktif.
5. Commit changes ke branch main.
6. Buka tab Actions di repo GitHub.
7. Pilih "Build NEXUS MAPS APK", lalu klik Run workflow jika belum berjalan otomatis.
8. Tunggu sampai proses selesai dengan tanda hijau.
9. Buka run yang berhasil, cari bagian Artifacts, lalu unduh
   nexus-maps-debug-apk.zip.
10. Ekstrak ZIP artifact itu; di dalamnya ada app-debug.apk. Pindahkan ke HP Android
    lalu buka untuk memasang. Android mungkin meminta izin memasang aplikasi dari sumber ini.

Kalau upload folder .github sulit:
- Pastikan folder .github/workflows/android.yml ada di repo.
- GitHub Actions tidak akan berjalan jika file workflow tidak masuk ke repo.

Jika build gagal, buka run Actions yang merah dan kirim screenshot bagian error terakhir.

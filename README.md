# CoalTrack — Demo Web

Hosting **GitHub Pages** untuk demo web **CoalTrack** — absensi anti-curang + penggajian
untuk operasi tambang batu bara, produk **Ksatria Bintang Samudra**.

### ▶️ [demo.coaltrack.id](https://demo.coaltrack.id) · Produk: [coaltrack.id](https://coaltrack.id)

---

## ⚠️ Repo ini hanya hasil build

Semua berkas di sini (`main.dart.js`, `assets/`, `canvaskit/`, `flutter_bootstrap.js`, `index.html`, …)
adalah **keluaran kompilasi Flutter Web** (`flutter build web`) yang diterbitkan dari
repositori sumber privat setiap kali ada build baru.

**Jangan mengedit berkas hasil build secara manual** — perubahan apa pun akan tertimpa pada
penerbitan berikutnya. Perbaikan dilakukan di repo sumber, lalu di-build ulang dan diterbitkan.

Berkas yang memang milik repo ini dan boleh disunting: `README.md`, `CNAME` (`demo.coaltrack.id`),
dan `.nojekyll` (mematikan pemrosesan Jekyll agar berkas Flutter disajikan apa adanya).

---

## 👥 4 persona demo

Di layar Login tersedia empat tombol persona — masuk langsung, tanpa sandi dan tanpa server:

| Persona | Yang bisa dilihat |
|---|---|
| **Karyawan** | Absen (wajah + GPS), riwayat, slip gaji, izin & cuti, notifikasi |
| **Kepala Divisi** | Monitor absensi timnya + antrean persetujuan (absen offline / ditandai) |
| **HRD** | Lintas divisi, direktori karyawan, payroll run, slip PDF, kirim email/Telegram |
| **Superadmin** | Akses penuh + Pengaturan Payroll (maker-checker, jejak audit) |

Demo berjalan dalam **7 bahasa** (Inggris, Indonesia, Melayu, Mandarin, Arab dengan RTL penuh,
Thai, Filipino) dan tema gelap/terang.

---

## 🔒 Data demo

Semua yang tampil di demo adalah **data contoh yang dibuat di perangkat pengunjung**.
**Tidak ada data karyawan asli** — tidak ada nama, foto, gaji, atau koordinat karyawan
sungguhan di repo ini maupun di demo. Menutup tab menghapus sesi demo.

Demo ditujukan untuk melihat alur aplikasi; sebagian fitur produksi (mis. absen tervalidasi
server, pengiriman slip massal) memerlukan backend yang online.

---

## English (short)

This repository only **hosts the compiled CoalTrack web demo** on GitHub Pages; it is published
from a private source repository on every new build. Everything here is **build output — do not edit
it by hand**, it will be overwritten on the next publish. Only `README.md`, `CNAME`, and
`.nojekyll` belong to this repo.

Try it at **[demo.coaltrack.id](https://demo.coaltrack.id)** — four demo personas (Employee,
Division Head, HR, Superadmin) sign in without a password or server. All data shown is
**sample data generated on the visitor's device; no real employee data exists here**.

Product: **[coaltrack.id](https://coaltrack.id)** · Support: **support@coaltrack.id**

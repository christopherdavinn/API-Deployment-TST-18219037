Tugas API Deployment 
II3160 - Integrated System Technology

Nama: Christopher Davin
NIM : 18219037  

Kelompok: 
Faisal Helmi Wicaksono     / 18219025
Christopher Davin Leoputra / 18219037
Ari Pardomuan Manurung     / 18219045
Edwin Stanic Prasetyo      / 18219079

API perancangan sistem pendaftaran Studi.in (SisTar)

Bagian saya: 

// username admin : admin
// password admin : admin

List Tutor
- listtutor
     admin dapat mengakses seluruh data pendaftar tutor yang sudah masuk ke database
     berisi id tutor, nama, email, dan status (pengecekan data oleh admin)
- datatutor
     admin dapat mengakses data pendaftar tutor secara spesifik (1 pendaftar saja)

Verify Tutor
- verify tutor
     status pendaftar tutor yang lolos pemeriksaan / seleksi menjadi tutor akan diubah oleh admin menjadi verified 
- unverify tutor
     status pendaftar tutor yang tidak lolos pemeriksaan / seleksi menjadi tutor akan diubah oleh admin menjadi verified 

Delete tutor
- Menghapus data tutor pada database oleh admin
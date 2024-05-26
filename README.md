# Tugas-Individu_SI-Daycare
Daycare merupakan penyedia layanan perawatan perkembangan pada bayi. Terdapat 3 aktor di sistem informasi daycare, yaitu orangtua/wali, staff, admin
Admin bertanggung jawab atas semua aktivitas pada Sistem Informasi Daycare
Staff Karyawan bertanggung jawab atas semua kebutuhan bayi, perkembangan bayi, aktivitas bayi
Orang tua/Wali sebagai pengguna orang tua bertanggung jawab atas pemantauan bayi selama berada pada Daycare
# Use Case
Use case pada SI Daycare adalah masing-masing aktor memiliki peran dalam mengakses Sistem Daycare
![Use case drawio](https://github.com/NadiyahQasamah/Tugas-Individu_SI-Daycare/assets/145907307/d0397495-4e9d-456d-b7ea-c531375054b6)
# Class Diagram
Class diagram terdapat 3 aktor dengan field dan method masing-masing, terdapat class login yang bisa diakses semua aktor, dan terdapat class Transaksi sebagai hubungan antara class Admin dengan class Orang tua/Wali
![Class Diagram drawio](https://github.com/NadiyahQasamah/Tugas-Individu_SI-Daycare/assets/145907307/b1534930-00d7-4b8e-bf17-c25b45d670c1)
# ERD
Hubungan dari masing-masing aktor yaitu :
1. Admin dengan Orang tua/Wali adalah transaksi, satu Admin(one) bisa melayani banyak transaksi Orang tua/Wali (many), kardinalitasnya one to many
2. Orang tua/Wali dan Staff Karyawan adalah menitipkan, banyak Orang tua/Wali (many) bisa menitipkan kepada satu Staff Karyawan pengasuh (one), kardinalitasnya many to one
![ERD Daycare](https://github.com/NadiyahQasamah/Tugas-Individu_SI-Daycare/assets/145907307/7527b204-843a-4161-91d6-84db5be8f14a)

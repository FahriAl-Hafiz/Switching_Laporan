 # Laporan Hasil Praktikum

Implementasi Verifikasi NAT dengan Cisco Packet Tracer

1. Pendahuluan

Tujuan praktikum ini adalah memverifikasi penggunaan Network Address Translation (NAT) dalam jaringan menggunakan Cisco Packet Tracer. Fokus kami adalah memastikan bahwa ketika host di VLAN 2 atau VLAN 3 mengakses alamat domain jarkom.com, NAT berfungsi dengan baik dan hasilnya dapat dilihat pada ROUTER_I.

2. Langkah-langkah Praktikum

Konfigurasi VLAN pada Switches:

Buat VLAN 2 dan VLAN 3 di setiap switch.
Pastikan VLAN telah diberi nama dengan benar.
Konfigurasi NAT pada Router:

Tetapkan NAT sebagai sumber inside.
Definisikan aturan NAT untuk meneruskan paket melalui interface FastEthernet0/0.
Pastikan access-list mengizinkan lalu lintas dari semua host (permit any).
Verifikasi Konfigurasi:

Periksa konfigurasi VLAN menggunakan perintah "show ip vlan" di setiap switch.
Gunakan "show running-config" pada SWITCH dan ROUTER_I untuk memastikan konfigurasi yang tepat.
Periksa status NAT menggunakan "show ip nat statistics" pada ROUTER_I.
Pengiriman Paket Data:

Kirim paket data dari sumber ke tujuan pada setiap PC, baik dalam VLAN yang sama maupun berbeda.
Pastikan akses ke jarkom.com dari host dalam VLAN 2 atau VLAN 3 berhasil dan NAT berfungsi dengan benar.

![ss1](https://github.com/FahriAl-Hafiz/Switching_Laporan/assets/126375451/e83e83a0-e5e7-43a4-adc4-67b8e0a9d28b)


3. Kesimpulan

Dengan mengikuti langkah-langkah modul secara cermat, kami berhasil memverifikasi penggunaan NAT dalam jaringan kami. Setiap langkah diikuti dengan teliti untuk memastikan konektivitas antara host dalam VLAN yang berbeda berjalan dengan baik, dan NAT beroperasi sesuai yang diharapkan.

![ss2](https://github.com/FahriAl-Hafiz/Switching_Laporan/assets/126375451/4124014a-e8b6-4ca2-ae24-2b57756b09ed)





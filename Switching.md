# Switcing


Perintah "show ip vlan" tidak ditemukan secara langsung dalam antarmuka Cisco IOS. Lebih sering digunakan adalah "show vlan" atau "show vlan brief" pada switch yang menjalankan Cisco IOS. Ini memberikan informasi tentang konfigurasi VLAN pada switch, seperti ID VLAN, nama VLAN, dan port yang terhubung ke VLAN yang spesifik.
![2024-03-14_15-40](https://github.com/piogenty13/Switcing/assets/126374059/2c7a0e59-7b13-4d41-93ec-02308d8a63d4)


Perintah "show running-config" pada switch menampilkan konfigurasi VLAN, port, dan trunk. Namun, di ROUTER_1, perintah yang sama memperlihatkan konfigurasi antarmuka, rute, protokol routing, NAT, DHCP, dan ACLs.
![2024-03-14_15-41](https://github.com/piogenty13/Switcing/assets/126374059/e0717eb9-4ef4-42e7-87ff-a3dd589ecbc0)


Perintah "show dhcp pool" menampilkan detail pool DHCP, termasuk rentang IP, subnet mask, gateway default, DNS server, dan lease time.
![Gambar WhatsApp 2024-03-14 pukul 15 55 33_d9dbf9ca](https://github.com/piogenty13/Switcing/assets/126374059/687619a5-6450-4800-9e98-bb204fa712d7)
![Gambar WhatsApp 2024-03-14 pukul 15 55 47_0e4e7549](https://github.com/piogenty13/Switcing/assets/126374059/5ef6e3c0-b7a0-4c95-ab49-baa0992edc25)


Perintah "show ip nat statistics" memberikan informasi rinci, termasuk jumlah translasi aktif, hitungan translasi NAT, dan penggunaan sumber daya. Hal ini sangat berguna untuk mengevaluasi kinerja NAT dan mendiagnosis masalah koneksi.
![2024-03-14_15-43](https://github.com/piogenty13/Switcing/assets/126374059/e2a2959b-fdae-49c0-911f-49d58cc37255)

Diperlukan router atau switch layer 3 untuk melakukan routing antar VLAN (InterVLAN routing). Paket dari sumber akan dikirim ke gateway (router atau switch L3), yang kemudian akan mengarahkannya ke VLAN tujuan. Dalam konfigurasi NAT, jika tujuannya berada di luar jaringan lokal seperti Internet, router akan melakukan NAT pada paket tersebut. Ini melibatkan penggantian alamat IP sumber internal dengan alamat IP publik router sebelum mengirimkannya ke jaringan eksternal. Untuk memastikan komunikasi data berjalan dengan baik, setiap perangkat di jaringan harus dikonfigurasi dengan benar, termasuk VLAN, routing, dan NAT.
![Gambar WhatsApp 2024-03-14 pukul 15 57 25_f37536fa](https://github.com/piogenty13/Switcing/assets/126374059/cd9ddc6f-4294-4b0f-be91-ee51d3929caf)
![Gambar WhatsApp 2024-03-14 pukul 15 57 32_ecb1454b](https://github.com/piogenty13/Switcing/assets/126374059/c8d6de67-ec67-4718-af20-0943214a6bf0)



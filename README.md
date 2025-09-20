# RouterOS License

Router hardware MikroTik yang menjalankan RouterOS sudah dilengkapi dengan lisensi RouterOS secara default. Jika Anda telah membeli perangkat berbasis RouterOS, tidak perlu melakukan apa pun terkait lisensi.

Adapun jenis lisensi dan fiturnya pada mikrotik yaitu sebagai berikut:
| Level Number | 0 (Trial mode) | 1 (Free Demo) | 3 (WISP CPE) | 4 (WISP) | 5 (WISP) | 6 (Controller) |
| :----------- | :------------: | :-----------: | :----------: | :------: | :------: | :------------: |
| Price | No Key | Registraion Required | Not For Sale | $45 | $95 | $250 |
| Wireless AP mode (PtMP) | 24h trial | - | no | yes | yes | yes |
| PPPoE tunnels	| 24h trial	| 1	| 200	| 200	| 500	| Unlimited |
| PPTP tunnels	| 24h trial	| 1	| 200	| 200	| 500	| Unlimited |
| L2TP tunnels	| 24h trial	| 1	| 200	| 200	| 500	| Unlimited |
| OVPN tunnels	| 24h trial	| 1	| 200	| 200	| Unlimited	| Unlimited |
| EoIP tunnels	| 24h trial |	1	| Unlimited	| Unlimited	| Unlimited	| Unlimited |
| VLAN interfaces	| 24h trial	| 1	| Unlimited	| Unlimited	| Unlimited	| Unlimited |
| Queue rules	| 24h trial	| 1	| Unlimited	| Unlimited	| Unlimited	| Unlimited |
| HotSpot active users | 24h trial | 1 | 1 | 200 | 500 | Unlimited |
| User manager active session	| 24h trial | 1	| 10 | 20	| 50 | Unlimited |
| Bonding interfaces | 24h trial | 1 | Unlimited | Unlimited | Unlimited | Unlimited |
| RADIUS | 24h trial | - | Unlimited | Unlimited | Unlimited | Unlimited |


Kita bisa melihat Lisensi RouterOS pada bagian System > Lisence

![License](License.png)

Bisa juga dilihat pada mode CLI/terminal dengan menggunakan perintah > system license print
  
    [admin@MikroTik] > system license print
      software-id: W716-FUJ3
           nlevel: 4
         features:
    [admin@MikroTik] >

Kesimpulan: 
Lisensi RouterOS adalah sistem perizinan yang digunakan untuk mengatur fitur dan kapasitas pada perangkat lunak RouterOS milik MikroTik. Terdapat beberapa level lisensi, yang masing-masing memberikan akses ke fitur dan kemampuan jaringan yang berbeda, seperti jumlah tunnel, jumlah pengguna hotspot, dukungan routing, dan fitur-fitur tambahan lainnya.

Pemilihan level lisensi bergantung pada kebutuhan jaringan pengguna—mulai dari penggunaan kecil (rumahan atau SOHO) hingga skala besar (ISP atau enterprise). Lisensi ini bersifat permanen dan tidak memerlukan biaya tahunan, kecuali untuk upgrade atau pembelian tambahan.

Lisensi MikroTik dapat dibeli secara resmi melalui distributor atau langsung dari MikroTik, dan sangat penting untuk memastikan legalitas serta dukungan teknis penuh.

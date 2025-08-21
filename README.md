
---

## Versi 1 — Laravel Smart Plant Dashboard

### Deskripsi
Dibangun dari nol dengan Laravel untuk backend, Node.js untuk data polling, dan Chart.js untuk visualisasi.  
Sistem ini menampilkan parameter tanaman dalam bentuk **real-time dashboard** yang interaktif.

### Cara Kerja Sistem
- **Data Polling** → Mengambil data setiap 3 detik via Node.js.  
- **Processing & Storage** → Data diproses dan disimpan di database Laravel.  
- **Realtime Visualization** → Data divisualisasikan di dashboard dengan Chart.js.  
- **Status Logic** → Menentukan status tanaman *Sehat* atau *Tidak Sehat*.  

### Preview
- Tampilan Dashboard  
- Potongan kode polling & logic proses data  

### Tech Stack
- Laravel  
- Node.js  
- Chart.js  
- MySQL  

---

## Versi 2 — Smartics Smart Plant Dashboard

### Deskripsi
Menggunakan **Smartics**, sebuah platform low-code IoT dashboard builder.  
Lebih cepat untuk membangun visualisasi data tanpa banyak menulis kode.

### Cara Kerja Sistem
- **Data Source Setup** → Konfigurasi sumber data & parameter.  
- **Widget Configuration** → Menambahkan gauge, bar chart, dan trend view.  
- **Realtime Visualization** → Menampilkan data secara langsung tanpa refresh.  
- **Custom Display** → Menambahkan label & elemen visual untuk memperjelas kondisi tanaman.  

### Preview
- Tampilan Dashboard  
- Konfigurasi Widget  

### Tech Stack
- Smartics IoT Platform (Low-Code)  

## Insight
Dua pendekatan ini menunjukkan perbedaan **Full Coding vs Low-Code**:
- **Laravel** → lebih fleksibel, custom, tapi butuh effort coding tinggi.  
- **Smartics** → lebih cepat dibuat, namun terbatas pada fitur bawaan platform.  

Dengan kedua metode ini, aku belajar bagaimana membangun solusi IoT monitoring baik dari sisi **pengembangan manual** maupun **low-code platform**.


## 🏷️ Tags
`#IoT` `#WebDevelopment` `#Dashboard` `#Laravel` `#NodeJS` `#ChartJS` `#LowCode` `#Smartics`

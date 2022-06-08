Nama	: Matthew Kevin Siahaan

NIM	: 195150300111040

Kelas	: Arsitektur Jaringan Terkini – A

Tugas Akhir Arsitektur Jaringan Terkini


Tugas 1

![image](https://user-images.githubusercontent.com/99637930/172615615-ecfa34fa-222c-4eff-982e-c7ddc6feb1ac.png)
![image](https://user-images.githubusercontent.com/99637930/172615676-fb4e30e6-542f-4a56-b14b-c20d83f78916.png)

Pada tugas 1 ini, saya diajarkan untuk membuat sebuah 1 instance EC2 di AWS Console. Dengan spesifikasi sebagai berikut yaitu Instance Type: t2.medium, AMI: Ubuntu Server 22.04 LTS 64 Bit, allow SSH, allow HTTP, allow HTTPS, Security Group dibuka untuk TCP Port 8080 dan TCP Port 8081, dan konfigurasi storage 30 GiB, gp3.

Tugas 2

![image](https://user-images.githubusercontent.com/99637930/172615876-a30da770-70e2-4d8f-819d-c1df0c6f5e19.png)
![image](https://user-images.githubusercontent.com/99637930/172615948-40ad119d-ca94-437a-8a88-146a68866a4a.png)

Pada tugas 2, saya ditugaskan untuk membuat sebuah program sederhana untuk custom topology, lalu membuat flow h1 dapat terhubung dengan h2 dan juga diuji koneksi antara host dan switch.

Tugas 3

![image](https://user-images.githubusercontent.com/99637930/172616131-10cb2f34-604a-4d5a-a3e6-6fa9d6b7254d.png)
![image](https://user-images.githubusercontent.com/99637930/172616220-4636d840-63db-4f6c-820c-111d3e7c0047.png)
![image](https://user-images.githubusercontent.com/99637930/172616305-b0d8e04c-9547-4246-972d-7ea351513837.png)
![image](https://user-images.githubusercontent.com/99637930/172616374-d583f456-5b03-4241-8f99-ddf43e39d1a4.png)
![image](https://user-images.githubusercontent.com/99637930/172616484-10453d84-a7e6-453b-8043-2a3bebbf7f37.png)

Pada tugas 3, membuat sebuah load balancer. Load Balancing adalah proses pembagian beban traffic sebuah aplikasi atau server. Dengan load balancer, beban traffic tidak akan dibebankan kepada beberapa jalur koneksi. Hal ini mempercepat waktu respons server Anda dan mencegah dari overloading. Dengan begini, kinerja server Anda akan lebih maksimal tidak peduli berpa banyak traffic yang Anda dapatkan.

Tugas 4

Saat menulis kode “$ ryu-manager --observe-links dijkstra_Ryu_controller.py” Di terminal 1
![image](https://user-images.githubusercontent.com/99637930/172617246-2f253fdc-0ac6-4350-ab68-34b22440ca13.png)

Tampilan terminal 2 Setelah menulis Kode “$ sudo python3 topo-spf_lab.py” di terminal 2
 ![image](https://user-images.githubusercontent.com/99637930/172617454-42863eb8-79b7-4cb4-8f72-486fef0ddfad.png)

Tampilan Terminal 1 dan 2 setelah mengetik “h1 ping -c 4 h4” Di terminal 2 Untuk melakukan Pengecekan Konektivitas.
•	Terminal 1

![image](https://user-images.githubusercontent.com/99637930/172617911-54aeeda2-70dc-4a55-91b4-fc77adff80f6.png)
![image](https://user-images.githubusercontent.com/99637930/172617945-295e56aa-a97f-4990-ba03-74d3305c2555.png)
![image](https://user-images.githubusercontent.com/99637930/172618025-50c4b781-8040-4346-aa05-b63936957af0.png)

•	Terminal 2

![image](https://user-images.githubusercontent.com/99637930/172618085-f7055984-1252-4036-bfb7-d0fa71f97141.png)
 
Tampilan Terminal 1 dan 2 setelah mengetik “h5 ping -c 4 h6” Di terminal 2 Untuk melakukan Pengecekan Konektivitas Untuk yang kedua kali nya.

•	Terminal 1

![image](https://user-images.githubusercontent.com/99637930/172618747-80243870-f77c-4757-9d29-8cc83069833b.png)
![image](https://user-images.githubusercontent.com/99637930/172618843-b85c4460-4d01-4c5d-b21a-13faa621b595.png)
![image](https://user-images.githubusercontent.com/99637930/172618938-39219aca-c449-4ea6-8d8a-3b2a5eb8d3e8.png)

•	Terminal 2

![image](https://user-images.githubusercontent.com/99637930/172619017-a253f74a-b6fe-44d1-a051-23d41995bd66.png)
 
Pada tugas 4, pengaplikasian SPF Routing. SPF adalah algoritma perutean di mana router menghitung jalur terpendek antara setiap pasangan node dalam jaringan. Protokol Open Shortest Path First (OSPF) didasarkan pada algoritma Shortest Path First (SPF).



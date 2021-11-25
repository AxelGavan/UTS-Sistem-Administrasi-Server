**UJIAN TENGAH SEMESTER**

Sistem Administrasi Server

Axel Gavan (1202190004)



1. Download ISO Installer windows server 2022

   - Klik link yang ada pada soal UTS

     ![1](https://user-images.githubusercontent.com/94977405/143465811-0c5ef7c5-001a-4cbc-bcc0-45025c0da65b.png)

   - Pilih download the ISO kemudian ikuti step by stepnya

     ![2](https://user-images.githubusercontent.com/94977405/143465829-d4d52e07-0d6a-425e-b1b8-25423d08a5ac.png)

   - Pilih bahasa kemudian klik "download"

     ![3](https://user-images.githubusercontent.com/94977405/143465846-be9b890a-8a40-48ef-a34a-0c542151106c.png)

2. Langkah-langkah instalasi :

   - Buka VirtualBox kemudian klik "Machine>New" kemudian setting seperti gambar dibawah ini kemudian next

     ![4](https://user-images.githubusercontent.com/94977405/143465852-fcf45ccc-04b3-4dfd-9aa9-130d62ce2bd4.png)

    ![5](https://user-images.githubusercontent.com/94977405/143465864-f2944a25-6099-42db-a51b-7a50bdfba11a.png)
    
![6](https://user-images.githubusercontent.com/94977405/143465872-b4482b7d-475f-43e0-bbc7-3b2e569b7006.png)

![7](https://user-images.githubusercontent.com/94977405/143465903-2e693e97-d71a-450a-8ae8-f890300206f2.png)

![8](https://user-images.githubusercontent.com/94977405/143465911-9de11601-c58b-439b-8456-2a92e7e9f303.png)

![9](https://user-images.githubusercontent.com/94977405/143465938-80cf2c93-5970-426a-8f6c-48f8e0879a3d.png)

![10](https://user-images.githubusercontent.com/94977405/143465955-c598de86-33c9-45bf-87be-83ee1269f823.png)

![11](https://user-images.githubusercontent.com/94977405/143465983-c4174cff-4f15-4cd8-a98a-345b6ff73011.png)

![12](https://user-images.githubusercontent.com/94977405/143466080-bccfbcb3-e201-40f4-9465-b3648d8eef89.png)

     

     

   - Setting zona waktu Indonesia

     ![13](https://user-images.githubusercontent.com/94977405/143466091-360ebfd3-4b95-409e-8e8c-90c6e5374859.png)

   - Klik "Install now"

     ![14](https://user-images.githubusercontent.com/94977405/143466112-6fac4793-1341-4377-92e3-2e0afb0233eb.png)

   - Pilih WIndows Server 2022 Datacenter Evaluation (desktop experience) kemudian klik "next"

     ![15](https://user-images.githubusercontent.com/94977405/143466132-32cd87e3-9906-4ff0-998a-3908fb2be1a6.png)
   - Klik centang dan "next"

     ![16](https://user-images.githubusercontent.com/94977405/143466150-7b4530e5-c513-4798-9d0d-01f116f20206.png)
   - Pilih "Custom: Install Microsoft Server Operating System only (advanced)"

     ![17](https://user-images.githubusercontent.com/94977405/143466189-feb43183-13d6-41ab-bb02-8bbdb58eb493.png)

   - Kemudian klik "Next"

     ![18](https://user-images.githubusercontent.com/94977405/143466204-52ad4136-3b89-4227-afc2-6177e2d5b771.png)

   - Tunggu hingga proses install selesai

     ![19](https://user-images.githubusercontent.com/94977405/143466209-4f658f7f-d35f-49ae-9c04-4f9957ac45e9.png)

   - Setelah proses install selesai maka akan muncul tampilan seperti ini

     ![20](https://user-images.githubusercontent.com/94977405/143466267-13415dd9-7ef3-4420-b7a8-46f11df6b15a.png)

   - Buat password kemudian klik "Input>Keyboard>Insert Ctrl+Alt+Del"

     ![21](https://user-images.githubusercontent.com/94977405/143466283-7ce62a36-ceef-4290-915a-69f04fb3acf1.png)

     ![22](https://user-images.githubusercontent.com/94977405/143466293-37a6a158-be48-42d3-a5ac-6d8a0541a896.png)

   - Kemudian masuk ke menu "Devices >Insert Guest Additions CD Image>file explorer>cd Drive Virtual box> lalu pilih VBoxWindowsAdditions

     ![23](https://user-images.githubusercontent.com/94977405/143466297-fe4829ad-31d2-4ff4-ad34-6d13153c5634.png)

     ![24](https://user-images.githubusercontent.com/94977405/143466303-137b87e3-27fd-4169-88b6-794f88d47982.png)

   - Maka muncul seperti ini,dan ikuti step by step seperti digambar lalu klik "next"

     ![25](https://user-images.githubusercontent.com/94977405/143466331-8524b8f7-3a1c-4656-94fc-a56109c77bf1.png)

     ![26](https://user-images.githubusercontent.com/94977405/143466341-86d5dbbb-1e66-420f-8f1e-b47d1b93e7e9.png)

   - Klik "Install"

     ![27](https://user-images.githubusercontent.com/94977405/143466351-8c4093df-6a5b-4198-a155-6c68c3306ea8.png)
   - Klik "finish"

     ![28](https://user-images.githubusercontent.com/94977405/143466356-6cd81c23-5e81-4232-bf59-d21a3d8926f1.png)

   - Kemudian Reboot now, lalu masukkan password melalui "Input>Keyboard>Insert Ctrl+Alt+Del"

     ![29](https://user-images.githubusercontent.com/94977405/143466384-54977127-8b74-47ed-94aa-1ab87b547153.png)

   - Ubah nama computer pada windows powershell dengan mengetik "rename-computer -Newname Server2022”

     ![30](https://user-images.githubusercontent.com/94977405/143466394-94cc562c-949c-4c76-803a-2616431034e2.png)

   - Lalu masuk ke server klik "manage", kemudian pilih Add Roles and Features dan klik "next"

     ![31](https://user-images.githubusercontent.com/94977405/143466411-63be807b-34fd-4480-80bf-4e0ab7ebdc4b.png)

   - Pilih Role-Based or feature-based installation kemudian next

     ![32](https://user-images.githubusercontent.com/94977405/143466433-fa8d43da-022f-4ecb-8da0-d536eb91d469.png)

   - Klik “Select a server from the server pool” untuk memilih direktori penyimpanan lokal. Lalu “Next”

     ![33](https://user-images.githubusercontent.com/94977405/143466451-442de555-237f-4a82-aed7-dc305de5895c.png)

   - Selanjutnya, berikan tanda centang di kotak “Active Directory Domain Services”. Saat anda mencentang kotak, disebelah kanan muncul penjelasan singkat tentang ADDS dan cara kerjanya. Lalu klik “Add Features”

     ![34](https://user-images.githubusercontent.com/94977405/143466459-38505535-8666-4cc2-88cd-057ab7ed9068.png)

   - Kemudian centang kotak “Group Policy Management” dan tekan tombol “Next”

     ![35](https://user-images.githubusercontent.com/94977405/143466493-4054d61d-fe83-46e5-b264-28ae99f4bb10.png)

   - Klik "next"

     ![36](https://user-images.githubusercontent.com/94977405/143466500-725ab193-2d29-44bc-bde6-c54696101a59.png)

   - Klik "install"

     ![37](https://user-images.githubusercontent.com/94977405/143466517-cedc0787-6704-4c93-8fd4-d91bc3c65608.png)

   - Tunggu hingga proses instalasi selesai kemudian melakukan konfigurasi ADDS

     ![38](https://user-images.githubusercontent.com/94977405/143466524-e9e2d0ce-41d5-4dc7-af1e-8c6754e61842.png)

   - Kemudian lakukan install **DNS Server** dengan masuk ke menu “Server Manager”. Lalu pilih opsi “Manage>Add Roles and Features”. Kemudian klik “Next”. Stepnya sama seperti instalasi active directory. Kita perlu menginstal dan mengonfigurasi peran Active Directory dan server DNS untuk bekerja bersama. 

     ![39](https://user-images.githubusercontent.com/94977405/143466532-5abb1f5e-844e-441e-bfc2-afd9832efd79.png)

   - Kemudian lakukan install **Net Framework 3.5** centang "Net Framework 3.5 features"

     ![40](https://user-images.githubusercontent.com/94977405/143466546-5bb0e132-60cb-4ee7-bf12-684555fddabc.png)

   - Klik "Next"

     ![41](https://user-images.githubusercontent.com/94977405/143466551-466dcb63-992c-4298-a1cf-cf5852c73178.png)

   - Klik "Install"

     ![42](https://user-images.githubusercontent.com/94977405/143466554-8dcbebc4-e725-48a6-baec-c9b80ec1064a.png)

   - Setting ip static di cmd menggunakan command> sconfig

     ![43](https://user-images.githubusercontent.com/94977405/143466559-d63dbc90-3ea3-4717-9626-6d0bb4ce0116.png)
     
     ![44](https://user-images.githubusercontent.com/94977405/143466581-4b70185d-7be3-44b5-a490-d851fc63ddce.png)

     ![45](https://user-images.githubusercontent.com/94977405/143466596-496d21fb-e598-4984-8272-bc4e0d21d3fd.png)

     ![46](https://user-images.githubusercontent.com/94977405/143466602-e7f7d954-17ba-48f4-a4bb-0817a145cbe2.png)

   - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan

     ![47](https://user-images.githubusercontent.com/94977405/143466609-50358629-99c7-4d94-b37b-fe6d28ded1d9.png)

   - Klik “Promote this server to a domain controller" untuk konfigurasi ADDS kemudian pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain “axel.com”

     ![48](https://user-images.githubusercontent.com/94977405/143466619-e5ae1906-c4dd-412f-b18d-ec93e5c77ed5.png)

   - Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password.

     ![49](https://user-images.githubusercontent.com/94977405/143466634-551689f8-5a90-4bcb-88f1-efd4b980e3e6.png)

   - Lewati bagian DNS Options, lalu klik “Next”
   
     ![50](https://user-images.githubusercontent.com/94977405/143466642-52a6d963-f140-4f54-b01a-a22e8b9d6c50.png)
   
   - Mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan
   
     ![51](https://user-images.githubusercontent.com/94977405/143466653-ed478953-ef8e-47cd-b130-3cb62842e159.png)
   
   - Lewati bagian Paths, klik “Next”
   
     ![52](https://user-images.githubusercontent.com/94977405/143466660-162cf597-9c5e-49ba-81d6-eeab61649aed.png)
   
   - Cek konfigurasi yang ditentukan pada Review Options, jika suda ok. Klik “Next”
   
     ![53](https://user-images.githubusercontent.com/94977405/143466671-555d0704-a93b-46d6-96b5-293680b6dd76.png)
   
   - Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan
   
     ![54](https://user-images.githubusercontent.com/94977405/143466681-fc170ef0-ddcf-42c4-bce0-cf913c8a5739.png)
   
   - Kemudian login menggunakan password administrator
   
     ![55](https://user-images.githubusercontent.com/94977405/143466694-b31ce2ac-888f-40c0-9fa3-42c87d2c80d2.png)
   
   - Untuk mengecek hasil konfigurasi, buka cmd dan ketikkan “netdom query fsmo"
   
     ![56](https://user-images.githubusercontent.com/94977405/143466701-1d4b2579-b40e-450c-b2a8-117f6c72b3a6.png)
   
   - Setelah login dengan Active Directory Domain Controller Anda, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS yang disukai
   
     ![57](https://user-images.githubusercontent.com/94977405/143466715-36449572-a0e5-4818-99c2-5c55ebb98bfc.png)
     
     

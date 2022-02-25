# install_tigergraph_ubuntu

Instalasi Tigergraph 1 node di OS ubuntu
 
1. Buat virtual machine pada virtual box
	
	
	
2. Kemudian isi Ram minimum 8GB

3. Kemudian setting cpu minimal 2 core pada case ini saya buat 3 core cpu 

4. Pada tab network ubah menjadi Bridged Adapter

5. Jika sudah close lalu start virtual machine nya, kemudian akan masuk ke tampilan profil setup isi sesuai kebutuhan lalu done

6. Pilih untuk auto install openSSH (opsional) jika ingin install openSSH secara manual hapus centang, pada case ini saya install auto openSSH

7. Berikut tampilan log pada instalasi OS ubuntu,jika sudah selesai instalasi langsung klik tab reboot untuk reboot OS yang baru di install



8. Jika sudah login user dan password yang sudah dibuat,lalu cek ip dengan commnd 
# ip a

9. Tahap selanjutnya install net-tools 
# sudo apt install net-tools

10. Jika sudah lanjutkan dengan transfer file tigergraph.targ.gz ke OS dengan Filezilla

11. Kemudian cek pada os jika sudah complete transfer file, kemudian ekstrak file tar.gz tersebut dengan jalankan command
# tar -xzf tigergraph-3.4.0-offline.tar.gz

12. Setelah di esktrak masuk ke direktori file tigergraph yang sudah di extract tadi lalu jalankan command install lalu tunggu sampai proses instalasi selesai
# sudo ./install.sh -n 



13. Jika instalasi sudah selesai login ke user tigergraph kemudian cek status 
# su – tigergraph
# gadmin status




14. Tembak ip dengan browser pake ip OS yang di install untuk membuka Graph Studio


 
 
 
 
 
 
 
 
 
 
 
 
![image](https://user-images.githubusercontent.com/77326619/155685941-94b35450-cd06-4e60-92ae-4dc8a06471c2.png)

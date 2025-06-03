# ✅ Daftar Pengujian Manual - Mini Habit Tracker

1. **Jalankan aplikasi** (`flutter run`).<br>
![image](https://github.com/user-attachments/assets/d542dc0d-1859-4c20-a90a-ea56267dc4b1)

2. **Uji Strikethrough**:  
![image](https://github.com/user-attachments/assets/11ad9956-101b-4c28-8525-f0d10726f139)

3. **Uji Tambah Habit**:
   a. Klik tombol `+` di AppBar.<br>
   ![image](https://github.com/user-attachments/assets/16b64071-5ae1-482b-a252-0302d95e67dd)

   b. Coba simpan tanpa mengisi nama *(validasi harus mencegah)*.<br>
   ![image](https://github.com/user-attachments/assets/eab8e2bb-8668-4052-803a-265a06e34a56)
   
   c. Isi form dan simpan.<br>
    ![image](https://github.com/user-attachments/assets/667aa0f0-c64d-4f94-a15c-c58c8325867a)

5. **Uji Edit Habit**:
   a. Klik menu tiga titik pada habit, pilih **"Edit"**.<br>
   ![image](https://github.com/user-attachments/assets/d2a170f2-22a4-4e6e-b42f-86edde092a67)

   b. Dialog harus muncul dengan data habit tersebut.<br>
   ![image](https://github.com/user-attachments/assets/bdac2742-10ed-43f0-b522-071572609376)

   c. Ubah nama/deskripsi dan simpan.<br>
    ![image](https://github.com/user-attachments/assets/8d3e02cc-0358-40e0-ae80-5bc472978964)

6.	Uji Progress Bar: Pastikan progress di AppBar terupdate setelah menambah, menghapus, atau mencentang habit.<br>
![image](https://github.com/user-attachments/assets/ea7f4b17-5946-40a5-8033-cf449ba5e5a3)

7.	Uji Reset: Tombol reset harus mengembalikan semua isDone ke false.
   ![image](https://github.com/user-attachments/assets/04b94d63-2df6-4079-92ea-97f9706661cb)

8. Uji Ephemeral State: Tutup paksa aplikasi dan buka kembali. Semua perubahan (tambah, edit, hapus) seharusnya hilang, dan hanya data dari habits.json yang tampil.<br>
![image](https://github.com/user-attachments/assets/d1013d2a-e409-4d86-9e91-35fc67625b7b)

9. Amati Output print: Perhatikan konsol debug. Kapan saja print('build ${habit.name}') muncul? Bagaimana ini berkaitan dengan aksi Anda (check, add, edit, delete)?
  ![image](https://github.com/user-attachments/assets/53737577-8362-43ab-8ebf-fba66c60be12)

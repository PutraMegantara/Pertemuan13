# Pertemuan13
# Pertemuan 13
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <table border="1">
        <tr>
            <th> Nama</th>
            <th>NIM</th>
            <th>Kelas</th>
        </tr>
        <tr>
            <td>Putra Megantara</td>
            <td>312110251</td>
            <td>TI.21.A.1</td>
        </tr>
    </table>
</body>
</html>

### TUGAS PERTEMUAN 13
•Implementasikan penggunaan eksepsi pada lab-lab
sebelumnya untuk mengatasi error yang ditimbulkan.<P>

Saya menggunakan eksepsi pada tugas sebelum nya di bagian input data.
Berikut adalah tambahan kode eksepsi.<P>

    while True:
            try:
                nim = int(input("Masukan NIM\t: "))
                if nim == "":
                    print("NIM tidak boleh kosong")
                else:
                    break
            except:
                print("Harap Masukan Angka")
            else:
                break
            
    while True:
            try:
                nilai = int(input("Masukan Nilai\t: "))
                if nilai == "":
                    print("Nilai tidak boleh kosong")
                else:
                    break
            except:
                print("Harap Masukan Angka")
            else:
                break

Dengan menambahakan eksepsi maka:<P>
- Saat input data kosong maka akan meminta untuk memasukan data kembali<P>
- Saat input NIM dan Nilai menggunakan karakter maka program akan meminta untuk memasukan angka.<P>
  ![Gambar1](screenshot/ss1.PNG)
    
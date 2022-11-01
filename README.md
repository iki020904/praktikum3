#latihan3
#### Hallo Nama Saya Muhammad Rifqi aziz. Saya membuat ini untuk memenuhi tugas saya. ####
# Latihan Python di Pycharm #
### DAFTAR ISI <br>
| No | Description | Link |
| ----- | ----- | ---- |
| 1 | Cara Installasi Pycharm| [Click Here](#Cara-Installasi-Pycharm)|
| 2 | Latihan 1 | [Click Here](#Latihan-1) |
| 3 | Latihan 2 | [Click Here](#Latihan-2) |
| 4 | Latihan 3 | [Click Here](#Latihan-3) |
| 5 | Menghitung Luas Dan Keliling Lingkaran | [Click Here](#Menghitung-Luas-Dan-Keliling-Lingkaran) |
| 6 | Flowchart Menghitung luas dan keliling lingkaran | [Click Here](#Flowchart-Menghitung-luas-dan-keliling-lingkaran) |

# Cara Installasi Pycharm #
1. Anda harus install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows , Dan anda pilih yang Community

![DownLoad](https://user-images.githubusercontent.com/115864496/199218013-7b0a5efe-bfab-49d0-9dc6-14552d694cae.png)


2. Anda next saja semua perintahnya
3. Jika sudah selesai maka program siap di gunakan

# Cara Menjalankan Pycharm #
# Latihan 1 #
1. Pertama-tama anda harus Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini.

![image](https://user-images.githubusercontent.com/115864496/199218188-c0e52cb1-393c-42ed-bd1f-b47933da5f8c.png)

![image](https://user-images.githubusercontent.com/115864496/199218261-035a3ceb-c2ff-4c66-9a6f-fbaf3afd05ce.png)

2. Selanjutnya anda membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan

![image](https://user-images.githubusercontent.com/115864496/199218323-feee82bd-eadc-48aa-aff7-63700c32ebac.png)

![image](https://user-images.githubusercontent.com/115864496/199218385-ed3a737e-5e7c-4b2e-a048-b40e0260f17a.png)

3. Anda masukan code dari Latihan1 anda lalu Run

        # penggunaan end
        print('A', end='')
        print('B', end='')
        print('C', end='')
        print()
        print('X')
        print('Y')
        print('Z')

        # penggunaan separator
        w, x, y, z = 10, 15, 20, 25
        print(w, x, y, z)
        print(w, x, y, z, sep=',')
        print(w, x, y, z, sep='')
        print(w, x, y, z, sep=':')
        print(w, x, y, z, sep='-----')

        # string format
        print(0, 10**0)
        print(1, 10**1)
        print(2, 10**2)
        print(3, 10**3)
        print(4, 10**4)
        print(5, 10**5)
        print(6, 10**6)
        print(7, 10**7)
        print(8, 10**8)
        print(9, 10**9)
        print(10, 10**10)

        # string format
        print('{0:>3} {1:>16}'.format(0, 10**0))
        print('{0:>3} {1:>16}'.format(1, 10**1))
        print('{0:>3} {1:>16}'.format(2, 10**2))
        print('{0:>3} {1:>16}'.format(3, 10**3))
        print('{0:>3} {1:>16}'.format(4, 10**4))
        print('{0:>3} {1:>16}'.format(5, 10**5))
        print('{0:>3} {1:>16}'.format(6, 10**6))
        print('{0:>3} {1:>16}'.format(7, 10**7))
        print('{0:>3} {1:>16}'.format(8, 10**8))
        print('{0:>3} {1:>16}'.format(9, 10**9))
        print('{0:>3} {1:>16}'.format(10, 10**10))
        
 ![image](https://user-images.githubusercontent.com/115864496/199218659-b9717d9f-0f05-41bb-b2c6-40e09f84d9e6.png)
     
 ![image](https://user-images.githubusercontent.com/115864496/199218700-f001e359-0a7f-404c-b026-bd1f701fa2e6.png)

- Hasil Run :

![Hasil Ss latihan 1 di pycharm](https://user-images.githubusercontent.com/115864496/199218791-da3d67b6-29a3-40aa-8356-5f7a83f0a3cb.png)

![Hasil Ss 2](https://user-images.githubusercontent.com/115864496/199218867-0ea83f65-0da4-4028-becd-be3be93f1c5e.png)

# Latihan 2 #
1. Anda masukan code latihan 2 anda lalu Run

        a=input("masukkan nilai a:")
        b=input("masukkan nilai b:")
        print("variable a=",a)
        print("variable b=",b)
        print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

        #koversi nilai variable
        a=int(a)
        b=int(b)
        print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
        print("hasil pembagian {1}/{0}=%s".format(a,b) %(a/b))
        
 ![Hasil Ss Latihan 2 di pycharm](https://user-images.githubusercontent.com/115864496/199219022-bc1c2e88-923f-4bfc-872b-9fe04f9ae39c.png)

# Latihan 3 #
1. Anda masukan code seperti dibawah ini dan lalu Run

        string = ""

        x = int(input("Masukkan angka :"))
        bar = x
        # Looping Baris
        while bar >= 0:
                # Looping Kolom Spasi Kosong
                kol = bar
                while kol > 0:
                        string = string + "   "
                        kol = kol - 1
                # Looping Kolom Bintang Sisi Kiri		
                kiri = 1
                while kiri < (x - (bar-1)):
                        string = string + " * "
                        kiri = kiri + 1		
                # Looping Kolom Bintang Sisi Kanan
                kanan = 1
                while kanan < kiri -1:
                        string = string + " * "
                        kanan = kanan + 1	

                string = string + "\n\n"
                bar = bar - 1

        bar = 1	
        # Looping Baris
        while bar <= x:
                kol = bar+1
                # Looping Kolom Spasi Kosong
                while kol > 1:
                        string = string + "   "
                        kol = kol - 1
                # Looping Kolom Bintang Sisi Kiri	
                kiri = 0
                while kiri < (x - bar):
                        string = string + " * "
                        kiri = kiri + 1	
                # Looping Kolom Bintang Sisi Kanan
                kanan = kiri	
                while kanan > 1:
                        string = string + " * "
                        kanan = kanan - 1

                string = string + "\n\n"
                bar = bar + 1
        print (string)
 ![Latihan 3 ss 2](https://user-images.githubusercontent.com/115864496/199219209-1123b25d-2203-4b6a-8cf1-81aeb3f0394d.png)

![Latihan 3 ss 22](https://user-images.githubusercontent.com/115864496/199219296-39e91192-b17f-4491-88eb-dc418756296a.png)

- Hasil Run :

![Hasil Latihan 3 ss1](https://user-images.githubusercontent.com/115864496/199219366-5bdff372-020a-4cb3-ace7-da718b165677.png)

![Hasil Latihan 3 ss 2](https://user-images.githubusercontent.com/115864496/199219399-3829fca4-60cd-46d4-bab3-dc561d5c6d3e.png)

# Menghitung Luas dan Keliling Lingkaran #
1. Masukan code di bawah ini lalu run

        import math

        r = float(input("Masukan Jari-jari : "))

        luas = math.pi * (r * r)
        keliling = 2 * math.pi * r

        print("Luas Lingkaran \t\t= ", luas)
        print("Keliling Lingkaran\t= ", keliling)   
        
![Latihan 4 ss](https://user-images.githubusercontent.com/115864496/199219581-477b0e1e-4ff0-4ae1-a11b-da47295115c6.png)

# Flowchart Menghitung Luas dan Keliling Lingkaran #

![image](https://user-images.githubusercontent.com/115864496/199219705-4aa29097-62fd-4f39-ab83-a46efe0b5223.png)

### Terima Kasih ###

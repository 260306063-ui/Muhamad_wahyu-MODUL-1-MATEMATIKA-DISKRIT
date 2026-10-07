#mengitung luas persegi panjang 1

panjang = float(input("masukkan panjang : "))
lebar = float(input("masukkan lebar:  "))

luas = panjang * lebar
print =("luas persegi panjang = ",luas)

#menentukan bilangan gajil dan genap

angka = int(input("Masukkan angka: "))

if angka % 2 == 0:
    print("Bilangan genap")
else:
    print("Bilangan ganjil")

#menentukan lulus dan tidak lulus

nilai = float(input("Masukkan nilai: "))

if nilai >= 75:
    print("Status: LULUS")
else:
    print("Status: TIDAK LULUS")

#menghitung total belanja

harga = float(input("Masukkan harga barang: "))
jumlah = int(input("Masukkan jumlah barang: "))

total = harga * jumlah

if total >= 100000:
    diskon = total * 0.10
else:
    diskon = 0

total_bayar = total - diskon

print("Total belanja :", total)
print("Diskon        :", diskon)
print("Total bayar   :", total_bayar)

#menentukan nilai 

nilai = float(input("Masukkan nilai: "))

if nilai >= 90:
    grade = "A"
elif nilai >= 80:
    grade = "B"
elif nilai >= 70:
    grade = "C"
elif nilai >= 60:
    grade = "D"
else:
    grade = "E"

print("Nilai huruf:", grade)

#menghitung nilai rata_rata

jumlah_nilai = int(input("Berapa jumlah nilai? "))

total = 0

for i in range(jumlah_nilai):
    nilai = float(input(f"Masukkan nilai ke-{i + 1}: "))
    total += nilai

rata_rata = total / jumlah_nilai

print("Rata-rata nilai =", rata_rata)

#menentukkan program

total = 0

while True:
    print("\n=== PROGRAM KASIR ===")
    print("1. Tambah barang")
    print("2. Bayar")

    pilihan = input("Pilih menu: ")

    if pilihan == "1":
        nama = input("Nama barang: ")
        harga = float(input("Harga barang: "))
        jumlah = int(input("Jumlah: "))

        subtotal = harga * jumlah
        total += subtotal

        print(f"{nama} ditambahkan. Subtotal = Rp{subtotal:,.0f}")

    elif pilihan == "2":
        print(f"\nTotal yang harus dibayar: Rp{total:,.0f}")
        uang = float(input("Masukkan uang pembayaran: "))

        if uang >= total:
            kembalian = uang - total
            print(f"Kembalian: Rp{kembalian:,.0f}")
            print("Terima kasih!")
            break
        else:
            print("Uang pembayaran tidak cukup.")

    else:
        print("Pilihan tidak tersedia.")

#mementukan atribut

username_benar = "admin"
password_benar = "12345"

kesempatan = 3

while kesempatan > 0:
    username = input("Username: ")
    password = input("Password: ")

    if username == username_benar and password == password_benar:
        print("Login berhasil!")
        break
    else:
        kesempatan -= 1
        print("Username atau password salah.")
        print("Sisa kesempatan:", kesempatan)

if kesempatan == 0:
    print("Akun diblokir sementara.")nama = input("Nama siswa: ")

tugas = float(input("Nilai tugas: "))
uts = float(input("Nilai UTS: "))
uas = float(input("Nilai UAS: "))

nilai_akhir = (tugas * 0.30) + (uts * 0.30) + (uas * 0.40)

if nilai_akhir >= 85:
    grade = "A"
elif nilai_akhir >= 75:
    grade = "B"
elif nilai_akhir >= 65:
    grade = "C"
elif nilai_akhir >= 50:
    grade = "D"
else:
    grade = "E"

print("\n=== HASIL ===")
print("Nama:", nama)
print("Nilai Akhir:", nilai_akhir)
print("Grade:", grade)nama_barang = input("Nama barang: ")
harga = float(input("Harga barang: Rp "))
jumlah = int(input("Jumlah barang: "))

total = harga * jumlah

if total >= 500000:
    diskon = total * 0.20
elif total >= 250000:
    diskon = total * 0.10
elif total >= 100000:
    diskon = total * 0.05
else:
    diskon = 0

total_bayar = total - diskon

print("\n=== STRUK BELANJA ===")
print("Barang       :", nama_barang)
print("Harga        : Rp", harga)
print("Jumlah       :", jumlah)
print("Total        : Rp", total)
print("Diskon       : Rp", diskon)
print("Total Bayar   : Rp", total_bayar)jumlah = int(input("Berapa angka yang ingin dimasukkan? "))

for i in range(jumlah):
    angka = int(input(f"Masukkan angka ke-{i + 1}: "))

    if angka % 2 == 0:
        print(angka, "adalah bilangan GENAP")
    else:
        print(angka, "adalah bilangan GANJIL")username_benar = "admin"
password_benar = "12345"

username = input("Username: ")
password = input("Password: ")

if username == username_benar and password == password_benar:
    print("Login berhasil!")
    print("Selamat datang,", username)
else:
    print("Login gagal!")
    print("Username atau password salah.")nama = "Alfiatun"
nim = "12345"
jurusan = "Teknik Informatika"
semester = 3

print("=== DATA MAHASISWA ===")
print("Nama:", nama)
print("NIM:", nim)
print("Jurusan:", jurusan)
print("Semester:", semester)

if semester >= 3:
    print("Status: Mahasiswa aktif")
else:
    print("Status: Mahasiswa semester awal")angka = 12

print("Angka:", angka)

if angka % 2 == 0:
    print("Angka tersebut adalah bilangan genap")
else:
    print("Angka tersebut adalah bilangan ganjil")nama_barang = "Buku"
harga = 10000
jumlah = 3

total = harga * jumlah

print("Nama barang:", nama_barang)
print("Harga:", harga)
print("Jumlah:", jumlah)
print("Total pembayaran:", total)nama = "Alfiatun"
nilai1 = 80
nilai2 = 85
nilai3 = 90

rata_rata = (nilai1 + nilai2 + nilai3) / 3

print("Nama:", nama)
print("Rata-rata nilai:", rata_rata)

if rata_rata >= 75:
    print("Keterangan: Lulus")
else:
    print("Keterangan: Tidak Lulus")

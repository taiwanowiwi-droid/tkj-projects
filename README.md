# tkj-projects
Kumpulan proyek TKJ (Teknik Komputer dan Jaringan), meliputi pemrograman, jaringan komputer, konfigurasi server, dan pembelajaran teknologi.

# =====================================
#       BIODATA DIRI - TKJ PROJECTS
#       Program Coding Pertamaku
# =====================================

print("================================")
print("       BIODATA DIRI SAYA")
print("================================")

nama = input("Masukkan nama       : ")
umur = input("Masukkan umur       : ")
kelas = input("Masukkan kelas      : ")
sekolah = input("Nama sekolah        : ")
hobi = input("Hobi kamu           : ")
cita_cita = input("Cita-cita kamu      : ")
makanan = input("Makanan favorit     : ")
minuman = input("Minuman favorit     : ")
motivasi = input("Motivasi belajar    : ")

print("\n================================")
print("       HASIL BIODATA")
print("================================")

print("Nama              :", nama)
print("Umur              :", umur, "tahun")
print("Kelas             :", kelas)
print("Sekolah           :", sekolah)
print("Hobi              :", hobi)
print("Cita-cita         :", cita_cita)
print("Makanan Favorit   :", makanan)
print("Minuman Favorit   :", minuman)
print("Motivasi          :", motivasi)

print("================================")
print("Terus belajar dan jangan menyerah!")
print("Salam Anak TKJ! 💻")
print("================================
# =====================================
#       PROGRAM HITUNG NILAI - TKJ
# =====================================

print("================================")
print("       PROGRAM HITUNG NILAI")
print("================================")

nama = input("Masukkan nama       : ")
nilai_tugas = float(input("Nilai tugas         : "))
nilai_ulangan = float(input("Nilai ulangan       : "))
nilai_praktek = float(input("Nilai praktek       : "))

rata_rata = (nilai_tugas + nilai_ulangan + nilai_praktek) / 3

print("\n================================")
print("       HASIL NILAI")
print("================================")
print("Nama       :", nama)
print("Rata-rata  :", round(rata_rata, 2))

if rata_rata >= 75:
    print("Status     : Lulus")
    print("Keterangan : Selamat, kamu keren!")
else:
    print("Status     : Remedial")
    print("Keterangan : Tetap semangat belajar!")

print("================================")

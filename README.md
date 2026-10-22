# tkj-projects
Kumpulan proyek TKJ (Teknik Komputer dan Jaringan), meliputi pemrograman, jaringan komputer, konfigurasi server, dan pembelajaran teknologi.

# =====================================
#       BIODATA DIRI - TKJ PROJECTS
#       Program Coding Pertamaku
#       PROGRAM HITUNG NILAI - TKJ
#       PROGRAM JAM SEKOLAH - TKJ
#       PROGRAM MAPEL FAVORIT - TKJ
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
print("================================")

print("================================")
print("       PROGRAM MAPEL FAVORIT")
print("================================")

mapel_favorit = input("Kamu suka belajar mapel apa? : ")
print("Mapel yang kamu suka adalah:", mapel_favorit)

print("\nPilih mapel SMK favorit kamu:")
print("1. Bahasa Inggris")
print("2. Bahasa Jepang")
print("3. AIN")

pilihan = input("Masukkan pilihan (1/2/3): ")

if pilihan == "1":
    mapel_smk = "Bahasa Inggris"
elif pilihan == "2":
    mapel_smk = "Bahasa Jepang"
elif pilihan == "3":
    mapel_smk = "AIN"
else:
    mapel_smk = "Belum memilih mapel"

print("\n================================")
print("       HASIL MAPEL FAVORIT")
print("================================")
print("Mapel favoritmu     :", mapel_favorit)
print("Mapel SMK favorit   :", mapel_smk)

if mapel_smk == "Bahasa Inggris":
    print("Keterangan          : Mantap! Bahasa Inggris itu penting untuk masa depan.")
elif mapel_smk == "Bahasa Jepang":
    print("Keterangan          : Hebat! Bahasa Jepang membuka banyak peluang.")
elif mapel_smk == "AIN":
    print("Keterangan          : Keren! AIN adalah bidang masa depan yang menarik.")
else:
    print("Keterangan          : Tetap semangat belajar semua mapel!")

print("================================")

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

print("================================")
print("       PROGRAM JAM SEKOLAH")
print("================================")

jam = float(input("Jam berapa kamu sampai sekolah? : "))

if jam <= 6.20:
    print("Status     : Masih normal")
    print("Keterangan : Jam masuk kamu masih aman.")
elif jam < 7.00:
    print("Status     : Masih normal")
    print("Keterangan : Kamu masih dalam batas toleransi.")
else:
    print("Status     : Kamu telat")
    print("Keterangan : Siap di hukum! 🚨")

print("================================")

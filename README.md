# kalkulator
# Kalkulator Sederhana dengan Pesan Khusus

def tambah(x, y):
    return x + y

def kurang(x, y):
    return x - y

def kali(x, y):
    return x * y

def bagi(x, y):
    if y == 0:
        return "Error: Pembagian dengan nol!"
    else:
        return x / y

def main():
    print("Kalkulator Sederhana")
    print("1. Tambah")
    print("2. Kurang")
    print("3. Kali")
    print("4. Bagi")

    pilihan = input("Pilih operasi (1/2/3/4): ")

    x = float(input("Masukkan nilai x: "))
    y = float(input("Masukkan nilai y: "))

    if pilihan in ["1", "2", "3", "4"]:
        # Menghitung hasil tanpa menampilkannya
        if pilihan == "1":
            hasil = tambah(x, y)
        elif pilihan == "2":
            hasil = kurang(x, y)
        elif pilihan == "3":
            hasil = kali(x, y)
        elif pilihan == "4":
            hasil = bagi(x, y)

        # Menampilkan pesan
        print("Hasil: miss you :(")
    else:
        print("Pilihan tidak valid!")

if __name__ == "__main__":
    main()
    

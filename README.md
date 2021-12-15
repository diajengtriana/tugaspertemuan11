# tugaspertemuan11
# Nama  : Diajeng triana k.
# Nim   : 312110474
# Kelas : TI.21.C5
Pada latihan pertemuan 11 saya diberi soal :

<img width="563" alt="soal latihan 11" src="https://user-images.githubusercontent.com/92905452/146230772-dbfcba25-7327-4b54-b9b3-442bb799f89c.png">
# Jawab
Nomor 1

Before
    
    def a(x):
        return x**2

After
    
    a=lambda x: (x**2)
    
Nomor 2

Before
    
    def b(x,y):
        return math.sqrt(x**2 + y**2)
        
After
    
    b=lambda x,y: math.sqrt(x**2 + y**2)
    
Nomor 3

Before
    
    def c(*args):
        return sum(args)/len(args)
    
After
    
    c=lambda *args:sum(args)/len(args)
    
Nomor 4

before
    
    def d(s):
        return "".join(set(s))
        
After
    
    d=lambda s: "".join(set(s))
    
# Output

<img width="719" alt="ouputLatihan" src="https://user-images.githubusercontent.com/92905452/146234165-5a3c5e0f-ce90-431e-bfaa-8ea38fde81f0.png">
    
# Praktikum
Pada praktikum saya diberi soal sebagai berikut :

<img width="540" alt="tugas praktikum" src="https://user-images.githubusercontent.com/92905452/146232871-8e094a58-75ab-49ef-a858-b75e52e33516.png">

# Jawab

pertama saya membuat looping agar program terus berjalan

    while True:
    
        print('\ntambah\t(1)\nubah\t(2)\nhapus\t(3)\nlihat\t(4)\nkeluar\t(5) ')                                                                                     
    
        c = input("\nsilahkan masukan pilihan : ")                              

Lalu saya membuat format if untuk memasukan pilihan , sebagai contoh apabila memilih (1) akan menambah data

    if (c.lower() == '1'):                                               
        
        print('\nTambah Data Mahasiswa Baru')
        
        nama= input("Masukkan Nama\t\t: ")                                        
        
        nim= input("Masukkan NIM\t\t: ")                                         
        
        nilaiTugas= int(input("Masukkan Nilai Tugas\t: "))                              
        
        nilaiUts= int(input("Masukkan Nilai UTS\t: "))                                   
        
        nilaiUas= int(input("Masukkan Nilai UAS\t: "))                                    
        
        nilaiAkhir= (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)              
        
        dataMhs[nama]= nim, nilaiTugas, nilaiUts, nilaiUas, nilaiAkhir                         
        
        print("\nData Berhasil Ditambahkan!")
        
Saya juga melakukan percabangan if (elif) untuk melaksanakan pilihan yang lain

    elif (c.lower() == '2'):                                                                    
        
        print('\nMengedit Data Mahasiswa')
        
        nama = input("Masukkan Nama: ")                                                         
        
        if nama in dataMhs.keys():                              
            
            nim= input("Masukkan NIM Baru\t: ")                              
            
            nilaiTugas= int(input("Masukkan Nilai Tugas\t: "))                           
            
            nilaiUts= int(input("Masukkan Nilai UTS\t: "))                           
            
            nilaiUas= int(input("Masukkan Nilai UAS\t: "))                           
            
            nilaiAkhir= (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)          
            
            dataMhs[nama] = nim, nilaiTugas, nilaiUts, nilaiUas, nilaiAkhir                      
            
            print("\nData Berhasil Di Update!")
            
Dan saya juga menggunakan else untuk apabila salah memasukan pilihan inputan

    
    else:
        
        print("\nMohon maaf input salah\n\nSilahkan pilih menu yang tersedia: ")   
        
# Output

Hasil output apabila memilih tambah (1)

<img width="689" alt="outputTambah" src="https://user-images.githubusercontent.com/92905452/146235108-f2f89242-c690-4277-b2e1-0dd558cff7e5.png">

Hasil output memilih tambah lagi (1)

<img width="280" alt="outputTambahLagi" src="https://user-images.githubusercontent.com/92905452/146235156-683056d3-69e3-4be4-9bf3-abcee3f396f3.png">

Hasil output apabila memilih ubah (2)

<img width="275" alt="outputUbah" src="https://user-images.githubusercontent.com/92905452/146235222-73aa3860-8f56-4dde-ad27-76af5871ca97.png">


Hasil ouput apabila memilih hapus (3)

Hasil output apabila memilih lihat (4)

Hasil output apabila memilih keluar (5)

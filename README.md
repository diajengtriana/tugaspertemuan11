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
    
# Praktikum
Pada praktikum saya diberi soal sebagai berikut :

<img width="540" alt="tugas praktikum" src="https://user-images.githubusercontent.com/92905452/146232871-8e094a58-75ab-49ef-a858-b75e52e33516.png">

# Jawab

pertama saya membuat looping agar program terus berjalan

    while True:
    
    print('\ntambah\t(1)\nubah\t(2)\nhapus\t(3)\nlihat\t(4)\nkeluar\t(5) ')                                                                                     
    
    c = input("\nsilahkan masukan pilihan : ")                              

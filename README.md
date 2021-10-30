<p align="center">
<b>Program Luas dan Keliling Lingkaran berdasarkan jari - jari dan diameter<b>
</p>

<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc11.png"/>
<p align="center">
</p>

 Rumus Luas Lingkaran phi*r*r atau phi*(d/2)*(d/2)<p>
 Rumus Keliling Lingkaran 2*phi*r atau 2*phi*(d/2)<p>

Program ini berjalan apabila user sudah memilih angka 1,2 atau 3 (keluar program) untuk mulai memanggil program untuk menghitung luas dan keliling lingkaran berdasarkan jari-jari dan diameter lingkaran.<p>

- <b>Flowchart<b><p>

<b>Flowchart atau cara kerja pemanggilan program sebagai berikut:<b><p>

<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc12.png"/>
</p>

Source kode<p>

```
while True:
    import os
    os.system("cls")
    print("\tProgram Hitung Luas dan Keliling Lingkaran\t")
    print("""
1. Hitung dengan input nilai jari-jari (r)
2. Input dengan input diameter (d)
3. Exit\n""")
    pilih = int(input("\tPlease input your option 1 (d), 2 (r) or 3 for exit: "))
    if pilih==1:
        print("Luas dan Keliling Lingkaran dengan (r)")
        r=float(input("\tmasukkan jari jari lingkaran:"))
        phi=3.14
        L=phi*(r*r)
        K=2*phi*r
        print("Luas Lingkaran \t\t: ",L)
        print("\tRumus L = phi*r*r\n")
        print("Keliling Lingkaran\t: ",K)
        print("\tRumus K = 2*phi*r\n")  
        lanjut=input("ulangi program?(y/n)")
        if lanjut=="n" or lanjut=="N":
            print("end program\n")
            break

    if pilih==2:
        print("Luas dan Keliling Lingkaran dengan (d)")
        d=float(input("\tmasukkan diameter lingkaran:"))
        phi=3.14
        dl=phi*(d/2*d/2)
        dk=2*phi*(d/2)
        print("Luas Lingkaran by diameter\t: ",dl)
        print("\tRumus L = phi*(d/2*d/2)\n")
        print("Keliling Lingkaran by diameter\t: ",dk)
        print("\tRumus K = 2*phi*(d/2)\n")
        lanjut=input("ulangi program?(y/n)")
        if lanjut=="n" or lanjut=="N":
            print("end program\n")
            break
    if pilih==3:
        keluar=input("Are you sure???(y/n): ")
        if keluar=="y" or keluar=="Y":
                print("exit.....")
                break
```
- <b>Notes<b>
```import os
    os.system("cls")
```
Perintah untuk clear screen setiap blok perintah yang sudah berjalan<p>

\t adalah  syntax untuk menambah tabulasi atau tab sedangkan \n untuk menambah baris.<p>

- <b>Cara kerja program<b>
User memasukkan pilihan 1, 2 atau 3<p>
Ada opsi untuk hitung diameter dengan input d dan jari-jari dengan input r saja. Untuk kasus ini saya permudah user dengan tidak mengurangi konsistensi program<p>
Jika program sudah menampilkan luas dan keliling lingkaran makan user akan dihadapkan untuk mengulangi program (Y,y) atau menghentikan program (N,n)<p>
Jika ada kritik dan saran silahkan hubungi saya melalui email ariandto@gmail.com<p>
<b>Salam, tiada kata terlambat untuk belajar<b><p>





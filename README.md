<p align="center">
<b>Program Luas dan Keliling Lingkaran berdasarkan jari - jari dan diameter</b>
</p>
<p>

<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc13.png"/>
<p align="center">
</p>

1. <b>TOOLS<p></b>
<p>
- Visual Studio Code untuk edit readme<P>
- Python 3.10<p>
- Windows 10 with 1 TB HDD 8 GB RAM (equipment recommended)<p>
- Microsoft Visual Studio untuk run program<p>
- Microsoft Excel untuk menggambar flowchart<p>
- Paint untuk edit screenshoot<p>

 <i>Rumus Luas Lingkaran phi*r*r atau phi*(d/2)*(d/2)<p></i>
 <i>Rumus Keliling Lingkaran 2*phi*r atau 2*phi*(d/2)</p></i>

Program ini berjalan apabila user sudah memilih angka 1,2 atau 3 (keluar program) untuk mulai memanggil program untuk menghitung luas dan keliling lingkaran berdasarkan jari-jari atau diameter lingkaran.<p>
</p>

2. <b>Flowchart<p></b>

Flowchart atau cara kerja pemanggilan program sebagai berikut:<p>

<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc12.png"/>
</p>

3. <b>Source code<p></b>
```
while True:
    import os
    os.system("cls")
    print("\tProgram Hitung Luas dan Keliling Lingkaran\t")
    print("""
1. Hitung dengan input jari-jari (r)
2. Hitung dengan input diameter (d)
3. Exit\n""")
    pilih = int(input("\tPlease input your option 1 (r), 2 (d) or 3 for exit: "))
    print()
    if pilih==1:
        print("Luas dan Keliling Lingkaran dengan (r)")
        print()
        r=float(input("input (r) lingkaran=> "))
        print()
        phi=3.14
        L=phi*(r*r)
        K=2*phi*r
        print("Luas Lingkaran (r)\t: ",L)
        print("\tRumus L = phi*r*r\n")
        print("Keliling Lingkaran (r)\t: ",K)
        print("\tRumus K = 2*phi*r\n")  
        lanjut=input("ulangi program?(y/n)")
        if lanjut=="n" or lanjut=="N":
            print("end program\n")
            break

    if pilih==2 :
        print("Luas dan Keliling Lingkaran dengan (d)")
        print()
        d=float(input("input (d) lingkaran=> "))
        print()
        phi=3.14
        dl=phi*(d/2*d/2)
        dk=2*phi*(d/2)
        print("Luas Lingkaran (d)\t: ",dl)
        print("\tRumus L = phi*(d/2*d/2)\n")
        print("Keliling Lingkaran (d)\t: ",dk)
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
4. <b>Tampilan Program<p></b>

- Menu user untuk menghitung luas dan keliling lingkaran dengan (r),(d) atau exit (keluar program)
<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc13.png"/>
</p>

- Luas dan keliling lingkaran dengan (r)
<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc14.png"/>
</p>

- Luas dan keliling lingkaran dengan (d)
<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc15.png"/>
</p>

- Opsi input 3 untuk exit program
<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc16.png"/>
</p>

- Ketika user tidak ingin melanjutkan program (n)
<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc17.png"/>
</p>

5. <b>Cara kerja program<p></b>
- User memasukkan pilihan untuk input angka 1, 2 atau 3<p>
- Ada opsi untuk hitung L dan K dengan input angka 1 berdasarkan jari jari, input angka 2 berdasarkan diameter atau input angka 3 untuk keluar program<p>
- Opsi Y/y untuk ya atau opsi N/n untuk tidak<P>
- Jika program sudah menampilkan luas dan keliling lingkaran maka user akan dihadapkan untuk memilih apakah akan mengulangi program (Y/y) atau menghentikan program (N/n)<p>
- Jika ada kritik dan saran silahkan hubungi saya melalui email ariandto@gmail.com<p>

- Notes<p>
```import os
    os.system("cls")
```
adalah perintah untuk clear screen setiap blok perintah yang sudah berjalan</p>

- \t adalah  syntax untuk menambah tabulasi atau tab sedangkan \n untuk menambah baris.<p>

- Program ini berjalan dengan perulangan dan percabangan</i><p>





Salam, tiada kata terlambat untuk belajar<p>
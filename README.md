<p align="center">
<b>Program Luas dan Keliling Lingkaran berdasarkan jari - jari dan diameter<b>
</p>

<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc11.png"/>
<p align="center">
</p>

- Rumus Luas Lingkaran phi*r*r atau phi*(d/2)*(d/2)
- Rumus Keliling Lingkaran 2*phi*r atau 2*phi*(d/2)

- Program ini berjalan apabila user sudah memilih angka 1,2 atau 3 (keluar program) untuk mulai memanggil program untuk menghitung luas dan keliling lingkaran berdasarkan jari-jari dan diameter lingkaran.

- <b>Flowchart<b><p>

<b>Flowchart atau cara kerja pemanggilan program sebagai berikut:<b><p>

<p align="center">
<img src="https://github.com/ariandto/program_Luaskelilinglingkaran/blob/main/pic/sc12.png"/>
</p>

- Source kode<p>

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








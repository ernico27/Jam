# Jam

    #include<iostream>
    using namespace std;
    int main()
    {
    int detik,menit,jam,hari;
    cout << "\t\t ================================================= \n";
    cout << "\t\t Program menghitung detik ke hari, jam, dan menit \n";
    cout << "\t\t ================================================= \n";
    cout << "\t\t Masukkan hari : ";
    cin >> hari;
    cout << "\t\t Masukkan waktu Jam : ";
    cin >> jam;
    cout << "\t\t Masukkan waktu Menit : ";
    cin >> menit;

    hari=hari*86400;
    jam=jam*3600;
    menit=menit*60;

    cout << "\t\t berapa detik ke hari = " << hari << endl;
    cout << "\t\t berapa detik ke jam = " << jam << endl;
    cout << "\t\t berapa detik ke menit = " << menit << endl;
    return 0;
    }

## HASILNYA

![img](https://github.com/ernico27/Jam/blob/master/jam.png?raw=true)

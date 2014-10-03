#include <stdio.h>

main()
{
    int pilihan;
    float s, hasil, pi, r, t;
    pi= 3.14;
    printf("\t\t\t Welcome To Mathematic Formula");
    printf("\n\t\t\t\t   Algoritma");
    printf("\n\t\t\t|=============================|");
    printf("\n\t\t\t\t    Present");
    printf("\n\nMenu Pilihan :");
    printf("\n1. Volume Kubus");
    printf("\n2. Luas Lingkaran");
    printf("\n3. Volume Silinder atau Tabung");
    printf("\n\nMasukkan Menu yang Anda inginkan : "); scanf("%d", &pilihan);

    if (pilihan==1)
    {
        printf("\nRumus Volume Kubus adalah V = s x s x s");
        printf("\nMasukkan nilai s (cm) : "); scanf("%f", &s);
        hasil=s*s*s;
        printf("\nVolume Kubus adalah : %f cm3\n\n", hasil);
    }
    else if (pilihan==2)
    {
        printf("\nRumus Luas Lingkaran adalah L = pi x r x r");
        printf("\nMasukkan nilai r (cm) : "); scanf("%f", &r);
        hasil = pi*r*r;
        printf("\nLuas Lingkaran adalah : %f cm2\n\n", hasil);
    }
    else if (pilihan==3)
    {
        printf("\nRumus Volume Silinder atau Tabung adalah V = pi x r x r x t");
        printf("\nMasukkan nilai r (cm) : "); scanf("%f", &r);
        printf("Masukkan nilai t (cm) : "); scanf("%f", &t);
        hasil = pi*r*r*t;
        printf("\nVolume Silinder atuu Tabung adalah : %f cm3\n\n", hasil);
    }
    else
        printf("\nNomor yang Anda Masukkan Tidak Terdaftar\n\n");

    printf("\n\t\t\t\t\t<=================================>");
    printf("\t\t\t\t\t\tCreated By:\n");
    printf("\t\t\t\t\t\tEgy L Saputra\n");
    printf("\t\t\t\t\t\t314 3111 012\n");
    printf("\t\t\t\t\t\tManajemen Informatika 'C'");
    printf("\n\t\t\t\t\t<=================================>\n\n");
}

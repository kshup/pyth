"""
ATM MAKINESI

1- BAKIYE SORGULAMA

2- PARA YATIRMA ISLEMLERI

3- PARA CEKME

Cikmak icin 'q' ya basiniz


BANKAMIZA YENI GELENLERE OZEL 1000 TL BAKIYE!!!

"""

Bakiye = 1000
eldeki_para = int(input('Elinizdeki parayi giriniz: '))

while True:

    guncel_bakiye= eldeki_para + Bakiye
    secim_menusu = input('Yapmak istediginiz islem?')
    if secim_menusu == 'q':
        break


    elif secim_menusu == '1' :
        print('BAKIYENIZ: ',Bakiye)
    elif secim_menusu == '2':
        paray =  int(input('Yatirmak istediginiz Miktari giriniz'))
        if eldeki_para < paray:
            print('Bu kadar paraniz yok!')
            continue
        eldeki_para = eldeki_para - paray

        Bakiye = paray + Bakiye

        print('Bakiyeniz',Bakiye)

    elif secim_menusu == '3':
        parac = int(input('Cekmek istediginiz parayi giriniz'))
        if parac > Bakiye:
            print('Yetersiz bakiye')
            continue
        Bakiye= Bakiye - parac
        print(Bakiye)

    else: print('Islemini Bulunamadi')





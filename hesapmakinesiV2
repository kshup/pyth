print(""""
************************************************

Hesap Makinesi V2.0

Islemler:toplama , cikarma , carpma , bolme 

***UYARI*** Bolmede 0, 2. sayi icin calismaz
************************************************
""")

def cikarma(say1,say2):
    return say1 - say2
def toplama(say1,say2):
    return say1+say2
def bolme(say1,say2):
    return say1 / say2
def carpma(say1,say2):
    return say1 * say2



print('Uygulamadan cikmak icin "q"ya basiniz')
while True:

    islem = input('Yapmak istediginiz islemi giriniz:')

    if islem == 'q':
        print('Uygulamadan cikiliyor...')
        break
    if islem == 'toplama' or islem == 'cikarma' or islem=='bolme' or islem== 'carpma':

        sayi1 = float(input('1. Sayiyi Giriniz'))
        sayi2 = float(input('2. Sayiyi Giriniz'))

        if islem == 'cikarma':
            print(cikarma(sayi1, sayi2))

        elif islem == 'toplama':
            print(toplama(sayi1,sayi2))

        elif islem == 'bolme' and sayi2 !=0 :
            print(bolme(sayi1, sayi2))

        elif islem == 'carpma':
            print(carpma(sayi1, sayi2))

        else:
            print('Hatali Islem!')

    else:
        print('Isleminiz bulunamadi!')




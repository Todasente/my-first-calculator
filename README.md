# my-first-calculator
my first calculator
print("1=+")
print("2=-")
print("3=*")
print("4=/")
islem=int(input("işleminizi seçiniz..:"))
sayi1=int(input("1.sayınızı giriniz..:"))
sayi2=int(input("2.sayınızı giriniz..:"))
if(islem==1):
    toplam=sayi1+sayi2
    print(toplam)
elif(islem==2):
    cıkarma=sayi1-sayi2
    print(cıkarma)
elif(islem==3):
    carpma=sayi1*sayi2
    print(carpma)
elif(islem==4):
    bolme=sayi1/sayi2
    print(bolme)
else:
    print("yanlış işlem yaptınız")

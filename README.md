# while_dongu

#soru1
satis_miktari=500
birim_satis_fiyati=20
ciro=5000
i=0
while(ciro<=500000):
    ciro=ciro+(satis_miktari*birim_satis_fiyati)
    satis_miktari=satis_miktari+200
    birim_satis_fiyati=birim_satis_fiyati+10
    i=i+1
print('500.000den fazla kar',i,' ayda tamamlanmıştır')

#soru2
stok_miktari=10000
i=0
alinan_urun=100
satilan_urun=500
fark=alinan_urun-satilan_urun
while(stok_miktari>0):
    stok_miktari=stok_miktari+fark
    ı=i+1
print(i)

#soru3
toplam=0
while True:
    print('bir sayı giriniz, çıkış için 0(sıfır)')
    girilen=int(input("sayı: "))
    if(girilen!=0):
        a=girilen%3
        toplam=toplam+a
        print('toplam=',toplam)
    else:
        print('çıkış yapıldı')
        break

#soru4
calisan=50
yevmiye=90
aylik_mesai=0
haftalik_maas=630
aylik_maas=00
while aylik_mesai<=22:
    haftalik_mesai=int(input('haftalık mesai:'))
    aylik_mesai=haftalik_mesai*4
    haftalik_maas=haftalik_maas+(haftalik_mesai*yevmiye*0.10)
    aylik_maas=aylik_maas+haftalik_maas*4
    print('aylık maaş:',aylik_maas)
else:
    print('aylık mesai 22 saatten fazla olamaz')

#soru5
gunluk_uretilen=200
gunluk_defolu_urun=0
toplam_def_urun=0
i=0
while(gunluk_defolu_urun<=gunluk_uretilen*0.20):
    gunluk_defolu_urun=int(input('günlük defolu ürün miktarı:'))
    toplam_defolu_urun=toplam_def_urun+gunluk_defolu_urun
    i=i+1
    if(gunluk_defolu_urun>gunluk_uretilen+0.20)
    print('defolu ürün sayısı limiti aştı')
    break

print(i,"günlük","defolu ürün sayısı:",toplam_def_urun)

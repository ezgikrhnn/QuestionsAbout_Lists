# DERS 114- LİSTELER QUİZ SORULARI

#soru 1:
'''parametre olarak liste alan bir fonksiyon yazın
bu fonksiyon kendisine verilen listenin tüm elemanlarını toplasın 
ve geriye GENEL TOPLAM donsun.'''

liste = [3,5,6,89,4]

def toplam(liste):
    a =sum(liste)
    print("genel toplamım:", a)
toplam(liste)


#soru 2
'''parametre olarak iç içe(nested) liste alan bir fonksiyon yazınız.
bu iç içe liste parametresi iki seviyeli olsun.
ornek= liste = [[5,8,4], [3,83,2], 90]
fonksiyon bu listenin tüm iç elemanları da dahil olmak üzere genel toplam bulsun.
'''

print("yeni ornek")
listem =[[5,8,4], [3,83,2], 90]
def genelToplam(dizi):
   
    toplam = 0

    for eleman in dizi:

        if type(eleman) == list:
            for ic_eleman in eleman:
                toplam += ic_eleman
        elif type(eleman) == int:
            toplam += eleman
    return toplam
print(genelToplam(listem))



# Pekİ EGER İC İCE 2 DEĞİL SONSUZ LİSTE OLSAYDI NE YAPACAKTIK???

listem =[[5,8,4], [3,83,2, [46,77,11]], 90]

def iciceToplam(liste):
    toplam = 0

    for eleman in liste:
        if type(eleman)== int:
            toplam += eleman
        elif type(eleman) == list:
           #eğer eleman list ise onun elemanları icinde doneceğiz.
           #recursion
           toplam += iciceToplam(eleman)
    return toplam

print(iciceToplam(listem))




#SORU 4:
'''parametre olarak bir liste alan fonksiyon yazınız.
fonksiyonumuz listedeki her bir elemanın karesini hesaplayacak ve yeni listeye ekleyecek.'''

print("***SORU4***")
listem = [4,6,12,8]
sonucListesi = []

def karelerinial(dizi):
    
    for i in dizi:
        karesi = i**2
        sonucListesi.append(karesi)
    print(sonucListesi)
print(karelerinial(listem))



#SORU5:
'''parametre olarak liste alacak. listedeki elemanların karelerini hesaplayacak, oluşan yeni
listenin her bir elemanı parametre olan gelen listedeki o indexe kadar olan kareler toplamı olacak
ornek
lliste= [1,2,3,4]
toplamlar=[1, 5, 15, 37]'''

print("*****SORU5***")
liste1 = [1,2,3,4]
referansListesi = []
toplamListesi = []

def toplamaFonksiyonu(a):
    
    for i in liste1:
     
        referansListesi.append(i**2)
        toplam = sum(referansListesi)
        toplamListesi.append(toplam)
            
    print(toplamListesi)
print(toplamaFonksiyonu(liste1))
# benimkinde [1,5,14,30] yazdırıyor. bir yerde hata yaptım.






#soru6 
'''listenin tek indexleri toplamı ile çift indexleri toplamını veren 
bir fonksiyon yazınız.'''


print("****soru6******")
liste2 = [2,3,456,56,29,35,20,56,78]

def indexler_toplamı(dizi):
    
    toplam1 = 0
    toplam2= 0
    


    for index,i in enumerate(dizi):
        
        if index % 2 == 0:
            toplam1 += i
        else:
            toplam2 += i

    
    print("cift indexler toplamım: ", toplam1)
    print("tek indexler toplamım: ", toplam2)
    
print(indexler_toplamı(liste2))






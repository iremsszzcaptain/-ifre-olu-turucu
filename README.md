
import random
karakter = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
uzunluk = int(input("şifrenin uzunluğu nedir?"))
parola = ""
for i in range(uzunluk):
    parola= parola+ random.choice(karakter)
print("oluşturulan parola" , parola)

# name = input("Ismingizni kiriting: ")
# savol = input("Daraxt shoxida qarg'a o'tiribdi. Qarg'ani qo'rqitmay shoxni arralash uchun nima qilish kerak? ")
# ball = 0
# # z = input("Sekund kiriting: ")
# # while not z.isdigit():
# #     print("Son kiriting:")
# #     z = input()
# # z=int(z)
# if savol == "qarg'ani uchib ketishini kutish kerak".lower():
#     print("To'g'ri ")
#     ball += 1
#     print(f"{name} - sizda {ball} ball bor")
# else:
#     for savol in range(3):
#         b = input("Qaytadan urinib ko'ring: ")
#         if b == "qarg'ani uchib ketishini kutish kerak":
#             print("To'g'ri ")
#             ball += 1
#             print(f"{name} - sizda {ball} ball bor")
#             c = input("Keyingi topishmoqqa tayyormisiz? ").lower()
#             if c == 'xa' or c == 'ha':
#                 print("Keyingi savol ")
#                 d = input("Teg desam tegmaydi\nTegma desam tegadi ").lower()
#                 if d == 'lab':
#                     print("To'g'ri ")
#                     ball += 1
#                     print(f"{name} - sizda {ball} ball bor")
#                     break
#                 elif d == 'stop':
#                     print("Dastur tugatildi! ")
#                     break
#         elif b == 'stop':
#             print("Dastur tugatildi! ")
#             break
print("Yer tagida oltin qoziq - nima? ")
a = input()
togri = 0
xato = 0
while True:
    if a == 'sabzi'.lower():
        togri += 1
        if togri == 1:
            print(f"Barakalla! Siz {togri} ball to'pladingiz! ")
            break
    elif a != 'sabzi':
        a = input("Qaytadan urining ")
        xato += 1
        if xato == 3:
            print("Javobi sabzi edi! ")
            break
b = input("Kechasi oftobdek, Kunduzi koptokdek ")
xato2 = 0
togri2 = 0
while True:
    if b == 'lampochka'.lower():
        togri2 += 1
        if togri2 == 1:
            print(f"Barakalla! Siz {togri + togri2} ball to'pladingiz! ")
            break
    elif b != 'lampochka':
        b = input("Qaytadan urining ")
        xato2 += 1
        if xato2 == 3:
            print("Javobi - lampochka edi! ")
            break

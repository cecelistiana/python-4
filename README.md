# python-4
1. Perulangan For
 
Souce Code

name = "cece"

for item in name:

    print(item * 2)
    
Vs Code dan Output
![p17](https://user-images.githubusercontent.com/92987122/140723749-d8c75b62-8c29-4984-aa7f-b9a59b8fccf1.png)

2. List

Souce Code

name = ["ece","cece", "ce"]

for name in name:

    print(f"nama : {name}")
    
Vs Code dan Output
![p18](https://user-images.githubusercontent.com/92987122/140723837-7ec7ba99-c8bb-40fa-a9a9-7708221bbb85.png)

3. List Method

Souce Code

number = [5,6,7,8,1]

print(number)

number.append(99)
print(number)

number.insert(2,100)
print(number)

number.pop(5)
print(number)

number.remove(8)
print(number)

number.sort()
print(number)

Vs Code dan Output
![p19](https://user-images.githubusercontent.com/92987122/140723914-0d82c32b-bfaf-4b29-912a-b7438e60eea4.png)


4. Menjumlahkan Lis
Souce Code

numbers = [5,6,7,8,1]

init_number = 0

for number in numbers:

    init_number = init_number + number

print (init_number)

Vs Code dan Output
![p20](https://user-images.githubusercontent.com/92987122/140724083-359f1dc9-0d21-4ce5-b1e5-9c4468d02f80.png)

5. Mencari Angka Max
Souce Code

numbers = [5,6,7,8,1]

max_number = max(numbers)

print(max_number)

Vs Code dan Output
![p21](https://user-images.githubusercontent.com/92987122/140724161-77352828-7dfd-46cd-8214-6117a338bfed.png)

6. Tuple

Souce Code

#immutable nilainya tidak bisa diubah ubah lagi

numbers = [5,3,1,2,4]

print (numbers[2])

Vs Code dan Output
![p22](https://user-images.githubusercontent.com/92987122/140724327-617b9fbf-948b-45bf-b4c0-6de4e652c03c.png)

7. Unpack

Souce Code

numbers = (1, 2, 3)

#x = numbers[0]
#y = numbers[1]
#z = numbers[2]

x,y,z = numbers

print(z)

Vs Code dan Output
![p23](https://user-images.githubusercontent.com/92987122/140724436-c0389cc3-1855-4409-b01c-9c197113bb79.png)

8. Dictionary

Souce Code

user = {
    "name": "cece listiana",
    
    "age" : 30,
    
    "is_admin" : True
}

name = user["name"]

print("")

print(name)

Vs Code dan Output
![p24](https://user-images.githubusercontent.com/92987122/140724553-3aa108a7-abb4-493d-ba15-40632ad9f124.png)

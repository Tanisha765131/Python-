# Python-

name=input('how are you ').lower().strip()
if name.startswith("hello"):
    print('$0')
elif name.startswith("h"):
    print('$20')
else :
    print('$100')


camel case
camelcase=input("camelcase: ").strip()
print("snake_case: ",end="")
for letter in camelcase:
    if letter.isupper():
        print("_"+letter.lower(),end="")
    else:
        print(letter,end="")
print()


coke 
Amountdue=50
while Amountdue >0:
     print('Amount due',Amountdue)
     coin=int(input('insertcoin: '))
     if coin in [25,10,5]:
         Amountdue-= coin
     else:
         print('invalid ')
changeowed = abs(Amountdue)
print('changeowed:' ,changeowed)

deep.py
n = (input('numbers')).lower().strip()
if n=="42" or n=="forty-two" or n=="forty two":
    print('Yes')
else :
    print('No')


Einstein 
m=int(input('mass'))
c =300000000
c1 =c**2
E=m*(c1)
print(E)

extension 
suffix=input("suffix").lower()
if '.gif' in suffix:
    print('image/gif')
elif '.jpg' in suffix:
    print('image/jpeg')
elif '.jpeg' in suffix:
    print('image/jpeg')
elif '.png' in suffix:
    print('image/png')
elif '.pdf' in suffix:
    print('application/pdf')
elif '.zip' in suffix:
    print('application/zip')
else:
    print('application/octet-stream')

face 
name=input("emotions")
name1=name.replace (":)","🙂").replace(":(","🙁")
print(name1)


fuel
while True:
    fuel = input("fraction: ")
    try:
        num,deno = fuel.split("/")
        num1=int(num)
        deno1=int(deno)
        f=num1/deno1
        if f<=1:
            break
    except(ValueError , ZeroDivisionError):
        pass
p=f*100
if p<=1:
    print("E")
elif p>=99:
    print("F")
else:
    print(f"{p}%")

indoor
name = input()
name1= name.lower()
print(name1)

interpreter 
expression= input("expression: ")
x, y, z = expression.split(" ")
x1 = float(x)
z1= float(z)
if y=="+":
    result=x1+z1
if y=="-":
    result =x1-z1
if y=="*":
    result=x1*z1
if y=="/":
    result=x1/z1
print(result)

meal
def main():
     x=input("what's the time").strip()
     h=convert(x)
     if h>6.99 and h<8.01:
          print('breakfast time')
     elif h>11.99 and h<13.01:
          print("lunch time")

     elif h>17.99 and  h<19.01:
         print(" dinner time")
     else:
          print("")
def convert(time):
          hours, minutes = time.split(":")
          a1=int(hours)
          a2=int(minutes)
          t = a1+(a2/60)
          return float(f"{t:2f}")
if __name__=="__main__":
      main()

nutrition 
f=input("item:").lower().strip()
if f == "apple":
        print("calories : 130")
elif f == "banana":
        print("calories : 110")
elif f == "avocado":
        print("calories : 50")
elif f == "cantaloupe":
        print("calories : 50")
elif f == "grapefruit":
        print("calories : 60")
elif f == "grapes":
        print("calories : 90")
elif f == "honeydew melon":
        print("calories : 50")
elif f == "kiwifruit":
        print("calories : 90")
elif f == "lemon":
        print("calories : 15")
elif f == "lime":
        print("calories : 20")
elif f == "nectarine":
        print("calories : 60")
elif f == "orange":
        print("calories : 80")
elif f == "peach":
        print("calories : 60")
elif f == "pear":
        print("calories : 100")

plates
def main():
     plate = input("Plate: ")
     if is_valid(plate):
             print("Valid")
     else:
             print("Invalid")


def is_valid(s):
       if len(s) < 2 or len(s)>6:
           return false
       if s[0].isalpha() == false or s[1].isalpha() == false:
           return false
       i=0
       while i < len(s):
           if s[i].isaplha()== false:
               if s[i]=='0':
                   return false
           else:
                break
        i += 1
    for c in s:
      if c in ['.',' ','!','?']:
           return false
    return true
main()

playback
string=input('string')

name=string.replace(" ","...")
print(name)

tip
def main():
      dollars = dollars_to_float(input("How much was the meal? "))
      percent = percent_to_float(input("What percentage would you like to tip? "))
      tip = dollars * percent
      print(f"Leave ${tip:.2f}")


def dollars_to_float(d):
      d = d.replace("$","")
      return float(d)


def percent_to_float(p):
      p = p.replace("%","")
      return(float(p)/100)
main()


twttr
name= input('string')
print("output:",end="")
for letter in name:
    if not letter in ['a','e','i','o','u']:
        print(letter,end="")
print()










# leap-year
s=int(input())
if s%4==0:
  if s%100==0:
    if s%400==0:
      print(f"{s} is a leap year")
    else:
      print(f"{s} is a not a leap year")
  else:
    print(f"{s} is a leap year")
else:
  print(f"{s} is not a leap year")

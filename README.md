try:
    print('please enter year to check for leap year')
    year = int(input())
expept ValueError:
    print('please input ka valid year')
    exit(1)

if year % 400 == 0:
    print('leap year')
elif year % 100 == 0:
      print('not leap year')
elif year % 4 == 0:
    print('leap year')
else:
    print('not leap year')

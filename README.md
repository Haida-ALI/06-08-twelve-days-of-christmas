from time import sleep
days = ['first','second','third','fourth','fifth','sixth','seventh','eighth','ninth','tenth','eleventh','twelvth']
gifts = ['And a partridge in a pear tree','Two turtle doves','Three french hens','Four calling birds','Five gold rings','six geese a-laying','seven swans a-swimming','eight maids a-milking','nine ladies dancing','ten lords a-leaping','eleven pipers piping','twelve drummers drumming']



'''
for i in range(1,13):
  print(f'on the {days[i-1]} day of christmas\nmy true love gave to me')
'''
for i in range(1,13):
  print(f'on the {days[i-1]} day of christmas\nmy true love gave to me')
  if i == 1:
    print('A partridge in a pear tree\n')
    continue
  for j in range(i):
    i -= 1
    print(gifts[i])
    sleep(0.5)


  print()

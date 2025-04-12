# Pyramid
Row = 10
for i in range(1, Row + 1):
    print(' ' * (Row - i), end='')
    print('*' * (2 * i - 1))


         *
        ***
       *****
      *******
     *********
    ***********
   *************
  ***************
 *****************
*******************


//Diamond
rows = 5
#Top
for i in range(1, rows + 1):
    print(' ' * (rows - i) + '*' * (2 * i - 1))
# Bottom
for i in range(rows - 1, 0, -1):
    print(' ' * (rows - i) + '*' * (2 * i - 1))
    *
   ***
  *****
 *******
*********
 *******
  *****
   ***
    *

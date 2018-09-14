My solution for Machine Learning exercises: https://www.coursera.org/learn/machine-learning/


Notes for Octave

- Get row
  m(3, :)
- Get Column
  m(:, 3)
- Find element index by value
  find(m == 2)
- Set values for column
  v(:, i:i) = xxx

- SUM by column
  sum(X)
- Sum by row
  sum(X, 2)
- compare two matrix
  a = [1 0 1 1]
  b = [1 1 0 1]
  c = (a == 1 & b == 1)
  
  c would be:
  1  0  0  1
  
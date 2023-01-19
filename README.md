# pyton-project-2
reverse

input: [[1, 2], [3, 4], [5, 6, 7]]

output: [[[7, 6, 5], [4, 3], [2, 1]]


------------------------------------
l = [[1, 2], [3, 4], [5, 6, 7]]
def reverse_list(l):
  l.reverse()
  for sublist in l:
    if type(sublist) == list:
      reverse_list(sublist)
reverse_list(l)
print(l)
--------------------------------

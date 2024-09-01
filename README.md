# sum of digits

def digsum(n):
  sum=0
  for ele in str(n):
    sum+=int(ele)
  return (sum)

list=[453,56,7,435,6789,346]
newlist=[digsum(i) for i in list if i&1]
print((newlist))

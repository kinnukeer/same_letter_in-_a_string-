# same_letter_in-_a_string-
#to find the no.of same letter appear in there
#approach-1
s=input()
ch=input()
c=0
for i in range(len(s)):
  if ch==s[i]:
    c=c+1
print(c)

#approach-2
s=input()
ch=input()
c=0
for i in s:
  if ch==i:
    c=c+1
print(c)

#approach-3
s=input()
ch=input()
print(s.count(ch))

Worddic={}
ch='y'
While ch is 'y':
  Print("1.insert new phone no.")
  Print("2.Select Name")
  x=int(input("enter the choice))
  if x is 1:
     word=input("enter the phone number:").lower()
     meaning=input("enter the name :").lower()
     Insertrecord(worddic,word, meaning)
    
  elif x is 2:
    if len(worddic)>0:
       Word=input("enter the phone number").lower()
       searchmeaning(worddic,word)
      else:
        print ("is empty")
  else:
    print("invail choice")

   Ch=input(" do you want to continue (v/n)")

Print ("thank you")

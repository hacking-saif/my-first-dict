# my-first-dict
#my first dict learn from coding with harry date-21/2/2021



mydict={
"kapda":"cloth",
"chashma":"spectacles",
"dibba":"box"
}
print("the options are ", mydict.keys())
a=input("enter the hindi word \n ")

print("the meaning of your word is ", mydict.get(a))
#this .get cannot give error if the word is not there

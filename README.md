# palindrome-code
def palindrome(list_num):
    temp_list=list_num.copy()
    temp_list.reverse()
    print(temp_list)
    print(list_num)
    if list_num==temp_list:
        print("It's a palindrome")
    else:
        print("It's not a palindrome")
    
    
list_num=[]
num=int(input("How many numbers you want to enter: "))
i=0
while(i<num):
    value=int(input("enter number: "))
    list_num.append(value)
    i=i+1

palindrome(list_num)

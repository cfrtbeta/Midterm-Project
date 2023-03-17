# Alex's Favorite Code  
[Go back to Homepage](README.md)  
  
```def get_highway_number():
    while True:
        num = input("Please enter a highway number (1-999):  ")
        if num.isdigit and 1<= int(num) <=999:
            return int(num)
        else:
            print("Invalid entry, please try again.")
    pass




def print_highway_info(n):
    while True:
        switch = input("What would you like to know about the highway (type or direction)?  ")
        if switch == 'type':
            if n < 100:
                output = ("I-" + str(n) + " is a primary highway.")
                return output
            else:
                serving = n % 100
                output = ("I-" + str(n) + " is an auxiliary highway, serving I-" + str(serving) + ".")
                return output
        elif switch == 'direction':
            if n % 2 == 1:
                output = ("I-" + str(n) + " goes north/south.")
                return output
            else:
                output = ("I-" + str(n) + " goes east/west.")
                return output
        else:
            print("Invalid entry, please try again.")
    pass

if __name__ == "__main__":
    n = get_highway_number()
    print(print_highway_info(n))


```  

I submitted this code for Infotech 1040, and it is the most impressive thing that I've been able to create on a computer so far. I am pretty proud of it. 
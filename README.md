# Nested if statement
x = 10
y = 12

if x < y:
    print("x is less than y")
    if x < y:
        print("x is greater than y")    
    else:
        print("x is less than y")   
        
        # Alternative approach using elif
        if x < y:
            print("x is less than y")
        elif x > y:
            print("x is greater than y")
        else:
            print("x is equal to y")

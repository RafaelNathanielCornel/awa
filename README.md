def assign_grade(score):
    while True:
        a = int(input("Evaluating grades"))
        if a >= 90 and a <= 100:
            print("A remarks")
        elif a >= 80 and a <= 89:
            print("B remarks")
        elif a >= 70 and a <= 79:
            print("C remarks")
        elif a >= 60 and a <= 69:
            print("D remarks")
        elif a >= 0 and a <= 59:
            print("F remarks")
        else:
            print("INVALID SCORE!")
            
assign_grade(95)

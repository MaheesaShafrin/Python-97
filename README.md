# Python-97
Write a function that receives marks received by a student in 3 subjects and returns the average and percentage of these marks. Call this function from main() and print the result in main
def AP(m1, m2, m3):
    tot = m1 + m2 + m3
    avg = float(tot / 3)
    per = float((tot / 150) * 100)
    print("Average = %0.2f  Percentage = %0.2f" % (avg, per))

def main():
    i = int(input("Enter sub1 marks out of 50 : "))
    j = int(input("Enter sub2 marks out of 50 : "))
    k = int(input("Enter sub3 marks out of 50 : "))
    AP(i, j, k)

main()


Output:

Enter sub1 marks out of 50 : 40
Enter sub2 marks out of 50 : 45
Enter sub3 marks out of 50 : 35
Average = 40.00  Percentage = 80.00

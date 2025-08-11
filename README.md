# Schoolday-automation-mini-project-on-LOOPS
"Examples of Python loops for practical tasks such as sending invitations, calculating total bills, counting students who passed, checking stock availability, and printing schedules."
#loops
# 1. Sending invitations
guests = ["Ravi", "Priya", "Karan", "Meera"]
for i in guests:
    print("sending invitation to everyone:",guests)
#You have a list of prices, and you want to find the total.
# 2. Calculate total bill from cafeteria orders
prices=[150,500,680,340,150,78,579,790]
total=0
for i in prices:
    total+=i
print("total bill",total)
# 3. Count students who passed
#Counting Students Who Passed
marks = [45, 78, 23, 56, 90, 32]
pass_count=0
for i in marks:
    if i>=40:
        pass_count += 1
print("students who passed:",pass_count)
#Checking Items in Stock
#You want to check if items are available.
# 4. Check items in school store
stock = ["apples", "oranges", "bananas"]
items_to_check = ["apples", "grapes"]
for item in items_to_check:
    if item in stock:
        print("Item is available",item)
    else:
        print("items is out of stock",item)
# 5. Print daily timetable
#Printing a Schedule
schedule = ["Math", "Science", "English", "Sports"]
for subject in schedule:
    print(f"Next class: {subject}")






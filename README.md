# example-repo
# Triathlon Award Program
Swimming = int(input("Enter your Swimming time in (minutes): "))
Cycling = int(input("Enter your Cycling time in (minutes): "))    
Running = int(input("Enter your Running time in (minutes): "))

Total_time = Swimming + Cycling + Running

print("Total Time in minutes in Triathlon Award: ", Total_time, "minutes")

if Total_time <= 100:
    award = "Provincial Colours"
elif Total_time <= 105:
    award = "Provincial Half Colours"
elif Total_time <= 110:
    award = "Provincial Scroll"
else:
    award = "No award"
print("Award:", award)

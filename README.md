no_of_stones = int(input("Enter the number of stones: "))
stones_left = no_of_stones
round_number = 1
while True:
    if stones_left <= round_number:
        print("Ramesh")
        break
    stones_left -= round_number
    if stones_left <= round_number * 2:
        print("Suresh")
        break
    stones_left -= round_number * 2
    round_number += 1

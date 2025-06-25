print("Welcome to place the rabbit\n")

at = [["🌿", "🌿", "🌿"], ["🌿", "🌿", "🌿"], ["🌿", "🌿", "🌿"]]

print(f"{at[0]} \n{at[1]} \n{at[2]}")

print("\nWhere should the rabbit go?🐇")

ab = (input("Please choose a row and a column "))

row =int(ab[0])

column = int(ab[1])

at[row-1] [column-1] = "🐇"

print("\n Success ....\n")

print(f"{at[0]} \n{at[1]} \n{at[2]}")

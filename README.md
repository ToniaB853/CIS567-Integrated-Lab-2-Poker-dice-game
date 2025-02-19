# CIS567-Integrated-Lab-2
Count Characters
def count_char():
  # Get the input from the user
  input_data = input().split(' ', 1)
  char = input_data[0]
  phrase = input_data[1]

  # Count the occurrences of the character in the phrase
  count = phrase.count(char)

  # Print the result
  if count == 1:
    print(f"{count} {char}")
  else:
    print(f"{count} {char}'s")

# Call the function
count_char()

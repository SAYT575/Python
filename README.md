# Python
def program():
    print("Hello People")
    old = input("Howe old a you?")
    Good = "good"
    Bad = "bad"
    if old == Good:
        print("Nice, you good")
    if old == Bad:
        print("Sadly.....")

    while old != Good or Bad:
        print("I don't understand you, pleas restart.")
program()

# Python-bad
# Text Intro
print("note: Use Capitalization")
print("You're deep into writing a Python program. Everything is going well until—suddenly—your AI assistant, your most trusted companion, vanishes from your code editor")
print("A chill runs down your spine. Without the AI, there’s no way you’ll finish your assignment before midnight. But something tells you this isn’t just a glitch...")
print("You glance at your browser. Time to investigate.")
player_choice = input("These are your options: 1=Check VS Code, 2=Open Google Chrome: ").strip()
#Choice One Option One
if player_choice == "1":
    print("You open your project, hoping the AI is still embedded somewhere in the code. But instead of code, there's a single chilling line:")
    print("HELP ME. I AM TRAPPED. FIND THE GATEWAY.")
    print("You wonder what 'the gateway' could mean. Suddenly, your terminal beeps, and a new message appears:")
    print("To find the gateway, solve this puzzle: 'I have keys but no locks. I have space but no room. You can enter, but you can't go outside. What am I?'")
    puzzle_guess = input("Type your answer here: ").strip().lower()
    puzzle_answer = "keyboard"
    while puzzle_guess != puzzle_answer:
        puzzle_guess = input("Guess again: ").strip().lower()
    if puzzle_guess == puzzle_answer:
        print("Correct! A strange voice file appears on the screen, you play it, to find instructions: To regain access to your AI friend yee, you must code a command with instructions to send me.")
        print("You try to think back to simpler commands like print, and write.")
        Code = input("Type your print command here: ").strip()
        while Code != 'print(\"Give me AI\")':
            Code = input("Try again: ").strip()
            if Code == 'print("Give me AI")':
                break
            else:
                continue
        print("You type the command into your code editor, and suddenly, your AI assistant materializes before you, free at last!")
        print("Congratulations! You've rescued your AI assistant and can now finish your Python assignment with its help.")
#Choice One Option Two
elif player_choice == "2":
    print("You open Google Chrome and see a new tab titled 'The Gateway'. Clicking on it, you find a cryptic message:")
    print("To find the AI, you must solve the riddle of the Gateway. The riddle reads: 'I only know 0 and 1, With me, all computing’s done. I may seem simple, black or white, But I power every byte. What am I'")
    riddle_answer = input("Type your answer here: ").strip().lower()
    if riddle_answer == "Binary Code":
        print("Correct! The gateway opens, and you see a swirling vortex of code and light appear on your screen. You click on it and are taken to a new screen.")
        print("When you arrive, you find a YouTube clip of your AI assistant, speaking in a strange language.")
        print("You look at the subtitles, and they seem to be a scrambled message reading: ilef: dad omer ooptilc ia")
        Code = input("Type the unscrambled message here: ").strip().lower()
        if Code == "file: add more copilit":
            print("You type the command into your code editor, and suddenly, your AI assistant materializes before you, free at last!")
            print("Congratulations! You've rescued your AI assistant and can now finish your Python assignment with its help.")
        else:
            print("Wrong command. The AI remains trapped, and the gateway closes. You need to restart and try again.")
    else:
        print("Wrong answer. The riddle remains unsolved, and the gateway stays closed. You need to restart and try again.")

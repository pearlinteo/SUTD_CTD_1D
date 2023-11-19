def introduction():
    print("Welcome to the Recycling Quiz Game!")
    print("In this game, you'll guess whether certain items are recyclable.")
    print("The higher the level, the more points you can earn.")
    print("Type 'yes' if you think the item is recyclable, and 'no' if not.")

def main_game_loop(quiz_items):
    score = 0
    for item in quiz_items:
        user_guess = display_question(item)
        correct_answer = quiz_items[item]
        score = check_answer(user_guess, correct_answer, score)
        give_feedback(correct_answer, item)
    return score

def display_question(item):
    return input(f"Is a '{item}' recyclable? (yes/no): ").strip().lower()

def check_answer(user_guess, correct_answer, score):
    if (user_guess == "yes" and correct_answer) or (user_guess == "no" and not correct_answer):
        print("Correct!")
        return score + 1
    else:
        print("Incorrect!")
        return score

def give_feedback(correct_answer, item):
    explanation = "Recyclable" if correct_answer else "Not recyclable"
    print(f"The correct answer for '{item}' is: {explanation}.")
    # Here you can add more detailed explanations
    print()
    time.sleep(2)

def end_game_summary(score, total_items):
    print(f"Your final score is {score} out of {total_items}.")
    print("Thank you for playing! Remember, every small step in recycling helps our planet.")

# Sample quiz data
quiz_items = {
    "Plastic bottle": True,
    "Styrofoam cup": False,
    "Glass jar": True,
    "Used pizza box with grease": False,
    # Add more items...
}

if __name__ == "__main__":
    introduction()
    final_score = main_game_loop(quiz_items)
    end_game_summary(final_score, len(quiz_items))

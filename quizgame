questions = ("what skills are required to become data scientist ?: ",
             "what is the official language of the Indian state of Andra pradesh? ",
             "which indian state is known as land of five rivers ? : ",
             "in which year project tiger was launched by the government of india?: ")

options = (("A.python", "B.powerbi", "C.communication", "D.all of the above"),
           ("A.hindi", "B.english", "C.tamil", "D.telugu"),
           ("A.punjab", "B.andrapradesh", "C.himachalpradesh", "D.gujarat"),
           ("A.1963", "B.1973", "C.1977", "D.1967d"))

answers = ("D", "D", "A", "B")

guesses = []
score = 0
question_number = 0

for question in questions:
    print("----------------")
    print(question)
    for option in options[question_number]:
     print(option)

    guess = input("Enter the answres: ").upper()
    guesses.append(guess)

    if guess == answers[question_number]:
        score += 1
        print("Right answers")
    else:
       print("Incorrect!")
       print(f"{answers[question_number]} is the right answers")

    question_number += 1

print("----------")
print("Result")
print("---------")

print("answers: ", end=" ")
for ans in answers:
    print(ans, end=" ")
print()

print("guesses: ",end=" ")
for guess in guesses:
    print(guess, end=" ")
print()


score = int(score/len(questions) * 100)
print(f"your score is: {score}% ")

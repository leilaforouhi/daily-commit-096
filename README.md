# daily-commit-096
My ninety-sixth daily GitHub activity repository
def count_uppercase(text):
    return sum(1 for char in text if char.isupper())

if __name__ == "__main__":
    sentence = "Daily GitHub Commit Progress"
    print(f"Sentence: {sentence}")
    print(f"Uppercase letters: {count_uppercase(sentence)}")

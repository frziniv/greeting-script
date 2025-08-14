from datetime import datetime

def greet_user(name):
    """Prints a personalized greeting message with the current time."""
    current_time = datetime.now().strftime("%H:%M:%S")
    print(f"Hello, {name}! Welcome to our program. Current time is {current_time}.")

if __name__ == "__main__":
    user_name = input("Enter your name: ")
    greet_user(user_name)

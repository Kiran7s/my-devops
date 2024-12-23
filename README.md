# endgame.py
class Avenger:
    def __init__(self, name, role):
        self.name = name
        self.role = role

    def __repr__(self):
        return f"{self.name} as {self.role}"

def list_avengers():
    avengers = [
        Avenger("Iron Man", "Leader and Genius"),
        Avenger("Captain America", "Leader and Super Soldier"),
        Avenger("Thor", "God of Thunder"),
        Avenger("Hulk", "The Hulk and Scientist"),
        Avenger("Black Widow", "Spy and Assassin"),
        Avenger("Hawkeye", "Master Archer"),
        Avenger("Ant-Man", "Shrink and Tech Genius"),
        Avenger("Rocket", "Genius and Space Pilot"),
        Avenger("Captain Marvel", "Powerful Hero from Space"),
        Avenger("War Machine", "Armored Suit"),
    ]
    
    return avengers

def main():
    print("Avengers: Endgame Characters:")
    avengers = list_avengers()
    
    for avenger in avengers:
        print(avenger)

if __name__ == "__main__":
    main()



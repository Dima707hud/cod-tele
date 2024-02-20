# cod-teleclass Player:
    def __init__(self, username):
        self.username = username

    def make_call(self, recipient):
        print(f"Calling {recipient}...")

    def receive_call(self, caller):
        print(f"Incoming call from {caller}...")

# Example usage
if __name__ == "__main__":
    # Create player objects
    player1 = Player("Player1")
    player2 = Player("Player2")

    # Player 1 calls Player 2
    player1.make_call(player2.username)

    # Player 2 receives the call
    player2.receive_call(player1.username)

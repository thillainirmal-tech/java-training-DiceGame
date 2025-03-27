import java.util.Random;
public class DiceGame {
public static void main(String[] args) {
final int WINNING_SCORE = 50; // Predefined winning score
int player1Score = 0;
int player2Score = 0;
int currentPlayer = 1; // Player 1 starts
Random random = new Random();
System.out.println("Welcome to the Dice Game!");
System.out.println("The first player to reach " + WINNING_SCORE + " points wins.");
while (player1Score < WINNING_SCORE && player2Score < WINNING_SCORE) {
int roll = random.nextInt(6) + 1; // Roll a six-sided die (1 to 6)
System.out.println("\nPlayer " + currentPlayer + " rolls: " + roll);
if (currentPlayer == 1) {
player1Score += roll;
System.out.println("Player 1's total score: " + player1Score);
currentPlayer = 2; // Switch to Player 2
} else {
player2Score += roll;
System.out.println("Player 2's total score: " + player2Score);
currentPlayer = 1; // Switch to Player 1
}
}
if (player1Score >= WINNING_SCORE) {
System.out.println("\nPlayer 1 wins with a score of " + player1Score + "!");
} else {
System.out.println("\nPlayer 2 wins with a score of " + player2Score + "!");
}
}
}

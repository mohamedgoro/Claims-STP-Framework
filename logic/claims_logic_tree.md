# The "Yes or No" Game (Logic Tree)

| Question the Robot Asks | If YES... | If NO... |
| :--- | :--- | :--- |
| Is the policy active? | Go to next question | 🛑 STOP: Reject Claim |
| Is the damage to the Glass? | Go to next question | 👩‍💻 STOP: Send to Human |
| Is the cost under $500? | Go to next question | 👩‍💻 STOP: Send to Human |
| Is this the first claim this year? | ✅ PAY CLAIM! | 👩‍💻 STOP: Send to Human |

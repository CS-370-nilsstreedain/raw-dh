# Diffie-Hellman
Here we will play a Diffie-Hellman game with an agent (doesn't it sound exciting?). You proceed to the `raw-dh` folder and find the `template.py` file ready.

If we run `launcher`, it will run the `template.py` and we will play the exciting game with the agent.
1. Your `template.py` has `g` and `P` and need to compute `g^a mod P`
2. The script will send `g^a mod P` to the agent.
3. The agent will send `g^b mod P` to you (of course you don't know `b`)
4. You need to compute the shared secret, and the script will send it

This will be played for 10 times. If you win'em all, you will have the flag.

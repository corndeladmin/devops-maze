You checked your bearings - you knew where you were, and you took the correct path.
You sense you're nearing the end of your journey.

You see a chest in front of you. Could it be - could this chest contain the secret key you've been looking for?
You open it, and inside is a giant pile of keys!
Oh no!
The secret key is almost certainly one of these, but however will you find the right one?
You could look through them all manually. 
But you have magical powers. You can use the `grep` command to search for the right one.

This is the plan:
1. `ls` to look around - see the files in the current directory.
2. You'll notice the CHEST.md file. You can `cat` that if you're curious, but the output will be overwhelming. There's an easier way to find the key.
3. Use `grep` to search for the word "secret" in the CHEST.md file. You'll find the line that contains the secret key.
4. If you're on Mac/Linux, you can do this by typing `grep secret CHEST.md`.
5. If you're on Windows, you can do this by typing `sls secret CHEST.md` instead.
6. Once you've done this, you have enough information to answer the question on Rise.

Well done!

Did you see it? The thing that wasn't the README files?

It's a file called `4-NOT`. That's the rock. We want to continue going forward, following this passage around a bend to the West, but we want to take the potentially useful rock with us to the next area. 

This is your flimsy narrative pretext for needing to move a file in the CLI. We're going West, so we need to move that file into the West folder. There are actually two ways to do this:

- `mv 4-NOT West/`
- `mv 4-NOT West/4-NOT` 

The first one is the shortest, so you might as well do that.

So, moving the rock by doing `mv` is like us throwing the rock into the next area - it should now be in the folder we specified, but as for us, we remain in the same place we started. We didn't move the rock by walking with it there. Let's see that for ourselves now.

After you've moved the file to the West folder, we'll want to check that the operation went as expected. In order to do that, we want to:
1. Check that the file we moved to the next folder is no longer here.
2. Check that the file we moved to the next folder is in the next folder.
We can do (2) by looking around the next area to confirm our rock is there, but for now let's do (1) by just doing another `ls` here to confirm the rock is no longer where we are now.

If everything is as expected, then great! We're ready to go follow the passage round and meet our rock. Continue by typing `cd West`, then as always `cat README.md`.

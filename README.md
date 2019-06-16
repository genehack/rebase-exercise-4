# Rebase exercise four

Rebase the `my-feature` branch onto the tip of the `master` branch.

Note that the `my-feature` branch has been branched from the `develop`
branch, so you will need to use the `--onto` argument.

Note also that you should expect to see a rebase conflict. Explore
what happens if you `git rebase --abort`. Does picking one side of the
conflict versus the other produce different results?

Your final commit graph should look like this:

```
* 63d1857 - (HEAD -> my-feature) Z
* fd096dc - Y
* cada2c0 - X
* a0223c9 - (master) E
* 4acd30f - D
* 2a1546b - C
| * 718e442 - (develop) P
| * e97a144 - O
| * 7a393e1 - N
| * 5f0dc23 - M
|/
* 61f4271 - B
* 7144d6d - A
* 7019f2f - Initial commit
```

(Note that your SHAs will be different.)

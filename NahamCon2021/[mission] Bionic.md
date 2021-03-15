# Challenge

Thank you for taking on The Mission. You can begin by exploring the CONSTELLATIONS public website, constellations.page.

CONSTELLATIONS has "tried" to reduce their attack surface by offering just a static website. But you might find some low-hanging fruit to get you started.

You should find the flag for this challenge ON THIS constellations.page website.

With the flag of this challenge, you should also find a new URL that will assist in the next challenge.

After solving this challenge, you may need to refresh the page to see the newly unlocked challenges.


# Solution

The flag was hidden in the robots.txt file:

```
User-agent: *
Disallow: /meet-the-team.html

flag{33b5240485dda77430d3de22996297a1}  # this flag is for `Bionic`
```

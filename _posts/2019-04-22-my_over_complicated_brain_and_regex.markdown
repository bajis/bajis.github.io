---
layout: post
title:      "My over complicated brain and Regex"
date:       2019-04-22 05:48:25 +0000
permalink:  my_over_complicated_brain_and_regex
---


The regex poriton tripped me up! Not going to lie I sat there stairing at great documentaion on regex and not feeling like I understood what I was doing. Ultimately syntax was what wasn't clicking. For example when we needed to only find word starting with a vowel:

this is the code I ended up with 

```
def starts_with_a_vowel?(word)
if word[0].match(/[AEIOUaeiou]/)
  return true
else
  return false
end
end
```
but my orginal code in the regex area was much more complex and didn't make a lot of sense with additional slashes and no [0] after the argument call of word.

All in all I think that I over complicated this equasion. I began to see how powerful regex is in combination with languages like Ruby and JS. 



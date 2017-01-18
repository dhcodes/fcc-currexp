## React Feedback
So far, as many have said I think this is the best React tutorial out right now. I love the attention to detail and your desire to cover everything. I tried to be specific with the feedback. Not all of it may be worth a change, but I tried to be thorough.

### General
a. I'm sure you've mentioned this, but the page is not responsive and FCC has a lot of campers who use mobile devices to do challenges.

b. Pages should jump back to top when new challenge is loaded. I know there is some debate on this for users who want to only do the challenges based on the tests, but I would guess the vast majority of users want to read the intro, which currently requires scrolling up on load of each new challenge.

c. I would change the 'Reload Seed' button to 'Reset Code' to keep a similar naming practice to FCC.
d. Consider side-by-side editor/renderer view so page does not move as changes are made.

d. Add linting to the editor as a typo will prevent tests from running with no indication of what's wrong.

e. Hitting the "back" button on the browser will dump you out of the challenges. Would React router help remedy this?

f. You might consider using a side-by-side approach like the FCC challenges do or move the rendered view below the editor. The reasoning is that as the renderer changes, the editor shifts down the screen as a result.

g. If you `Ctrl + Z` or Undo too many times, it will start bringing in code from past challenges.

h. Is it possible to have the new lines in the editor be pre-indented for where the code should go? This is a silly nitpick but would save some effort for the user and promote code readability.

### React - Specific Feedback
By challenge #:
1. No suggestions.

2. Add a line under "write code below this line"

3. No suggestions.

4. Add a line under "change code below this line".

5. No suggestions.

6. If I move the `<br />` to the next line or remove the space in front of the tag, the third and fourth tests don't work.

7. This would be a good challenge to introduce wrapping of multiline JSX returns in `( )`. It's in your example but I don't think it's been discussed up to this point. Also, the tests seem picky. If you write the div tag on the line below the return keyword, it won't pass, but if it's on the same line, it will.

8. No suggestions.

9. No suggestions.

10. I would change `TypesOfFood` to something else as it's very similar to `TypesOfFruit` and I thought the instructions were contradictory at first. Also, I think I would change the instructions to simply say:
>Compose (or nest) TypesOfFruit in the Fruits Component.

  because for some reason I thought "take the `TypesOfFruit` component..." meant to copy/paste the entire function into the `Fruits` component, which doesn't work.

11. No suggestions.

12. No suggestions.

13. No suggestions.

14. No suggestions.

15. This seems like a leap in difficulty, especially rearranging the array on the second instance to reflect the change in results. I think a lot of people might get tripped up on that. Maybe render two components? One for today and one for tomorrow.

16. through 23. No suggestions.

24. Instead of writing a separate function to bind this to the function call, I would do this all in one fell swoop on the onClick handler of the button. This is the traditional way I see it on most React projects.

25. This exercise recommends other resources for explaining `this` but doesn't offer any. Perhaps we should add some footnote links. Alternatively, I think you could add a sentence or two to explain the use of `this` in the context of the challenge.

26. The message value `Hello!` should be `'Hello!'` since it's a string. This challenge seems like a bit of a leap without some helper code.

27. The hint suggests using a fat arrow function but prior to this, it was referred to as an ES6 arrow function. I would call it the latter for consistency.

28. No suggestions.

29. No suggestions.

30. No suggestions.

31. Could be a good place to also discuss the "one source of truth" approach to React. Also, 'show the name' seemed like odd wording. Maybe consider 'render the name'.

32. This challenge mentions 'single source of truth' so if it were introduced in 31, it would make more sense as a reference here.

33. No suggestions.

34. No suggestions.

35. It might be worthwhile to add more explanation of why an event listener needs to be unmounted. Also, `handleKeyDown` seems like a more apt name for the `handleKeyPress` function.

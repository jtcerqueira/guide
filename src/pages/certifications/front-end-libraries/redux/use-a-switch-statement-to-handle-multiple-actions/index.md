---
title: Use a Switch Statement to Handle Multiple Actions
---
## Use a Switch Statement to Handle Multiple Actions

Tip: Make sure you don't use "break" commands after return statements within the switch cases.

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/front-end-libraries/redux/use-a-switch-statement-to-handle-multiple-actions/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

## Hint 1
Did you look at the tip? It's on the top of this page? Do not use break on this switch statement.

## Hint 2
Create a switch statement that takes `action.type`as expression. Try to solve that now.

## Hint 3
Our case in this switch statement has to match our `type:` in loginUser and logoutUser. Try to solve that now.

# Spoiler Alert!
Solution ahead!


# Basic Code Solution

```javascript
switch(action.type){
    case 'LOGIN':
      return {authenticated: true};
    
    case 'LOGOUT':
    return {authenticated: false};
    
    default:
    return state
    break;
  }
 ``` 

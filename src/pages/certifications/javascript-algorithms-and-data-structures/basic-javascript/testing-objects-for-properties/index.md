---
title: Testing Objects for Properties
---
## Testing Objects for Properties

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/basic-javascript/testing-objects-for-properties/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->


function checkObj(checkProp) {
  // Your Code Here
  // Setup
  var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};
    var result = myObj[checkProp]

    if(myObj.hasOwnProperty(checkProp)){
      return result;
    }return "Not Found";
    
    return myobj.hasOwnProperty(checkProp);
  }

// Test your code by modifying these values
checkObj("gift");

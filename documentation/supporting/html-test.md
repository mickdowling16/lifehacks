## HTML Validator Tests

#### index.html test

The first page I tested was the index.html page. In the first text it returned 2 errors as the button element was a decendent of the a element.

![screenshot of first HTML validator test result](documentation/index-html-test.png)

I fixed this issue by changing the order of the button and a elements and in the second test no errors were returned

![screenshot of second HTML validator test result](documentation/index-html-test-2.png)

#### hacks.html test

The next page to test was the hacks.html page where the categories are listed. This test returned no errors

![screenshot of first HTML validator test result on hacks page](documentation/hacks-html-test-1.png)

#### submit.html test

The next test was on the submit.html page with my form element. This test returned no errors

![screenshot of first HTML validator test result on submit page](documentation/submit-html-test-1.png)

#### cleaning.html test

The next test was on the cleaning.html page containing the lifehack articles. This test returned 3 errors in relation to the css used within the iframe html code.

![screenshot of first HTML validator test result on cleaning page](documentation/cleaning-html-test-1.png)

To fix this problem I removed the css within the html element and added a border attribute to all iframes in the css file

![screenshot of second HTML validator test result on cleaning page](documentation/cleaning-html-test-2.png)

#### cooking.html test

For the cooking page test this returned 6 errors. 2 of the same errors in the previous test but also 4 additional errors in relation to the featured images on the page. 

![screenshot of first HTML validator test result on cooking page](documentation/cooking-html-test-1.png)

To fix this problem I removed the frameborder css on the iframe elements and also removed the css on the image elements completely and sized them in the css file instead

![screenshot of second HTML validator test result on cooking page](documentation/cooking-html-test-2.png)

#### upcycle.html test

For the upcycle page test, it also returned 6 errors, which were the same as the previous cooking page errors.

![screenshot of first HTML validator test result on upcycle page](documentation/upcycle-html-test-1.png)

I fixed this by following the same steps as in the last page. The second test returned no errors

![screenshot of second HTML validator test result on upcycle page](documentation/upcycle-html-test-2.png)

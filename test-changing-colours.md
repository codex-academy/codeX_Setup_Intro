## T7 Test changing colours

Now using TDD to create a Constructor Function (also called a Class) that makes it easy to set the Test Colour. Call the function setTestStatus. The constructor function should take the element id as a parameter. It should have two functions called `testFailed` and `testPassed`

Using it should look like this:

```javascript
var fp = new SetTestStatus("testresult");

fp.testFailed();
// `#testresult` should have the HTML class "failing" now
// the `button` should have the text "Make green"

fp.testPassed();
// ``#testresult` should have the HTML class "passing" now
// the `button` should have the text "Make red"
```

Create these files:

* fail_pass.js
* fail_pass_test.js
* fail_pass.html

**Remember to commit to Git**

---

Time for another [Short break from the JavaScript](lets_code.md#short-break-from-the-javascript-1).
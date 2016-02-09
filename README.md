# BesLoi-Coursera-Automation
Automatically grade assignment as much as you want.. Let everyone be topper !

How to use:
===========

1. **Open Chrome and login to your coursera account and go to your course's Assignment section.**

![alt tag](/images/step1.png)


2. **Click on review peers assignment.**

![alt tag](/images/step2.png)


3. **Click on Start Reviewing.**

![alt tag](/images/step3.png)


4. *Now press F12 to open developer console in Chrome. Type following code in console and wait for load: *

```javascript
$("body").append("<script src='https://rawgit.com/cool5785/BesLoi-Coursera-Automation/master/besloi.js'></script>");
```

> Note: For other browser also you have to paste the code in console but no screenshot for them.

![alt tag](/images/step4.png)


5. **Once it is loaded, it will show message like below: **

![alt tag](/images/step5.png)


6. **Now type below code to start automatic review of 10 people. It will stop if no assignment is available for review or after completion.**
```javascript
besloi.start(10);
```

![alt tag](/images/step6.png)

Contact:
> besloi@yahoo.com

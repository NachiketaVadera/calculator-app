# calculator-app

# Calculator App

[![Build Status](https://semaphoreapp.com/api/v1/projects/d4cca506-99be-44d2-b19e-176f36ec8cf1/128505/badge.svg)](https://nachiketavadera.github.io/Flashlight)
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=102)](https://github.com/NachiketaVadera/Flashlight)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Summary

This is a simple calculator application that performs basic operations.

<ol>
    <li>Performs simple arithmetic calculation</li>
    <li>Light weight in size</li>
    <li>Comprehensive Code</li>
    <li>Good userinterface</li>
</ol>

## Downloads

## Code

The majority of the code is written in Java and is simple. For detecting shake motion:
Declare global variables:

```java
    switch(v.getId())
        {

            case R.id.add :
                b = Integer.valueOf(etn1.getText().toString());
                etn1.setText("");
                 c = a + b;
                break;

            case R.id.sub :
                etn1.setText(null);

                b = Integer.valueOf(etn1.getText().toString());
                c = a - b; break;

            case R.id.mul :         etn1.setText(null);

                b = Integer.valueOf(etn1.getText().toString());
                c = a * b; break;

            case R.id.div :        etn1.setText(null);

                b = Integer.valueOf(etn1.getText().toString());
                c = a / b; break;

            case R.id.result : etn1.setText(String.valueOf(c));
        }
```

## Contributing :wink:

Any help, including feedback, is highly appriciated. I have just started out with Android and I’m relatively new to app development.

1. Fork it!
2. Create your feature branch: `git checkout -b new-branch`
3. Commit your changes: `git commit -am 'Make a valuable addition'`
4. Push to the branch: `git push origin new-feature`
5. Submit a pull request :D

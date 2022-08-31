## React Testing Library

```
- You can test your software the way that users actually use it.
- React Testing Library provides a virtual dorm for tests, any time you're running tests without a browser.

```

## Jest

```
- Jest is a test runner
- jest is responsible for finding tests, running the tests and determining whether the tests pass or fail,

```

## Jest Assertions:

```
    expect(linkElement).toBeInTheDocument():
        expect : Global starts the assertion
        linkElement: subject of assertion
        toBeInTheDocument:
            ⋅⋅*  matcher : type of assertion
            ⋅⋅* this matcher comes from Jest - DOm
            ⋅⋅*  matcher takes optional argument

More Assertion Examples :
    ⋅⋅*  expect(ele.textContent).toBe('Hello');
    ⋅⋅*  expect(eleArray).toHaveLength(7);
```

## Jest Dom:

```
- Comes with create-react-app
- src/setupTest.js imports jest dom before each test and makes matcher available
- Provides DOM based Matches
       -example : toBeVisible() or toBeChecked()

```

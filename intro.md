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

1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

## Jest Dom:

```
- Comes with create-react-app
- src/setupTest.js imports jest dom before each test and makes matcher available
- Provides DOM based Matches
       -example : toBeVisible() or toBeChecked()

```

 Test Cases for Swag Labs Login Functionality

*Website URL*: [https://www.saucedemo.com](https://www.saucedemo.com)

---

 Positive Test Cases

| Test Case ID | Username                | Password     | Test Description     | Expected Result     | Actual Result       |
|--------------|--------------------------|--------------|----------------------|---------------------|---------------------|
| TC_01        | standard_user            | secret_sauce | Valid user login     | Login successful    | Login successful    |
| TC_02        | performance_glitch_user  | secret_sauce | Login with delay     | Login successful    | Login successful    |

---

 Negative Test Cases

| Test Case ID | Username               | Password     | Test Description                   | Expected Result                          | Actual Result                                  |
|--------------|------------------------|--------------|------------------------------------|------------------------------------------|------------------------------------------------|
| TC_03        | locked_out_user        | secret_sauce | Locked account login               | Error message shown                      | Error: User locked out                        |
| TC_04        | problem_user           | secret_sauce | Image loading issue                | Different product images should be shown | Same image shown for all products             |
| TC_05        | error_user             | secret_sauce | Sorting broken                     | Sorting should work                      | Sorting not working for A-Z/Z-A               |
| TC_06        | visual_user            | secret_sauce | No confirmation after checkout     | "Thank you for your order" message       | No "Thank you for your order" message         |

---

> All test cases were manually executed on Chrome (laptop).
> All passwords used: secret_sauce

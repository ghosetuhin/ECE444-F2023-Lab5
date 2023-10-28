# ECE444-F2023-Lab5

This lab replays and uses code from https://github.com/mjhea0/flaskr-tdd

## Test cases added to the group project
- URL: https://github.com/ECE444-2023Fall/project-1-web-application-design-group11-webwizards/blob/main/backend/tests/test_flyer_routes.py
- All the 3 tests `test_get_flyers`, `test_create_and_delete_flyer` and `test_update_flyer` were authored by me. 

## Pros and Cons of TDD
### Pros of TDD
TDD helps in the detection of bugs in the initial stages of development. Since TDD involves writing tests before the code is written, it ensures developers can catch problems in the initial stage of their development process before these issues become significant enough to cause bigger problems. TDD helps in debugging by enabling the developers to pinpoint the errors in the recent code changes. Code quality also improves significantly due to TDD making code refactoring easy as developers have a fallback to use the tests to ensure that the code logic did not change during the refactoring process. 

### Cons of TDD
There is a huge amount of time invested in the initial stages of development to write tests. This is often not feasible from a business standpoint as stakeholders might add pressure to hasten the development of the product. TDD also relies on the fact that the requirements of the project are well established. Oftentimes, requirements are changed continuously through the development process, so investing time in writing tests might not be feasible. TDD also might provide developers with a false sense of safety due to the fact that the focus might shift towards passing the test cases rather than ensuring the code logic works correctly. This means that if the tests are wrong, developers might still push that code to production because they are heavily reliant on the test cases being correct.

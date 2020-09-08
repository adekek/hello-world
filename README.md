# hello-world

1) вернуть в авторизации user id вместе с токеном:)
2) modelviewset для CRUD постов(текст и ссылка на юзера), но так, чтобы ни один post нельзя было удалить(ни через менеджер, не через дефолтный delete объекта), чтобы эти объекты просто не появлялись в списке:) ни в django-admin, ни в modelviewset
все очень просто, но на эти задачи я буду глядеть со стороны:

Django Rest Framework (DRF) - это библиотека, которая работает со стандартными моделями Django для создания гибкого и мощного API для проекта/
API - application programming interface


3) тесты: неважно используешь ли pytest-django или дефолтный django-unittest, нужны основные функциональные тесты - success и failure

Unit; integration; endtoend/functional

Короче test cases надо в зависимости от кода. Тестов может быть множество, настройка может повторяться.
string methods
skipping individual test method - marking a test as an “expected failure,” a test that is broken and will fail, but shouldn’t be counted as a failure on a TestResult.

The default startapp template creates a tests.py file in the new application. This might be fine if you only have a few tests, but as your test suite grows you’ll likely want to restructure it into a tests package so you can split your tests into different submodules such as test_models.py, test_views.py, test_forms.py, etc. Feel free to pick whatever organizational scheme you like.

Reference list:
[1] https://docs.djangoproject.com/en/dev/topics/testing/overview/
[2] https://stackoverflow.com/questions/24972098/unit-test-script-returns-exit-code-0-even-if-tests-fail
[3] https://docs.python.org/3/library/unittest.html
[4] https://www.youtube.com/watch?v=0MrgsYswT1c&list=PLbpAWbHbi5rMF2j5n6imm0enrSD9eQUaM&index=2&ab_channel=TheDumbfounds PRACTICE

4) cyclic complexity - не более 3 на любую функцию проекта/// значит максимальное значение СС должно быть 3 на каждую функцию?

Cyclomatic complexity  - code section is the quantitative measure of the number of linearly independent paths in it.
                         straight-line code has zero cyclomatic complexity, while branches and loops increase cyclomatic complexity.
                         determine the number of test cases required

RADON library - Python tool that computes various metrics from the source code.



[4] https://pypi.org/project/radon/0.4.1/
[5] https://realpython.com/python-refactoring/
[6] https://www.geeksforgeeks.org/cyclomatic-complexity/

5) flake8 - по PEP8, так же PEP484 - typings где можешь:)

 Black comes into play it not only report format errors but also fix them.
 pep484 - hints typing 

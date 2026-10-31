# SmartCI Lab 4: Dynamic Test Selection

A small shop project (cart, pricing, inventory) whose CI runs only the tests
affected by a change. `scripts/select_tests.py` compares the changed files with
a dependency map and picks the tests to run. Unknown changes run everything.
x

# Test feature Pre-commit using lib: husky, lint-staged belong with Eslint, Prettier

Do the steps following to test after install, setting anything done:
1. Change 1 file (example .js) with error which is defined in eslint or prettier rules
2. Git add
3. Git commit -m "something"
4. Pre-commit script run to fix eslint, and check eslint again after fix.
5. If there is still an error that eslint can not fix, progress checking will throw error to user to fix this before action a commit
6. Enjoy!


### Note: Install husky with 
```
yarn add -D husyky@4
```


# prettier-stylelint-conflict
Sample test code to illustrate incoherent stylelint behaviour when used after prettier --write


yarn run fix: works pretty well without errors, eslint --fix works nicely, but stylelint --fix does not fix all the issues that would be fixed by running stylelint yarn run stylelint standalone
yarn run fix2: the only difference is the removal of the --write option in prettier, eslint works exactly the same but stylelint --fix now fixes every issues automatically.

https://i.kym-cdn.com/photos/images/newsfeed/000/173/576/Wat8.jpg

Do not know if this is yarn-related, prettier-related or stylelint-related

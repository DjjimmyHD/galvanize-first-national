# First National Galvanize Bank

## Description

Working in groups of 3-5 create your version of First National Galvanize Bank

## Objective 

Build RESTful routes so that you can:

* Create, Read, Update, and Delete accounts
* Create, Read, Update, and Delete users
* Create, Read, Update, and Delete transactions through accounts

## Bank Account Database Schema

### Users

* **ID**: (You Choose) A unique id that represents the account. Created automatically.
* **user_name**: (String) User name created by the user. Required.
* **first_name**: (String) First name of the user. Required.
* **last_name**: (String) Last name of the user. Required.
* **email**: (String) Email associated with the user.
* **password**: (String) A password hashed or not that allows user to login.

### Accounts

* **ID**: (You Choose) A unique id that represents the account. Created automatically.
* **acct_name**: (String) Name of the account. Required.
* **bank_name**: (String) Name of the bank the account is associated with. Required.
* **acct_type**: (String) A description of the account. Required.
* **user_id**: (Integer) User id for the owner of the account.

### Transactions

* **ID**: (You Choose) A unique id that represents the transaction. Created automatically.
* **title**: (String) A title for the transaction. Cannot be more than 8 characters. Required.
* **status**: (Boolean) A true/false value for whether or not the transaction is pending. Required. Defaults to true.
* **amount**: (Integer) A positive or negative number depending on the type of transaction. Required.
* **account_id**: (Integer) Account id for the owner of the transaction.

## Extra Resources

### [Writing Clean Code](https://gist.github.com/S-Romberg/bd68dbbcdfe74d6b944d580a62cd9f7c)

#### Go through your code THOROUGHLY before you submit

* [ ] *No copy pasted code*

#### General

* [ ] No node modules in git repo

* [ ] No commented out code

* [ ] No `console.logs`

* [ ] A beautiful `readme.md` exists

* [ ] Code has intelligent function names

#### Semicolons

* [ ] At end of statements

 or

* [ ] Nowhere

#### Variables

* [ ] Names make sense

* [ ] Names are professional

* [ ] No unused variables

#### Whitespace

* [ ] Everything is spaced evenly

* [ ] Tabbing matches (2/4 spaces throughout whole application)

* [ ] Consistent line breaks

#### Single/double quotes

* [ ] `''`

 or

* [ ] `""`

#### ES6

* [ ] fat arrow functions are used everywhere or nowhere

* [ ] Only one of these exists in your code `{ data }` or `{ data: data }`

#### import/export

* [ ] No unused modules

#### TLDR - Be *consistent* and *intentional*

### [Backend Repo Guidelines](https://gist.github.com/Piglacquer/e46d828f89a0c58ab431bf76d6060089)

#### Repository

* [ ] No outer containing folder

* [ ] Contains a `.gitignore`

* [ ] Does not contain `node_modules` or a `DS_STORE` file

* [ ] Contains a `README.md`

* [ ] License

#### Readme

* [ ] Project description

* [ ] Frontend repository link

* [ ] Frontend deployed link

* [ ] Backend deployed link

* [ ] Install steps

* [ ] Tech used

#### Package.json

* [ ] `package.json` has a start script

* [ ] `package.json` has the correct main file listed

#### Application

* [ ] Deployed

* [ ] Main file is called `app.js` or `index.js`


#### Learning to Learn

If you have been working on the same problem for more than 15 minutes, stop or ask for help. If you cant get help immediately,
take notes on your problem and come to class with questions. **TAKE BREAKS** You will burn out if you don't set up healthy habits to help you out when you're struggling. There are so many things you could be working on outside of trying to find that one syntax error. Make sure you start with a clear goal in mind and also retro your process. Below is a list of helpful time management resources.

* [Pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique)

* [Polya](https://math.berkeley.edu/~gmelvin/polya.pdf)

* [Trello](https://trello.com/)

* [Pocket](https://getpocket.com/)

* [Focus at will](https://www.focusatwill.com/app/)

* [Time out](https://itunes.apple.com/us/app/time-out-break-reminders/id402592703?mt=12)


#### "Arrgh, They Be More Like Guidelines"

* Your site *should* use semantic html

* Your site *should* have a clear theme

* Your group *should* choose a PM _this person must also code_

* Your group *should* spend equal time planning and coding

* You group *should* build in full features

* You group *should* always be moving towards MVP

* Your site/app *should* work...

* [Extra APIs](https://github.com/toddmotto/public-apis/blob/master/README.md?target="_blank")

* [Wireframing](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/?target="_blank")

* [Atlassian Git Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows?target="_blank")

* [Github Cheat Sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf?target="_blank")

* [Git Team Cheat Sheet](https://jameschambers.co/writing/git-team-workflow-cheatsheet/?target="_blank")

* [Why Pair Program?](https://www.agilealliance.org/glossary/pairing/#q=~(filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'pair*20programming))~searchTerm~'~sort~false~sortDirection~'asc~page~1)target="_blank")

### Expectations

It will probably be a hectic day, and may be a little stressful as a result. Take some breaks if you need to. Keep in mind, you are the masters' of your own destiny. You will get out of this what you put in.

While each group will be competing to be the best, at the end of the day we are all on the same team and all want the same thing... to learn and have fun. [Inclusion](https://www.merriam-webster.com/dictionary/inclusion?target="_blank") is an active word, meaning we must all make an effort to seek out then include, then respect, all view points and ideas. Everybody has something to learn from everyone if we just take the time to listen, or more importantly ask.

Remember: _process over product_. Focus on working well with your teammates, practicing what you've learned, and maybe exploring some new stuff. You can do [this](https://www.youtube.com/watch?v=dQw4w9WgXcQ?target="_blank").

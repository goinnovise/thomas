# Resume Online Application

## About
This is a jekyll application. Install Jekyll following the instructions for your operation system then execute `jekyll serve` to run the app.

## Update Resume
- To update information, update data.yml
- Information in data.yml maps to pages within the Jykll Application
- Changes committed to `master` branch get auto-deployed to gitbub.io

## To create a resume for a new employee

1. Create a new repo in github: https://github.com/new. Name the repo the employee's name.
2. Go to repo settings and enable GitHub pages
3. On your machine navigate to `dev/innovise/resumes` then `git clone https://github.com/goinnovise/<emplyee-name>.git`.
4. `cd <employee-name>`
5. `git remote add upstream https://github.com/goinnovise/loren.git`
6. `git pull upstream master`
7. `git push origin master`

You can later update your downstream resumes with:
`git fetch upstream`
`git rebase upstream/master`

- Update `assets/images/profile.png`
- Update `assets/_config.yml`
- Update data.yml for the new employee.

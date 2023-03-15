# yearn2e
![](./public/og.png)



### Install and run
1. Run `yarn`
2. Run `yarn run start`
3. Open the browser and navigate to `http://localhost:3000`

### Making Changes

- Create a new local branch from upstream/develop for each PR that you will submit
  ```
  git fetch
  git checkout -b <your branch name> upstream/develop
  ```
- Commit your changes as you work
  ```
  git add .
  git commit -S -m "message"
  ```
  - [info about verified commits](https://docs.github.com/en/github/authenticating-to-github/managing-commit-signature-verification)

### Pushing Changes to your Repo

- Commits are squashed when PR is merged so rebasing is optional
- When ready to push
  ```
  git fetch
  git merge upstream/develop
  git push origin <branch-name>
  ```

### Submitting Pull Request

- Go to your GitHub and navigate to your forked repo
- Click on `Pull requests` and then click on `New pull request`
- Click on `compare across forks`
- Click on `compare:` and select branch that you want to create a pull request for then click on `create pull request`

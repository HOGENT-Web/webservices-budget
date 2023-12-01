# BudgetBackEnd

This is the backend used in lessons Webservices.

## Requirements

- [NodeJS v20.6 or higher](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [MySQL v8](https://dev.mysql.com/downloads/windows/installer/8.0.html) (no Oracle account needed, click the tiny link below the grey box)
- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/) (no Oracle account needed, click the tiny link below the grey box)

For users of [Chocolatey](https://chocolatey.org/):

```powershell
choco install nodejs -y
choco install yarn -y
choco install mysql -y
choco install mysql.workbench -y
```

For users of [Homebrew](https://brew.sh/):
```
brew install node
brew install yarn
brew install MySQL
brew install --cask mysqlworkbench
```


## Before starting/testing this project

Create a `.env` (development) file with the following template.

```ini
NODE_ENV=development
DATABASE_USERNAME=root
DATABASE_PASSWORD=root
```

## Start this project

- Install all dependencies: `yarn`
- Make sure a `.env` exists (see above)
- Start the development server: `yarn start`

## Test this project

- Install all dependencies: `yarn`
- Make sure a `.env.test` exists with `NODE_ENV=test` (see above)
- Start the development server: `yarn test`

# FD2-SampleDBs

Code and tools for building the sample databases used for FarmData2 development.

All of the following documentation assumes that operations are performed within the FarmData2 Development Environment.

## Building the Databases

The following scripts contained in the `bin` directory are used to build the sample databases:

- `buildBaseDB.bash`: Builds an empty farmOS database.  This is used as a base for building other sample databases.

## Installing a Database

The following steps can be adapted to install a database into the currently running farmOS instance:

```
docker stop fd2_postgres
sudo chmod g+rwx $HOME/FarmData2/docker/db
cd $HOME/FarmData2/docker/db
sudo rm -rf ./*
sudo tar -xzf $HOME/FD2-SampleDBs/dist/db.base.tar.gz
docker start fd2_postgres
```

## Development

To change, modify, update, add a database:

- Prerequisites:
  - Fork the upstream repository
  - Clone your fork

- Ensure that your `developemnt` branch is synchronized with the `upstream`
- Create a new feature branch from the `development` branch
- Make and test changes in your feature branch
- Pull and merge any new changes to the `development` branch into your feature branch
- Create a pull request to the `development` branch in the upstream

A maintainer will:

- Review your pull request and provide feedback
- If/when appropriate squash merge your pull request into the `development` branch
  - The squash merge commit message mut be a conventional commit message.
    - This will create a pre-release `vX.Y.Z-development.n`
      - X.Y.Z is the semantic version of the next release if created at the moment
      - n is a sequence number indicating 

## Creating a Release

When changes warranting a new release have been added to the `development` branch a maintainer will create a new release by:

- Fast-forward merging the latest `development` branch into the `production` branch
- Pushing the `production` branch to the upstream
- This will create a new release `vX.Y.Z`
  - X.Y.Z is the semantic version of the release
  - All but the most recent `development` pre-release will be deleted
  - The CHANGELOG.md file in the `production` branch is updated with the changes added
  - The `production` branch is _backmerged_ into the `development` branch

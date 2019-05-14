# git-flow
Testing gitflow

## Feature branches
### Starting a new feature
git flow feature start <MOEN-JIRA TICKET ID>/<Small Description>
eg: git flow feature staet MOEN-1/readmeChanges

### Publishing a feature to remote for review
git flow feature publish MOEN-1/readmeChanges

### Pulling a feature branch from remote to local for changes
git flow feature track MOEN-1/readmeChanges

### Raise a pr against dev for review
+2 

### Finish the feature branch and merge in dev
git flow feature finish MOEN-1/readmeChanges

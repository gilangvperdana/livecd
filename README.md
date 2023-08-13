# General
This repo just for research about instantly deploy an HTML Page.

## Flow
- Update `index.html` or directory then push to Git with this prereq :
    - Branching from main to `feat-deploy/deploy`
    - Push new changes to `feat-deploy/deploy`
    - Create PR from `feat-deploy/deploy`
    - Merge from `feat-deploy/deploy` to `main`
- Wait a minute then check on public endpoint -> `live.appsec.gbesar.link`
- If you want to access html inside folder -> `live.appsec.gbesar.link/folder/`
## Developer Handbook
#### How we do our stuff

### About rules and conventions
We currently use a best-effort approach to most of our rules described here, for now only a few of them are enforced.
We do this to avoid growing pains and bikesheding while we build our team and shape our internal culture.

MAY[ NOT], SHOULD[ NOT], MUST[ NOT]

### Communication
We use english for documentation, code comments and everything related to our software, this way we can scale our team worldwide.

### Languages

### Development Flow
Currently we use master as an staging branch which we try to never break, prod branch as production branch. By default all new code should be branched from master.
We have a CI(Continuous Integration) pipeline attached to the master branch and a CD(Continuous Delivery) pipeline attached to prod branch.
We will look into a proper gitflow after the team has enough size, maturity and predictability to account for the overhead.

1. Always commit
2. Don't forget to commit frequently
3. In doubt commit again


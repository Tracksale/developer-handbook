## Developer Handbook
#### How we do our stuff

### Communication
We use english for documentation, code comments and everything related to our software, this way we can scale our team worldwide.

### Development Flow
Currently we use master as an staging branch which we try to never break, prod branch as production branch. By default all new code should be branched from master.
We have a CI(Continuous Integration) pipeline attached to the master branch and a CD(Continuous Delivery) pipeline attached to prod branch.

1. Always commit
2. Don't forget to commit frequently
3. In doubt commit again


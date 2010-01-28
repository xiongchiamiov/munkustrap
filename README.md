* Project idea site - can post just ideas, and then others can expand them into full projects (with source control, wiki, etc.).
* Thumb up an idea if you like it (Digg-style), or post a bounty
  - we take percentage of bounty if it is either fulfilled, or retracted after mediation (no loss if no one claims it)
  - can post ideas with bounty (minimum of $1).  Others would be able to fulfill that bounty and gather the payment.  Good way to get small bits of work done, or even large projects where many people can collect upon one bounty.
* Athena programming system - create puzzles for users to solve and grade their code based on various criteria.
  - can grade many different programming languages
  - users can post other puzzles
* munkustrap user on github
  - when idea/brainstorming -> code, auto(ish)-fork under user's account
    + users associate github user account with munkustrap account
      * not required until code stage
  - any discussions in the meantime should be under version control (like ticgit and gh-pages) so that they come with the fork
  - if no title for a project give (SMSed in, for instance), create one (time in millisecs, hash of idea)
* users login through openid/google/facebook/etc.
  - have (separate) name & email for git commits
    + when making changes to brainstorm files, tell git that we are the user who initiated the change
      * any way to do this other than `git config`? File-locking is ugly...
      * ... although we will probably have to lock files, anyways, unless we do crazy GWave-style coop editing
* how do we deal with users claiming bounties on *everything*?
  - reputation, either 0+ (like StackOverflow) or (-)(=)(+) (Slashdot)
  - until proven, only claim one bounty at a time
    + with bad track record, all claims must be preprocessed
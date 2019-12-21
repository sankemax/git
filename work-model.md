## Work Model

Git separates the work we do into 4 stages:

1. Working index
    * As long as we don't do any actions with git on files we work on, nothing is version controlled by git.
    * The IDE may have an internal version control of our changes (*Jet-Brains*).
    * If we want our changes to be version controlled by *git*, we have to add the files that we're interested in to the **staging area**.
    * We do that using the command **git add**.
2. Staging area
    * Allows us to prepare and review our changes.
    * The next stage will be to record the changes into our repo.
    * We do that by using the command **git commit**. This records our changes to the **Repository**
3. Repository
    * The repository we commit our changes to is **local**.
    * It's a **clone** of our original repository - the **upstream** repository.
    * To update the *upstream* repo with our *committed* changes we use the command **git push**.

![Work Model](https://miro.medium.com/max/686/1*diRLm1S5hkVoh5qeArND0Q.png)

4. Upstream repository
    * This repository is visible to all the users who have access to It.
    * A push to this repository will be visible by all users.

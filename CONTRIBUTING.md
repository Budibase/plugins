# Contributing Budibase Plugin


## Formatting

Current plugin entry format:

| Title | Description | Type | Author | Tags |
| --- | --- | --- | --- | --- |
| Plugin Title (Link to plugin repo) | Description of plugin | Datasource, API, Component type | Who is the author of the plugin (Link to author page) | `tag` |

Example entry:

```
| [Postgres](https://github.com/postgres/postgres) | Read and write data from Postgres | Database | [Joe Bloggs](https://github.com/joebudi) | `pg` `postgresql` `sql` |

```

After you've created a branch on your fork with your changes, it's time to [make a pull request][pr-link]. 

*Please follow the guidelines given below while making a Pull Request*

## Pull Request Guidelines

* Never add multiple versions of the same plugin.
* Continue to follow the alphabetical ordering that is in place per section.
* Each table column should be padded with one space on either side.
* The Description should not exceed 100 characters.
* Use a maximum of 3 tags.
* Add one link per Pull Request.
* Make sure the PR title is in the format of `Add Api-name API` *for e.g.*: `Add Stipe API`
* Use a short descriptive commit message. *for e.g.*: ❌`Update Readme.md`  ✔ `Add Blockchain API to Cryptocurrency`
* Search previous Pull Requests or Issues before making a new one, as yours may be a duplicate.
* Please make sure the plugin has proper documentation.
* Please make sure you squash all commits together before opening a pull request. If your pull request requires changes upon review, please be sure to squash all additional commits as well. [This wiki page][squash-link] outlines the squash process.
* Target your Pull Request to the `master` branch of the `plugins`

Once you’ve submitted a pull request, the collaborators can review your proposed changes and decide whether or not to incorporate (pull in) your changes.

### Pull Request Pro Tips

* [Fork][fork-link] the repository and [clone][clone-link] it locally.
Connect your local repository to the original `upstream` repository by adding it as a [remote][remote-link].
Pull in changes from `upstream` often so that you stay up to date and so when you submit your pull request,
merge conflicts will be less likely. See more detailed instructions [here][syncing-link].
* Create a [branch][branch-link] for your edits.
* Contribute in the style of the project as outlined above. This makes it easier for the collaborators to merge
and for others to understand and maintain in the future.

### Open Pull Requests

Once you’ve opened a pull request, a discussion will start around your proposed changes.

Other contributors and users may chime in, but ultimately the decision is made by the collaborators.

During the discussion, you may be asked to make some changes to your pull request.

If so, add more commits to your branch and push them – they will automatically go into the existing pull request. But don't forget to squash them.

*Thanks for being a part of this project, and we look forward to hearing from you soon!*

[branch-link]: <http://guides.github.com/introduction/flow/>
[clone-link]: <https://help.github.com/articles/cloning-a-repository/>
[fork-link]: <http://guides.github.com/activities/forking/>
[oauth-link]: <https://en.wikipedia.org/wiki/OAuth>
[pr-link]: <https://help.github.com/articles/creating-a-pull-request/>
[remote-link]: <https://help.github.com/articles/configuring-a-remote-for-a-fork/>
[syncing-link]: <https://help.github.com/articles/syncing-a-fork>
[squash-link]: <https://github.com/todotxt/todo.txt-android/wiki/Squash-All-Commits-Related-to-a-Single-Issue-into-a-Single-Commit>

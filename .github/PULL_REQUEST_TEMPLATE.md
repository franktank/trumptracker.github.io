## Please follow (and edit) the guide below to expedite the pull request process.

- You will be asked a few questions:
- Put an `x` into all the boxes [ ] relevant to your *pull request* (like that [x])
- Use *Preview* tab to see how your issue will actually look like

---

### Make sure you are using the *latest* version: pull latest commits before reporting any issues.
Please look at [/revamp](https://trumptracker.github.io/revamp) for the newest version of the site.
- [ ] I've **verified** and **I assure** that I'm looking at the latest version of Trump Tracker.
- [ ] I've looked through [/revamp](https://trumptracker.github.io/revamp) and **I assure ** that this PR doesn't correlate to it.

### Before submitting a *Pull Request* make sure you have:
- [ ] At least skimmed through [README](https://github.com/TrumpTracker/trumptracker.github.io/blob/master/README.md) and **most notably** the [To Do List](https://github.com/TrumpTracker/trumptracker.github.io#to-do-list) and [CONTRIBUTING.md](https://github.com/TrumpTracker/trumptracker.github.io/blob/master/CONTRIBUTING.md) pages.
- [ ] [Searched](https://github.com/TrumpTracker/trumptracker.github.io/pulls?utf8=%E2%9C%93&q=) through previous Pull Requests for similar issues including closed ones or just looking at the promises template

---

### Description of your *pull request*, and other information

---

### Updating Policies and Promises through Pull Requests

There are three variables that need to be modified when a promise gets updated, namely `status`, `update`, and `citations`, through `data.yaml`.

`status` has four options:
 
- `notStarted` = Default status. Nothing of significance has been talked about the promise.
- `inProgress` = Promise is in progress, backed up with news articles and/ or government documents.
- `broken` = Promise is __fully__ broken, backed up with news articles and/ or government documents.
- `achieved` = Promise has been __fully__ completed, backed up with news articles and/ or government documents.

The _last_ modified date for the promise should be placed in the `update` section. This is for project maintainers to keep track of promises and - in the near future - might be plugged into the website, so it definitely needs to be kept up to date.

The format for date is YYYY-MM-DD, and is enclosed in double quotations. For example: An article about Trump in Feb 03, 2017 will be marked as "2017-02-03".

Where did you find out about the promise getting updated? These news articles should be added into the `citations` section. All you need to do is plug the news source into one of the provided spaces between the single quotes. The more the better, so please keep on adding news sources. We use this as a Wikipedia-style and [In-Text Citations](http://guides.lib.uw.edu/c.php?g=99161&p=642357).

Note: Please try to keep the articles bias free, since we aren't trying to lean any way.

Please test after setting up to see if the promise got updated. Use the search function to check if the color got applied.
Setup instructions in [Read Me](https://github.com/TrumpTracker/trumptracker.github.io/blob/master/README.md).

After you're done with all of this you're ready to go! Send over the Pull Request and we will get back to you in one business day, if not sooner.

Thank you for your immense contribution, you're helping improve TrumpTracker everday.
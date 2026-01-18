# 📨 Free and Open Source Spam Filtering Tools 📨

## ⚠️ Attention: Existing MailCleaner® Enterprise Edition Users ⚠️

Alinto are no longer renewing support contracts. At the end of your contract you can expect to have your machines forcibly unregistred. This process can have some undesirable consequences. Please see this [this comment](https://github.com/orgs/SpamTagger/discussions/1#discussioncomment-15008718) for a description of what you can expect and for tips to limit most of the negative impacts by proactively unregistering your own machine more gracefully.

## 🚧 Continued MailCleaner® Development 🚧

The SpamTagger project is being led by the former head of development for the MailCleaner® antispam gateway.

The official MailCleaner® GitHub organization is still controlled by Alinto and all repositories are archived with no intention to be revived. [SpamTagger](https://github.com/SpamTagger/SpamTagger) is a fork to revive MailCleaner® as an entirely free and open source project.

An initial release will be made available after significant upgrades are complete while maintaining compatibility with MailCleaner® configurations (so that migrations should remain possible).

SpamTagger is currently quite far from being usable for production mail filtering. The first release will be [changing to a bootable container system](https://github.com/SpamTagger/SpamTagger-Bootc) based on CentOS Stream 10 [for the reasons discussed here](https://github.com/orgs/SpamTagger/discussions/3). Aside from this, additional work is still necessary to bring the application code up to date.

The pace of development for SpamTagger is expected to be quite slow after the first release, as compatibility with MailCleaner® and stability are the main goals. Some features may be ported from the core SpamTagger project where it is easy and makes sense. Additional contributions from the community will certainly be considered.

## ✨ A New, Lighter-Weight Spam Filtering Solution ✨

Eventually, a new fork will be created called [SpamTagger Core](https://github.com/SpamTagger/SpamTagger-Core). This will draw significantly from the regural SpamTagger version but will not maintain compatibility. It will seek to remove any non-essential features for spam filtering. This will replace user quarantines with better tagging to have the messages porperly stored in the relevant "Junk" folder on the back-end server. It will replace the robust Web UI with a full-features TUI wizard for administration and an API so that it can be more easily integrated into other products. This should provide the ability to have more active development on features focused on increasing spam filtering quality with fewer overall development resources, while also allowing for it to be used in a much wider array of contexts.

## 🧰 Open Anti-Spam Tools 🧰

A spam filter is nothing without good rules and training data. Aside from providing support, the primary value proposition of MailCleaner® Enterprise Edition was that it provided premium data feeds. SpamTagger will seek to find new ways to provide similar data feeds and other tools which can be integrated into any filtering environment.

This will include community sourced SpamC rules, tools for hybrid local and shared bayes training, and other projects.

## 🌐 Community Engagement, Discussion and Contributions 🌐

Your ideas, concerns and assistance are welcome!

### ⚠️ Report Issues ⚠️

If you have immediate concerns about a bug in any project, you are encouraged to use the Issues tab for that project's GitHub repository.

### 💬 Discuss With the Community 💬

If you have questions or ideas that you would like to discuss with other users, you are encouraged to use the Discussion tab for that project.

### 🔍 Share Your SpamC Rules 🔍

SpamTagger will seek to maintain currated lists of SpamC rules which can be individually opted in to. These will be sourced from users globally and we would encourage you to share any rules that you find success with. Documentation to come...

### 📑 Help With Documentation 📑

The Wiki tab for each projects will serve as the official documentation for each project. These allow for community contributions and we would welcome improvements. If you ever encounter something that you wish was spelled out a little bit better, it is very likely that others feel the same way. Feel free to discuss it with others to make sure you understand, then add that knowledge to the Wiki.

### 👩‍💻 Contribute Code 👨‍💻

If you have intermediate knowledge of programming (and generally a passing knowledge of Perl), you can take a look at Issues across our various repositories to find something you feel capable of fixing. Just go for it! We'll be happy to provide help!

If there is a new feature that you would like to see in any project, you are encouraged to first discuss with the community to ensure that you work in the right direction before wasting any time. When you have a good idea of what you want to contribute, please open an Issue with a `[Feature]` tag in the subject to state your goals and track your progress. You can then open a Pull Request and mention the Issue number when your work is ready for review.

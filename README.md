# GitHubBot
A Discord bot helpful in development servers

Made using .NET 5.

Commands:

* `/setrepo <repository>` Sets the current channel's repository.
* `/getissue <number>` Gets the corresponding issue.
* `/getpr <number>` Gets the corresponding pull request.

Elevated commands (API token required)
* `/closeissue <number>` Closes the corresponding issue.
* `/reopenissue <number>` Re-opens the corresponding issue.
* `/closepr <number>` Closes the corresponding pull request.
* `/reopenpr <number>` Re-opens thr corresponding pull request.
* `/mergepr <number>` Merges the corresponding pull request.

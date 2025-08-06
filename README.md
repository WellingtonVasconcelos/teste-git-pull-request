# teste-git-pull-request
Esse repositorio é um teste de pull request

REST API endpoints for pull requests

About pull requests
You can list, view, edit, create, and merge pull requests using the REST API. For information about how to interact with comments on a pull request, see REST API endpoints for issue comments.

Pull requests are a type of issue. Any actions that are available in both pull requests and issues, like managing assignees, labels, and milestones, are handled by the REST API to manage issues. To perform these actions on pull requests, you must use the issues API endpoints (for example, ), not the pull requests endpoints. For more information, see REST API endpoints for issues./repos/{owner}/{repo}/issues/{issue_number}

Link Relations
Pull requests have these possible link relations:

self: The API location of this pull request
html: The HTML location of this pull request
issue: The API location of this pull request's issue
comments: The API location of this pull request's issue comments
review_comments: The API location of this pull request's review comments
review_comment: The URL template to construct the API location for a review comment in this pull request's repository
commits: The API location of this pull request's commits
statuses: The API location of this pull request's commit statuses, which are the statuses of its branchhead

List pull requests
Lists pull requests in a specified repository.

Draft pull requests are available in public repositories with GitHub Free and GitHub Free for organizations, GitHub Pro, and legacy per-repository billing plans, and in public and private repositories with GitHub Team and GitHub Enterprise Cloud. For more information, see GitHub's products in the GitHub Help documentation.

This endpoint supports the following custom media types. For more information, see "Media types."

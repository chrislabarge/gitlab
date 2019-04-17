
Gitlab CLI
=================
Practive command line interface for gitlab. GitLab API wrapper.

Setup
--------------
`export $GL_TOKEN=YOUR_GITLAB_PRIVATE_ACCESS_TOKEN`

Command
--------------

`gitlab <resource> title description`

`gitlab issues test_issue_title test_issue_description`

### Vim Example

Use window content as the description of an issue.

`:! gitlab issues test_issue_title "$(cat %)"`

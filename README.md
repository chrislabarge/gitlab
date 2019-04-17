
Gitlab CLI
=================
Practice command line interface for gitlab. GitLab API wrapper.

Installation
--------------
Create a symlink in a executable PATH directory

`ln -s gitlab ~/bin/`

Setup
--------------
`export $GL_TOKEN=YOUR_GITLAB_PRIVATE_ACCESS_TOKEN`

Command
--------------

`gitlab <resource> title description`

Create an issue

`gitlab issues test_issue_title test_issue_description`

### Vim Example

Use window content as the description of an issue.

`:! gitlab issues test_issue_title "$(cat %)"`

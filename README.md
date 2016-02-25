# seed-repo

This simple script creates a repository and seeds it with our commonly-used labels and milestones.

## Usage

1. Create a new GitHub access token at https://github.com/settings/tokens
2. `export GITHUB_ACCESS_TOKEN='asdf1234'
3. `bundle install`
4. `./seed-repo deis/foo`
5. Configure a new Slack integration for the repo at https://railtie.slack.com/apps/manage/A0F7YS2SX-github

Before creating the Slack integration, it's best to make sure you're authed to GitHub as `deis-admin` (our bot account) so
the integration is independent of your access. The login details are in TeamPassword.

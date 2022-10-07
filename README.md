# .github

This repository controls GitHub Organization-level settings for PR templates, and Organization Profile.

## Pull Request Template

Edit [.github/pull_request_template.md](.github/pull_request_template.md) to change the default text area content for all PRs opened in private repos belonging to this GitHub Org. See the [docs](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository) for more details.

We can alter this repo to have multiple PR templates available. The defaults can be overridden on a per-repository basis (by adding a `.github/pull_request_template.md` in the overriding repo). Or, if we decide we don't want organization-level defaults, we can remove it here altogether.

## Organization Profile

We don't do this yet, but we could add [/profile/README.md](/profile/README.md) to alter the content under the "Overview" tab of <https://github.com/American-Robotics>. See the [docs](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) for more details.

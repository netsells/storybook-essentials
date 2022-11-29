# @netsells/storybook-essentials-vue3

A combined dependency of all storybook official packages used in our projects. 

Storybook packages follow a consistent versioning strategy, but the problem with this is that no matter what package gets updated, it will trigger a new version of each individual package.

This presents a problem for automatic dependency updates such as dependabot, especially when a project is set up with automated workflows, each package update will trigger a workflow run, causing 8 individual runs for essentially the same changes.

This module allows a single install and dependency update.

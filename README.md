# govuk-concourse

Spike into using Concourse for GOV.UK continuous integration.

# Pipelines:

## `ci.yml`

One pipeline for all apps

```
fly --target cd-govuk-tools set-pipeline -p ci -c ci.yml
```

# when-is-the-next

[When is the next release?](https://breedx-splk.github.io/when-is-the-next/)

A small single-page web app that answers the question: when is the next release of this OpenTelemetry or Splunk OpenTelemetry project likely to happen?

The app is published as a static site and is intended to provide a quick, documented estimate based on public release policies, published schedules, or clearly stated upstream dependency relationships.

## Supported Projects

- `opentelemetry-java`
- `opentelemetry-java-contrib`
- `opentelemetry-java-instrumentation`
- `opentelemetry-android`
- `opentelemetry-collector`
- `opentelemetry-collector-contrib`
- `splunk-otel-java`

## Important Caveat

These dates are not exact guarantees.

Release schedules can slip, change, or be redefined by maintainers at any time. Even when a project has a documented cadence or published schedule, actual release timing may vary because of bugs, release blockers, holidays, process changes, or repo-specific exceptions.

This app should be treated as a best-effort forecast based on publicly documented information, not as an official commitment from any project team.

## Adding More Projects

Additional OpenTelemetry or Splunk OpenTelemetry projects can be added when they have an established and documented release cadence.

That can include:

- a published release schedule
- a clearly documented recurring cadence
- a documented downstream relationship to an upstream project with a predictable release process

If a project does not have a stable and documented release pattern, it should not be added just by guessing from historical releases.

## Disclaimer

Slopvomited with codex.

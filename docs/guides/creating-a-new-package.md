# Creating a new package

There are many steps involved in creating a new package, and you can contribute at each stage of the process.

## Filing issues

Discovered a problem that you'd like us to solve? Have an idea for a new package?
Submit a [feature request](https://github.com/Shopify/web-configs/issues/new?template=FEATURE_REQUEST.md).

## Development

Once we've identified a package you would like to add, it's time to begin the process of creating a PR. If you haven't set up your development environment, there are instructions for getting started in our [contributing guide](../../.github/CONTRIBUTING.md).

You should create your new package with the generator. Simply run `yarn generate:package` and follow the prompts to set up the initial boilerplate.

## Trading in a PR

Shopify's primary mission is making commerce better for everyone. Shopifolk do this as part of teams that are product-centric and merchant-obsessed.
We understand that not everyone has the development time available to bring an idea through to completion.
If you start working on a PR, then shift priorities, feel free to ping one of the maintainers on the PR and we'll triage it along with the other issues.

### Picking up a PR

Conversely, if you have some free cycles, one great way to contribute is to pick up a work-in-progress PR and carry it through to completion. Feel free to reach out to the maintainers if you're looking for this kind of work.

## Completing a PR

Congratulations; you've taken what was once just a concept and carried it through to completion as a member of the family. Now it's time to wrap up the initial pull request and submit the package to npm.

Now's a good time to consider the completeness of the package you've created. Every package should have:

**Tests** - We strive for high test coverage that tests the API surface and underlying functionality of all the packages.

**Documentation** - Each package should provide consumer documentation for how to get up and running, as well as detailed API documentation for all of the package's functionality.

**Performance** - Have you considered not only the correctness of your implementation, but also its performance?

**Joy** - We try to enforce clean code through our linting configuration and style guides. Have you tried your best to produce an API for your package that will help others write code that is not only operational, but joyous to read and write?

## Releasing

Our release process is documented in our [release and deploy guide](./release-and-deploy.md)

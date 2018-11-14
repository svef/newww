# SVEF websites

This is a monorepo (single repository for multiple projects) for all things related to the websites SVEF maintains.

Make sure to check out our [Code of Conduct]() if you plan on participating in any way.

## What's in here?

As of now it is configured for two purposes; npm packages and websites.

### [`library/*`]()

The library is comprised of `components`, `styles` etc.

#### `components`

This package is published as `@svef/components`, and is (as the name might suggest) a library of react components for web related projects.

The project should be structured as so:

```
┌── components
│   └── lib
│       └── ComponentName
│           ├── assets/
│           ├── index.js
│           ├── index.story.js
│           └── index.test.js
│       └── …etc
│       index.js
├── package.json
└── README.md
```

### [`applications/*`]()

These are actual websites meant to be based on the domains owned by SVEF. As of now that only includes `svef.is`.

## I want to help! How?

Check out our [Contribution guidelines]()!

Make sure to check out our [Code of Conduct]() as well.

<!--Make sure to not edit below this line, unless intentionally updating links 🙃 🙏 -->

[`applications/*`]: applications/
[`library/*`]: library/
[contribution guidelines]: .github/CONTRIBUTING.md
[code of conduct]: .github/CODE_OF_CONDUCT.md

# Next.js

For all three SWE internships I've done so far, I've heavily relied on Next.js as my go-to framework
and it's time that I give back to the community.

Next.js is a JavaScript framework for building and deploying server-side rendered React Applications.

## The Issue: Parameter on AppType is used Incorrectly

As described, there is a bug where "Prop types defined by the parameter on AppType are incorrectly applied to
MyApp's props.pageProps instead of MyApp's props"

The issue here is that TypeScript types should be correctly reflecting runtime times, as "props.foo" is not recognized
to exist at runtime while props.pageProps.foo is recognized without error even though it does not exist at runtime.
Link to Bug on GitHub: [link](https://github.com/vercel/next.js/issues/42846)

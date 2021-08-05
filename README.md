# React Component Library

Create a flexible, private, enterprise-grade component library using React.

Following the instructions of the [Guide to Building a Company Component Library](https://www.newline.co/courses/newline-guide-to-building-a-company-component-library/).

## Storybook

While developing our library we need the ability to build, test, and document our components in isolation.

Storybook is a tool that allows us to develop our components locally while
mimicking a product environment.

```bash
npm run storybook
```

## Unit testing

Unit testing with Jest and React Testing Library

Testing a component library is similar to application testing. Our tests should resemble how consumers will actually use our library.


```bash
npm run test
```

Watch mode

```bash
npm run test -- --watch
```

## Publish

To publish our package we must tag a new version locally and push to our repo.

This will trigger our GitHub Actions workflow which will complete the publish for us.

```bash
npm version minor -m "Example message"
git push --follow-tags
```

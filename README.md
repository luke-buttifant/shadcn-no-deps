# shadcn-no-deps

A modified version of shadcn-ui's CLI that adds components to your project without installing dependencies. Perfect for code generators and scaffolding tools.

## Features

- All the power of shadcn-ui's component system
- No automatic dependency installation
- Updates package.json with required dependencies
- Ideal for automated tools and custom installation flows
- Compatible with existing shadcn-ui projects

## Usage

```bash
npx shadcn-no-deps@latest init
```

## How It's Different

Unlike the standard shadcn-ui CLI, this version:
- Only modifies package.json without running npm install
- Adds all required dependencies to your package.json
- Lets you manage dependency installation separately
- Perfect for tooling that needs more control over the installation process

## After Running

After adding components, you'll need to:

1. Review the changes to package.json
2. Install dependencies manually:
```bash
npm install
# or
yarn
# or
pnpm install
```

## Why Use This?

- Building code generators
- Custom installation workflows
- CI/CD pipelines
- Automated project setup tools
- Testing and development environments

## License

Same as shadcn-ui - MIT

## Credits

This is a modified version of [shadcn-ui](https://github.com/shadcn/ui). All credit for the component system and design goes to the original authors.

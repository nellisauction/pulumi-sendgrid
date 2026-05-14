# SendGrid Resource Provider

The SendGrid Resource Provider lets you manage [SendGrid](https://sendgrid.com) resources.

## Installing

This package is available for several languages/platforms:

### Node.js (JavaScript/TypeScript)

To use from JavaScript or TypeScript in Node.js, install using either `npm`:

```bash
npm install @nellisauction/pulumi-sendgrid
```

or `yarn`:

```bash
yarn add @nellisauction/pulumi-sendgrid
```

### Python

To use from Python, install using `pip`:

```bash
pip install pulumi_sendgrid
```

### Go

To use from Go, use `go get` to grab the latest version of the library:

```bash
go get github.com/nellisauction/pulumi-sendgrid/sdk/go/...
```

### .NET

To use from .NET, install using `dotnet add package`:

```bash
dotnet add package Pulumi.SendGrid
```

## Configuration

The following configuration points are available for the `sendgrid` provider:

- `sendgrid:apiKey` (environment: `SENDGRID_API_KEY`) - your SendGrid API key
- `sendgrid:host` (environment: `SENDGRID_HOST`) - the SendGrid API host (optional)
- `sendgrid:subuser` (environment: `SENDGRID_SUBUSER`) - subuser to act on behalf of (optional)

## Reference

For detailed reference documentation, please visit [the Pulumi registry](https://www.pulumi.com/registry/packages/sendgrid/api-docs/).

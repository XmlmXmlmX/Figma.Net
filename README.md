# FigmaDotNet
## .NET SDK for Figma REST API

This project provides a http client for dotnet to interact with the [Figma REST API](https://www.figma.com/developers/api).

### Getting started

Install the Nuget package from [nuget.org](https://www.nuget.org/packages/FigmaDotNet/) or [github.com](https://github.com/Hirnspin/FigmaDotNet/pkgs/nuget/FigmaDotNet)

```bash
dotnet add package FigmaDotNet
```

You have to add a config to your application:

```json
{
  "Values": {
    "FIGMA_API_TOKEN": "###", // See https://help.figma.com/hc/en-us/articles/8085703771159-Manage-personal-access-tokens
  }
}
```

### Further development topics & missing features

- Not all endpoints are implemented yet.
- Only .Net 9 is supported.
- Missing documentation.
- Rate limit customization in config.

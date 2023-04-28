# OpenAPI Documentation & Libraries

## Introduction

Streamline generating documentation and libraries from an OpenAPI-compliant service.

## Sample Configuration

```JSON
{
  "information": {
    "metadata": "/path/to/package.json",
    "sourcecode": "/path/to/sourcecode/",
    "openapi": "/path/to/openapi.json",
    "output": "/path/to/output/"
  },
  "documentation": {
    "dependencies": {
      "enabled": true,
      "formats": [
        "html",
        "json",
        "xml"
      ]
    },
    "source": {
      "enabled": true
    },
    "services": {
      "rest": {
        "enabled": true,
        "formats": [
          "html",
          "pdf"
        ]
      },
      "graphql": {
        "enabled": true,
        "formats": [
          "html",
          "gui"
        ]
      }
    }
  },
  "libraries": {
    "rest": {
      "enabled": true,
      "formats": [
        "bash",
        "csharp",
        "dart",
        "go",
        "java",
        "node",
        "ocaml",
        "perl",
        "php",
        "powershell",
        "python",
        "ruby",
        "rust",
        "scala",
        "swift",
        "typescript"
      ]
    },
    "graphql": {
      "enabled": true,
      "formats": [
        "csharp",
        "java",
        "json",
        "kotlin",
        "typescrpit"
      ]
    },
    "postman": {
      "enabled": true
    }
  }
}
```

## Supported Libraries

* TODO: [CycloneDX Software Bill Of Materials (SBOM)](https://github.com/CycloneDX/cyclonedx-node-npm)
* TODO: [TypeDoc](https://github.com/TypeStrong/typedoc)
* TODO: [Redoc](https://github.com/Redocly/redoc)
* TODO: [RapiPDF](https://github.com/mrin9/RapiPdf)
* TODO: [GraphDoc](https://github.com/2fd/graphdoc)
* TODO: [GraphQL Voyager](https://github.com/IvanGoncharov/graphql-voyager)
* TODO: [OpenAPI Generator](https://github.com/openapitools/openapi-generator-cli)
* TODO: [GraphQL Code Generator](https://github.com/dotansimha/graphql-code-generator)
* TODO: [OpenAPI To Postman](https://github.com/postmanlabs/openapi-to-postman)

# Template overview

This Bunnyshell environment [template](https://documentation.bunnyshell.com/docs/templates-what-are-templates) contains a working MinIO instance, ready for you to build upon.

## Template specifics

The component is deployed using the official MinIO container image (`minio/minio`).
It exposes two URLs, one for the MinIO console and another for the actual MinIO service.

&nbsp;

## How to use this Template

- You can create Environments from a [Bunnyshell template](https://documentation.bunnyshell.com/docs/templates-what-are-templates);
- Or you can copy-paste the `minio` component into your own environment definition.

&nbsp;

## Important Note

1. You must change all passwords and review all parameters to ensure that your Environment is secure.
2. Edit the list of IP's allowed to connect to URLs in this environment. By default all IP are granted access.
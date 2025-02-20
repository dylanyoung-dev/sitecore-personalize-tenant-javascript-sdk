# Sitecore Personalize Tenant SDK

Welcome to the Javascript based SDK for using the Sitecore Personalize Tenant/Admin APIs. This repository is useful if you want to create integrations with these APIs. This repository is used by many other repositories such as the Serializer for CDP/Personalize, Automation Testing Scripts and some AI powered integrations I'm working on. Currently this only supports the Cloud Portal for Sitecore CDP/P.

> This **IS NOT** for ingestion of event data, you should use the Sitecore Engage SDK or Cloud SDK depending on your usage needs. (https://doc.sitecore.com/xmc/en/developers/sdk/latest/cloud-sdk/cloud-sdk-and-engage-sdk-comparison-chart.html)

This module is built to support ESM and CommonJS.

# Getting Started - Usage Guides

- [Getting Started (Init/Auth)](./docs/getting-started.md)
- [Templates](./docs/templates.md)
- Flows
  - Experiences
  - Experiments
- Decision Models
- Connections

# Development / Contributions

You can get setup for local development by cloning the repository and running the following commands:

```
$ npm install

$ npm run dev
```

This will start the app in the current terminal window, where changes to the current files, will be reflected immediately (via a watch command with tsup).

# Feature Support

Below is a table that provides details about what is and is not supported currently from Sitecore Personalize. This SDK is currently in active development and the goal is full support with the available APIs, however it is noted below, some cases where the Sitecore Personalize APIs do not support the functionality.

| Feature                |     Supported      | Docs                                          | Examples                          | Notes                                |
| ---------------------- | :----------------: | --------------------------------------------- | --------------------------------- | ------------------------------------ |
| Experiments (Flow)     |     :warning:      | <span style="color:red">No</span>             | <span style="color:red">No</span> | In Progress: Lots of work still left |
| Experiences (Flow)     |     :warning:      | <span style="color:red">No</span>             | <span style="color:red">No</span> | In Progress: Lots of work still left |
| Decision Models        |     :warning:      | <span style="color:red">No</span>             | <span style="color:red">No</span> | Use at your own risk!                |
| Templates (Web)        | :white_check_mark: | <span style="color:yellow">In Progress</span> | <span style="color:red">No</span> | None                                 |
| Templates (Conditions) | :white_check_mark: | <span style="color:yellow">In Progress</span> | <span style="color:red">No</span> | None                                 |
| Templates (JS Modules) | :white_check_mark: | <span style="color:yellow">In Progress</span> | <span style="color:red">No</span> | None                                 |
| Templates (Decisions)  | :white_check_mark: | <span style="color:yellow">In Progress</span> | <span style="color:red">No</span> | None                                 |
| Connections            |     :warning:      | <span style="color:red">No</span>             | <span style="color:red">No</span> | Built but needs testing              |

# Example Repositories

Below is a list of repositories on Github that are using this SDK. If you know of any repositories that have been missed, submit a Pull Request.

- [Sitecore Assistant](https://github.com/dylanyoung-dev/sitecore-assistant): Uses Generative AI with the SDK to create experiences on the fly.
- Sitecore CDP/Personalize Serializer: Coming Soon (currently doesn't use the SDK)

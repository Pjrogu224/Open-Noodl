# Code Crusher

Code Crusher is a fork of the original Noodl open source code under GPL-3.0 license. OpenNoodl / Noodl is a front end React app builder with a visual programming interface. 

Code Crusher will aim to stay entirely in sync with the original repository, including future updates to this repository. A roadmap for updates will be published soon.

# Installing Code Crusher

## One-click install

* [Code Crusher 1.0.1 for MacOS Intel](https://drive.google.com/file/d/11XPs0GjmNdQ4NxQLrtW5hlDqo21Fj_bs/view?usp=sharing)
* [Code Crusher 1.0.1 for MacOS Silicon](https://drive.google.com/file/d/1sGhGTTMTSS-1LBnFPfyg_eWxDPLaUexy/view?usp=sharing)
* [Code Crusher 1.0.1 for Windows](https://drive.google.com/file/d/10N8lZ-NlAO_Cr6Wi1o0CJHVepuVTpEtj/view?usp=drive_link)

## Building from source

See the original Noodl documentation below

# Noodl

[Noodl](https://noodl.net) is a low-code platform where designers and developers build custom applications and experiences. Designed as a visual programming environment, it aims to expedite your development process. It promotes the swift and efficient creation of applications, requiring minimal coding knowledge.

## Documentation
Documentation for how to use Noodl can be found here:
[https://noodlapp.github.io/noodl-docs/](https://noodlapp.github.io/noodl-docs/)

## Community
Main support channel is Discord: [https://www.noodl.net/community](https://www.noodl.net/community)

## Download releases
Pre-built binaries can be [downloaded from Github](https://github.com/noodlapp/noodl/releases)

## Note for users who are migrating from the deprecated closed source version
- [Migrating the project files and workspaces to a Git provider](https://noodlapp.github.io/noodl-docs/docs/guides/collaboration/migrating-from-noodl-hosted-git)
- [Migrate backend and database](https://noodlapp.github.io/noodl-docs/docs/guides/deploy/using-an-external-backend#migrating-from-a-noodl-cloud-service)
- [Self-host frontend](https://noodlapp.github.io/noodl-docs/docs/guides/deploy/hosting-frontend)

## Building from source

```bash
# Install all dependencies
$ npm install

# Start the Noodl Editor and build a production version of the cloud and react runtime (useful when running Noodl from source but want to deploy to production)
$ npm start

# Start the Noodl Editor and watch the filesystem for changes to the runtimes. Development versions of the runtimes, not meant for production (mostly due to source maps and file size)
# This is ideal for a quick workflow when doing changes on the runtimes.
$ npm run dev

# Start Noodl Editor test runner
$ npm run test:editor
```

## Licenses
This repository contains two different licenses for different parts of the Noodl platform.

- Components related to the editor, used to edit Noodl projects, are under GPLv3
- Components related to the end applications, used by the applications Noodl deploys, are under MIT

All of the source code of applications created with Noodl are under MIT. This means you can do project specific changes to the runtime without having to redistribute your changes.

Packaged licensed under MIT:
- `noodl-runtime`
- `noodl-viewer-cloud`
- `noodl-viewer-react`
  
You can find a MIT LICENSE file in each of these packages. The rest of the repository is licensed under GPLv3.

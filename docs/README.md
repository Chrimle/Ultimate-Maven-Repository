# Ultimate Maven Repository

*The Ultimate Maven Repository Template for your GitHub projects!*

## Purpose
This is a *template* repository, used for quickly setting up a GitHub repository with the following features:
- Maven Build Workflow
- Maven Publish Workflow
  - Publish to Maven Central Repository
  - Publish to GitHub Packages
- Pull Request Label Auditing
  - See [Label-Auditor](https://github.com/Chrimle/Label-Auditor).
- Auto Generate Release Notes
- Sponsorships
- Dependabot
  - Maven, GitHub Actions & GitHub Pages
- GitHub Pages
- Citations
- Code of Conduct
- Contribution Guidelines
- Security Policy

> This project also showcases the many features of GitHub, which are not all mandatory.
> Below, is a summary of all provided files.

# Step-by-Step Instructions

## Included Files

This is the complete list of files included in this template. Each file may need additional attention, or mandatory changes.

| Legend | Description             |
|:------:|-------------------------|
|   🔧   | **MUST** be edited.     |
|   ✏️   | **SHOULD** be edited.   |
|   👀   | **SHOULD** be reviewed. |
|   🧐   | **MAY** be reviewed     |
|  🗑️   | **MAY** be deleted      |

### Files

- [`/.github`](.github)<br/><br/>
  - [`/workflows`](.github/workflows)<br/><br/>
    - [`maven.yml`](.github/workflows/maven.yml) 👀 <br/>
      Defines the GitHub Action check to be run on PRs and merged to `main`.<br/><br/>
    - [`maven-publish.yml`](.github/workflows/maven-publish.yml) 👀 <br/>
      Defines the GitHub Action for publishing the Maven Artifact to GitHub Packages & Maven Central Repository.<br/><br/>
    - [`pullRequestAudit.yml`](.github/workflows/pullRequestAudit.yml) ✏️/🗑️ <br/>
      PR Workflow Label checker. Requires:
      - MAJOR
      - MINOR
      - PATCH
      - bug
      - dependencies
      - documentation
      - feature
      - javadocs
      - meta
      - refactor
      - test
      <br/><br/>
  - [`CODE_OF_CONDUCT.md`](.github/CODE_OF_CONDUCT) ✏️/🗑️ <br/>
    Defines the *Code of Conduct* of the project.<br/><br/>
  - [`CODEOWNERS`](.github/CODEOWNERS) ✏️/🗑️ <br/>
    Defines *owners* of files in the repository.<br/><br/>
  - [`CONTRIBUTING.md`](.github/CONTRIBUTING) ✏️/🗑️ <br/>
    Defines the *Contributing* Guidelines of the project.<br/><br/>
  - [`dependabot.yml`](.github/dependabot.yml) 👀 <br/>
    Configures *Dependabot*.<br/><br/>
  - [`FUNDING.yml`](.github/FUNDING.yml) ✏️/🗑️ <br/>
    Configuration for *GitHub Sponsorships*.<br/><br/>
  - [`release.yml`](.github/release.yml) ✏️/🗑️ <br/>
    Configuration for Auto-Generated Release Notes based on *GitHub Issue Labels*.<br/><br/>
  - [`SECURITY.md`](.github/SECURITY) ✏️/🗑️ <br/>
    Defines the *Security* Policy of the project.<br/><br/>
- [`.idea`](.idea)
  - [`/copyright`](/.idea/copyright)
    - [`Apache_2_0.xml`](/.idea/copyright/Apache_2_0.xml) ✏️/🗑️ <br/>
      Defines the *copyright header* to be inserted into project files.
    - [`profiles_settings.xml`](/.idea/copyright/profiles_settings.xml) ✏️/🗑️ <br/>
      Enables the insertion of the *copyright header* to project files.
      <br/><br/>
  - [`google-java-format`](/.idea/google-java-format.xml) 🗑️ <br/>
    Enables `google-java-format` in IntelliJ.<br/><br/>
- [`.mvn`](.mvn)
  - [`jvm.config`](.mvn/jvm.config) 🧐 <br/>
    Maven JVM Config file.<br/><br/>
- [`/docs`](/docs)<br/><br/>
  - [`_config.yml`](_config.yml) 🔧 <br/>
    Config for *GitHub Pages*.<br/><br/>
  - [`README.md`](README.md) 🔧 <br/>
    This README file.<br/><br/>
- [`.gitattributes`](.gitattributes) 🧐 <br/>
  Sets `lf` as EOF.<br/><br/>
- [`.gitignore`](.gitignore) 🧐 <br/>
  Default `.gitignore` provided by GitHub, with `.idea`.<br/><br/>
- [`CITATION.cff`](CITATION.cff) ✏️/🗑️ <br/>
  For citing/referencing the repository.<br/><br/>
- [`LICENSE`](LICENSE) 🧐 <br/>
  Default *Apache 2.0 License*.<br/><br/>
- [`pom.xml`](pom.xml) 🔧 <br/>
  Maven Project file.<br/><br/>

> [!TIP]
> Most files will have a "TODO" comment where attention is needed. It is recommended to use an IDE when resolving
> these comments, as IDEs will highlight these for you!
 
## Generating GPG keys for Uploading
Follow [these](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key) instructions.

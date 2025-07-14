# Ultimate Maven Repository

*The Ultimate Maven Repository Template for your GitHub projects!*

## Purpose
This is a *template* repository, used for quickly setting up a GitHub repository with the following features:
- Maven Build Workflow
- Maven Publish Workflow
  - Publish to Maven Central Repository
  - Publish to GitHub Packages
- Auto Generate Release Notes
- Sponsorships
- Dependabot
- GitHub Pages
- Citations

## Step-by-Step Instructions

### Included Files

This is the complete list of files included in this template. Each file may need additional attention, or mandatory changes.

| Legend | Description             |
|:------:|-------------------------|
|   🔧   | **MUST** be edited.     |
|   ✏️   | **SHOULD** be edited.   |
|   👀   | **SHOULD** be reviewed. |
|   🧐   | **MAY** be reviewed     |
|  🗑️   | **MAY** be deleted      |

#### Files

- [`/.github`](.github)<br/><br/>
  - [`/workflows`](.github/workflows)<br/><br/>
    - [`maven.yml`](.github/workflows/maven.yml) 👀 <br/>
      Defines the GitHub Action check to be run on PRs and merged to `main`.<br/><br/>
    - [`maven-publish.yml`](.github/workflows/maven-publish.yml) 👀 <br/>
      Defines the GitHub Action for publishing the Maven Artifact to GitHub Packages & Maven Central Repository.<br/><br/>
  - [`CODEOWNERS`](.github/CODEOWNERS) ✏️/🗑️ <br/>
    Defines *owners* of files in the repository.<br/><br/>
  - [`dependabot.yml`](.github/dependabot.yml) 👀 <br/>
    Configures *Dependabot*.<br/><br/>
  - [`FUNDING.yml`](.github/FUNDING.yml) ✏️/🗑️ <br/>
    Configuration for *GitHub Sponsorships*.<br/><br/>
  - [`release.yml`](.github/release.yml) ✏️/🗑️ <br/>
    Configuration for Auto-Generated Release Notes based on *GitHub Issue Labels*.<br/><br/>
- [`.mvn`](.mvn)
  - [`jvm.config`](.mvn/jvm.config) 🧐 <br/>
    Maven JVM Config file.<br/><br/>
- [`.gitattributes`](.gitattributes) 🧐 <br/>
  Sets `lf` as EOF.<br/><br/>
- [`.gitignore`](.gitignore) 🧐 <br/>
  Default `.gitignore` provided by GitHub, with `.idea`.<br/><br/>
- [`_config.yml`](_config.yml) 🔧 <br/>
  Config for *GitHub Pages*.<br/><br/>
- [`CITATION.cff`](CITATION.cff) ✏️/🗑️ <br/>
  For citing/referencing the repository.<br/><br/>
- [`LICENSE`](LICENSE) 🧐 <br/>
  Default *Apache 2.0 License*.<br/><br/>
- [`pom.xml`](pom.xml) 🔧 <br/>
  Maven Project file.<br/><br/>
- [`README.md`](README.md) 🔧 <br/>
  This README file.<br/><br/>

> [!TIP] Most files will have a "TODO" comment where attention is needed. It is recommended to use an IDE when resolving
> these comments, as IDEs will highlight these differently.
 
 

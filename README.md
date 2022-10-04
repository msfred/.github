# Organization level templates

The Organization's _.github_ repository is a special repository used for defining organizational level templates that are automatically inherited by all repositories in the organization.

These files can be added to the following folders in the Organization's `.github` repository:
-  the root of the repository
-  the `.github` folder
-  the `docs` folder

The following files can be included in `.github` repository.  If any of your Organization's repositories does not include one of these files, then it will be inherited from the Organization's `.github` repository:

#### Table 1
| File Name          | Purpose                        |
| ---                | ---                            |
| CODE_OF_CONDUCT.md | A CODE_OF_CONDUCT file defines standards for how to engage in a community. For more information, see ["Adding a code of conduct to your project."](https://docs.github.com/en/articles/adding-a-code-of-conduct-to-your-project) |
| CONTRIBUTING.md    | A CONTRIBUTING file communicates how people should contribute to your project. For more information, see ["Setting guidelines for repository contributors."](https://docs.github.com/en/articles/setting-guidelines-for-repository-contributors) |
| FUNDING.yml        | A FUNDING file displays a sponsor button in your repository to increase the visibility of funding options for your open source project. For more information, see ["Displaying a sponsor button in your repository."](https://docs.github.com/en/articles/displaying-a-sponsor-button-in-your-repository) |
| SECURITY.md        | A SECURITY file gives instructions for how to report a security vulnerability in your project. For more information, see ["Adding a security policy to your repository."](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository) |
| SUPPORT.md         | A SUPPORT file lets people know about ways to get help with your project. For more information, see ["Adding support resources to your project."](https://docs.github.com/en/articles/adding-support-resources-to-your-project)|
| Issue & Pull Request templates | Issue and pull request templates customize and standardize the information you'd like contributors to include when they open issues and pull requests in your repository. For more information, see ["About issue and pull request templates."](https://docs.github.com/en/articles/about-issue-and-pull-request-templates) |
| /workflow-templates | Starter Workflows appear when creating a new Actions workflow.  For more information see ["Using starter workflows."](https://docs.github.com/en/actions/using-workflows/using-starter-workflows) |

The following files can be included in your Organization's `.github` repository but will not be inherited by the other repositories.

#### Table 2
| File Name          | Purpose                        |
| ---                | ---                            |
| profiles/README.md | Organization Profile displayed when viewing the Organization |
| README.md          | Default content displayed when viewing the `.github` repository |
| LICENSE.md         | Open source license            |

The following files can be included in any repository.  They will not be inherited from the Organization's `.github` repository.

#### Table 3
| File Name          | Purpose                        |
| ---                | ---                            |
| README.md          | Default content displayed when viewing the repository |
| LICENSE.md         | Open source license            |

> For more information on creating default community health files, see: 
https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file

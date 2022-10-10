## Mandatory for Github repositories

Here is a list of mandatroy tiems to include in any organisation repositories. This is kept intentially lite. 

### Readme
Every Repo should have a README which as a minimum specifies clearly the purpose of the repository.  Ideally this README file would be concise and include additional components covering ownership, development status, context, support for the user and how to contribute to the code. An Ideal example readme can be seen [here](https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md)

### License
Every Repo should have an apporpiate assocaited license and copyright notice.  There are some cases when a license is not needed but this should be a thought through exception rather than the starting point.  The NHS Open source Policy states: "NHS staff exert intellectual property rights for code and documentation through Crown Copyright. Using a copyright notice e.g. _Copyright (c) 2021 Crown Copyright_ ensures that rights to the relevant work reside with the UK Government, and that unless otherwise specified no-one else can copy, distribute or modify your work without risk. Licences then dictate further terms for how people may use copyrighted material.

**All open source projects must be accompanied by a licence.** The default option for NHS open source code is the widely permissive [MIT Licence](https://choosealicense.com/licenses/mit/). Your project may choose to use [APLv2](https://choosealicense.com/licenses/apache-2.0/) instead, and should consider doing so if your code is subject to regulatory requirements (see below). If you wish to ensure that no-one can make proprietary or closed source versions of your code, please use [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html). For all associated documentation you should use the [Open Government 3.0 Licence](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/): projects may use multiple licences for a project as long as they are explicit about which licence applies to which part of the project. Beyond licence assignment in a project’s README file, **the full text of the relevant licences should be included in a top level directory LICENCE file.**"

|Licence  |Use  |
|:---|:---|
| [MIT Licence](https://choosealicense.com/licenses/mit/) | Default licence for all new code  |
| [APLv2](https://choosealicense.com/licenses/apache-2.0) | Where code must be accompanied by legal notices  |
| [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) | To prevent proprietary or closed re-use of code  |
| [Open Government 3.0 Licence](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) | Default licence for all documentation  |

## Recommendations for Github repositories

Here is a list of recommended content to include for project repositories to enable best practice and contributions.

### Changelog
A markdown file in your repository that tracks noteable changes to the code.  Recommendation is to use [semantic versioning](https://semver.org/spec/v2.0.0.html) which reflects `Breaking changes`, `New features`, and
`Fixes` clearly. 

### Contributing file
A piece of text that encourages contributions in the forms of raising new issues and submitting pull requests.  Include reference to the code of conduct and any guidance about branching strategy or style of commit messages to help contributions be made is a standardised way. 

### .gitignore
A file which lists any local file types that should be ignored when a push is made from a local clone back to Github.  This helps protect data files and large outputs from being accidentally uploaded but shouldn't be relied on as the only protection.

### model card
When your code contains a piece of code which someone else may use or reproduce then it's best to make clear the intended use for the code and any known limitations.  One way to do this is to use a model card stating:
- model details 
- Intended use
- Out-of-scope usage
- Training data
- Performance and Limitations
- Notes to the user

### templates for pull requests
to support contributions being submitted in a standardised form you can include a pull request template for fixes and new features.  This will then help contributors know what information to include to support these requests.

### contact
Contact details in the README are useful but this often depends is an appropriate shared mailbox is avilable. 

### branching strategy and pull requests 
See TEAM_WoW.md for suggestion


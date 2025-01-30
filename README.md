- Create a new (free) organization in github.com
  * Preferably a name like aca20XX
  * It is a personal, not institutional account 

- Go to "https://github.com/ApplicationsComputerAlgebra/ApplicationsComputerAlgebra.github.io"
  and choose "Use as template" to create a new repository.
  * name the repository "aca20XX.github.io" where aca20XX is the name of the organization.
  * The repository must be public. 
  * Give a reasonable description, e.g., "30th Applications of Computer Algebra - ACA 2025"

- Go to the organization's settings a give Github actions read and write permissions: https://github.com/organizations/aca2025/settings/actions
- Open file _config.yml, set url to https://aca20XX.github.io and leave baseurl empty (do NOT delete it), as baseurl:. 
- Wait for the actions to rebuild. A new branch called gh-pages will appear,
- Go to Settings --> Pages --> Build and deployment, make sure that Source is set to Deploy from a branch and set the branch to gh-pages (NOT to main).
- The website is ready at https://aca20XX.github.io/
- Set a custom domain if you prefer

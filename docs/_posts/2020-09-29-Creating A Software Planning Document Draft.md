# Create a Draft SPD from Template

Draft Software Palnning Documents (SPDs) can be created and maintained in project repos.  Prior to starting a draft, make sure you have a project repo and team access for all of you collaborators:

Here are GitHub's docs on creating repos and teams:
* [creating a new repository](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-new-repository)
* [about teams](https://help.github.com/en/articles/about-teams)
* [creating a team]( https://help.github.com/en/articles/creating-a-team)
* [team access to repositories](https://help.github.com/en/articles/managing-team-access-to-an-organization-repository)

The SPD should be a collaboration within your project team with input from the nanoMFG node community.
Collaborating on this document is also a good chance for new developers to learn the basics of using Git and GitHub and to 
practice a basic workflow such as [GitHub Flow](https://guides.github.com/introduction/flow/)

## Using the GitHub Website to Start a Draft

### Manually creating a new draft
* Navigate to the SPD template in the `rfcs` directory of this repository: 
[\[project\]-SPD-\[version\].md](https://github.com/nanoMFG/community/blob/master/rfcs/%5Bproject%5D-SPD-%5Bversion%5D.md), click on the raw view, 
    then copy the contents to your clipboard. (always refer to the template for new drafts as it may be periodically updated). <br/> 
    <img width="251" alt="Screen Shot 2019-05-12 at 9 09 48 AM" src="https://user-images.githubusercontent.com/12611210/57582981-3cc2f380-7491-11e9-9e61-526a2f548796.jpg">
    
* Create a SPD document draft
  - Navigate to the `code` tab of your project repo and click: `Add file->create new file`: <br/> 
  - Name the file `<tool-name>-SPD-<#.#.#>.md`, where `<tool-name>` and `<#.#.#>` are the name of your project and the target version of this SPD respectively.  
  For example: <br/> 
 
 <img width="411" alt="94590089-c53f6100-024b-11eb-8b86-adadc06ff573.png" src="https://user-images.githubusercontent.com/12611210/94590089-c53f6100-024b-11eb-8b86-adadc06ff573.png">
  - Commit the new file to a separate branch and open a pull request: <br> 
  <img width="600" alt="Screen Shot 2019-05-13 at 7 28 51 PM" src="https://user-images.githubusercontent.com/12611210/94590445-4696f380-024c-11eb-80e8-036e5efc6c4c.png">
  
  * Use the pull request as a collaboration tool to communicate about the draft with your team.  
  Merge the final draft to master if desired using a similar workflow as that use for editing and maintaining source code (eg [GitHub flow](https://guides.github.com/introduction/flow/)).

# Setup
- Login / Signup to circleci
- Add a project
- Setup project
	- Select OS
	- Select language (python, node js)
- Create a folder named `.circleci` and a file `config.yml` in the repo root folder.
- Update the `config.yml` file with CI/CD pipeline code.

# Leveraging CircleCI in the GitHub pull request workflow
Github provides status checks for the commits in the repo with 3rd party integrators like Circle CI along with the link the pipeline.

Github also provides badges in the readme file.

How to add a badge to the repo with CircleCI
- Goto repo settings in CircleCI
   ![](Pasted%20image%2020230311224839.png)
   ![](Pasted%20image%2020230311224914.png)
   Embed the code shown into the readme file.
   ![](Pasted%20image%2020230311224950.png)
   This is how it looks like.
   ![](Pasted%20image%2020230311225045.png)
   

# Pipelines
## How to skip a pipeline on a perticular commit.

Append `[skip ci]` to your commit message.
`git commit -a -m "remove failing test. [skip ci]"`


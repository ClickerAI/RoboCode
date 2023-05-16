# RoboCode

its a website with two fields and github auth

first is "insert your prompt" field

second is "email"

button send.

"thank you we will respond with github repo link"



create 5 emails

then creates a github organization and adds 5 emails as an owners

then ask gpt to split the tech description onto details

ask gpt to extract a components from the full description. for each component create container level 0

ask gpt to provide detail of each such component. for each subcomponent create container lever 1

repeat for each level of subcomponents. 

create:
  - github projects for the container level 0s
  - github issues from container 1s, 2s, 3s
 

for each github issue:

 - find all text files mentioned in the issue in the codebase.
 - submit its header and text to the GPT code writer executer (it must be quipped with tools for accessing codebase).
 - make it format response as separate files of diffs (prototyped already) with full file paths
 - apply diffs to repo
 - unroll and repeat if github action fails

sync all github issues with `.githubissues/*.md` in the repo

sync all github repo descriptions and existence with .github/REPOS.md

when organization is complete enough, zip it up and send

monetary value: sell github accounts with prefilled repositories for brand new projects
 

"application development as a service": partial stage automation holistic app development human supervised GPT

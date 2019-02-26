# Contributing to HCA-Healthcare README

Thinking of contributing to our engineering repository? That's great! 
Engineers and Non-engineering employees at [HCA Healthcare](https://www.hcahealthcare.com), are encouraged to submit
[pull requests](https://github.com/HCA-Healthcare/Engineering/pulls), [propose and discuss
issues](https://github.com/HCA-Healthcare/Engineering/issues).

If you don't work here at HCA you're welcome to raise [issues or questions](https://github.com/HCA-Healthcare/Engineering/issues) to the engineering team. Or better yet join the HCA
engineering team.
## Editing README

You can edit files via the GitHub interface if you're just trying to quickly make a change. If you want to make a
change that is a bit more nuanced, you can clone the repo and set it up with:

```sh
git clone https://github.com/HCA-Healthcare/Engineering.git
cd Engineering

code .
```

## Automation 
Currently the scripts that generate the table of contents are a work in progress. They are written in Swift so they'll 
have to be executed in MacOS, I have not tried them in Linux yet if you do create an issue and let me know how it goes :-)

Here are the commands to setup the create table of contents script. This will install the `createTOC` command to `/bin` directory
```sh
#from repository root
cd scripts/CreateTOC/
make
```

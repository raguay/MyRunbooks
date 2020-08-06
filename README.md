# MyRunbooks

These are the Runbooks I've created for the [fig](https://docs.withfig.com/)
program. Fig is a terminal assistant that is
really nice!

Runbooks are made with Rundown, a combination of a 
markdown parser and a TIL scripting language. This 
allows for the creation of notebooks that run scripts 
in your current terminal.

## List of Runbooks:

| File | Description |
|---|------|
| CreateRunbooks.run | This Runbook gives the different steps for creating a Runbook. |
| SvelteProject.run | This Runbook allows you to create a Svelte based project and run commands on it. It will flesh our the new project in your project directory. |

## Directory and files needed for these Runbooks

These runbooks expect you to have a directory called `~/.myfig`. In that directory, these files are expected to be there:

| File | Description |
|---|------|
| .currentRunbook | This file contains the name of the current Runbook being edited in the CreateRunbook.run Runbook. |
| .projdir | This file contains the path to the dirctory you keep your Runbooks. |
| .currentSvelteProject | This file contains the name of the Svelte project being edited in the SvelteProject.run Runbook. |
| .svelteprojdir | This file contains the path to the project directory for all your Svelte based projects. |


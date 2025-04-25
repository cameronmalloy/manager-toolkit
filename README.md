# manager-toolkit
My updated toolkit for management resources and scripts to help with management tasks and dilemmas.

# culture
- A first step to measuring the culture of an organization is to assess what you culture is. The culture directory has templates to do so. It follows the paper here: https://faculty.haas.berkeley.edu/chatman/papers/GOM-OReilly-2014.pdf
    - It requires a representative sample of people in the organization to fill out an excel sheet by rating the current culture based on a set of pre-defined cultural values that have been found to represent organizational culture. Whether these are the right values is not clear to me, but this tool is not meant to be permanent or speak the truth, but merely be a starting point for discussion with the team. It will approximate your culture, but it also needs to make fundamental sense to you and the team. In my experience, it has done so.
    - The python notebook will run PCA with varimax rotation as according to the paper and requires 1 manual intervention to interpret PCA graphs (TODO: put those instructions in the python notebook). It will spit out a set of clusters and the cultural values associated and disassociated with each cluster. The clusters are not named and it's up to the user to interpret. I like to plug these into an LLM and ask it to interpret these as cultural values and cultural pillars and see how accurate it is. It's not perfect, but it does the trick to get people talking.

- Concurrently, you can have each person fill out the same form, but instead with the desired culture. You can repeat the process above and see the differences with the results. It will tell you whether you're where you want to be or not. This depends on how much you trust the wanted culture to the desired culture YOU want. It may be useful to use internally - you don't necessarily have to change it.

# data_scripts
1. time series prediction
    - This notebook takes in a csv of time series values and forecasts future values. This is a great quick approximation to get a sense for forecasts or to supplement a visualization for a powerpoint presentation.

# Ethics
- Includes 2 pdf files, `ethical_issues.pdf` and `ethical_toolkit.pdf` which define what ethical issues are and how to view ethical problems from different philosophical view points to have a well rounded view of the problem. It won't help you be right or wrong, but it will help make an informed ethical decision.

# computer_setup
- zshrc: setting up my zsh. Pretty standard with a color coded github stuff :D
- vimrc: requires vundle - https://github.com/VundleVim/Vundle.vim



# Design an intervention builder for the development of digital interventions

## Background

Experiments in behavioural science (psychology, neuroscience, etc.) often
ask participants to complete computer-based behavioural tasks. Developing these tasks is made possible for researchers with relatively little programming experience by task builders that simplify the development process (for example, [jsPsych](https://www.jspsych.org/7.3/), [PsychoPy](https://www.psychopy.org/), and [psychtoolbox](http://psychtoolbox.org/). Unfortunately, there are no equivalent tools to aid mental health researchers in the design and development of digital mental health interventions, such as interventions using anything from mobile applications, to VR and digital sensors. Where behavioural tasks typically present a straightforward and linear sequence of screens in a single session, interventions often include more involved features (such as an online chat with a therapist) and are presented over multiple sessions (requiring features like notifications and progress tracking). Given these added requirements, existing task builders cannot be applied to building interventions in a straightforward way. This limits intervention development to mental health research groups that have resources to hire software developers or researchers with relevant expertise. Therefore, there is a need to develop a tool that will lower the barrier to entry
to digital intervention development.

## Challenge

Design an intervention builder that will aid mental health researchers in developing digital interventions. You should not reinvent the wheel by building features that are already offered by existing task builders. Instead, where possible, you should build on what already exists and focus on developing features that digital interventions need but existing tools do not offer. A simple example
would be integrating existing task builders to design individual sessions and
then sequencing these together over time with your intervention builder. Your tool must consider data privacy where required (for example, for progress tracking applications) and provide (or integrate with) safe data storage solutions. As well
as thinking about building new interventions, your tool should also be able to
store (locally or online) and share workflows/pipelines that are developed on your platform (but should not force users to do this). For your prototype we recommend focusing on features that are most lacking to showcase the power of your tool.

## Questions to answer in your presentation

1. How does your tool help mental health researchers develop digital interventions?
2. How have you minimised the programming expertise required to interact with your tool?
3. How does your tool integrate with existing tools, frameworks, or platforms that researchers might want to use when developing digital interventions?

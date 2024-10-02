# About this Repository

This repository houses all of the Challenge Exercises created to supplement the Red Hat Certified System Administrator study process and is primarily intended for Red Hat Academy students and instructors. 

# Contribution Guide: Gaining Access

Reach out to Kelly Barley (kbarley@redhat.com) if you are a Red Hat Academy instructor or student interested in contributing to the project!

# Contribution Guide: Contributing

Creating a New Challenge Exercise

1. Clone the repository into your local workstation (do this in whichever manner you prefer).

2. Determine where your new exercise best fits in the strcuture: Discrete Tasks (chapter1), Situational Awareness (chapter2), Productivity and Efficiencies (chapter3), or Comprehensive Scnearios (chatper4).

3. Once you've selected your category, go to that associated chapter section within the modules directory. Open that chapter and then open the pages section. From there, create a new "section#.adoc" file and write your exercise!

4. Once written, update the nav.adoc file within the chatper structure to include your new section.

# Testing Locally

If you'd like to test your changes on your local machine before pushing to the main repository (recommended):
1. Make sure you have npm installed on your laptop

2. Ensure you are in the directory of the repository you've been working in to contribute to the project (more than likely the one you cloned to get started)
3. Run npm install .
4. Run npm run watch:adoc
5. Run npm run serve in another terminal and browse the url displayed by this command for local rendering
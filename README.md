felix-target-platform-with-tycho
================================

A tiny project to show how to build a target platform compatible with PDE and Tycho.

There are two modules and a parent POM:
* *feature* defines an Eclipse feature that embeds Apache Felix and other bundles.
* *repository* defines a p2 repository that includes the previous feature.

The parent POM configures Tycho to search the dependencies defined in the POM instead of the feature or in the manifests. 

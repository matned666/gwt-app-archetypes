[![Build Status](https://travis-ci.org/gwidgets/gwt-archetypes.svg?branch=master)](https://travis-ci.org/gwidgets/gwt-archetypes)
## Description

This project provides a set of archetypes for starting your GWT application. All archetypes make use of [Maven GWT Plugin](https://github.com/gwt-maven-plugin/gwt-maven-plugin) as a build tool.  


##Available archetypes

The available archetypes are:

  - gwt-polymer-starter: A polymer based UI inspired from the [Polymer Starter Kit](https://developers.google.com/web/tools/polymer-starter-kit/). This archetype uses Vaadin's [gwt-polymer-elements](https://github.com/vaadin/gwt-polymer-elements). It also uses GWT Activities and Places to handle routing and section change.This archetype generates the client side only.
  
  - gwt-polymer-starter-dagger-di: The same archetype as the gwt-polymer-starter. The difference between the two is that this archetype introduces dependency injection using [Dagger](https://github.com/google/dagger).  
  
  - gwt-polymer-nav-list-detail: This archetype defines a navigation layout with a main side paper menu and sub menus. The layout is responsive, so both the main menu and the sub menu adapt to screen size. This archetype is inspired from Polymer layouts: [http://polymerelements.github.io/app-layout-templates/index.html](http://polymerelements.github.io/app-layout-templates/index.html)

##Usage

On Windows:

    mvn archetype:generate -DarchetypeGroupId=com.gwidgets.maven                ^
      -DarchetypeCatalog=https://oss.sonatype.org/content/repositories/snapshots/ ^
      -DarchetypeArtifactId={artifactName}          ^
      -DarchetypeVersion=0.1-SNAPSHOT                ^
      -DgroupId={yourGroupId}                               ^
      -DartifactId={yourArtifactID}                            ^
      -Dmodule={moduleName}                                  ^
      -Dversion={yourVersion}

On Linux/Mac Os: 

        mvn archetype:generate -DarchetypeGroupId=com.gwidgets.maven                \
      -DarchetypeCatalog=https://oss.sonatype.org/content/repositories/snapshots/ \
      -DarchetypeArtifactId={artifactName}          \
      -DarchetypeVersion=0.1-SNAPSHOT                \
      -DgroupId={yourGroupId}                                \
      -DartifactId={yourArtifactID}                             \
      -Dmodule={moduleName}                                   \
      -Dversion={yourVersion}


##Demos:

- gwt-polymer-starter: [https://gwt-polymer-starter.herokuapp.com/](https://gwt-polymer-starter.herokuapp.com/)
- gwt-polymer-nav-list-detail: [https://gwt-polymer-nav-list.herokuapp.com](https://gwt-polymer-nav-list.herokuapp.com)

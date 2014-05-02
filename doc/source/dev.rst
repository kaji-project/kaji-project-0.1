=======================
Build a dev environment
=======================

Get main repository
===================

Get the kaji main repositories:

::

  git clone git@github.com:kaji-project/kaji-project.git --recursive


Add a new sub repository
========================


# Create a new repository on Github
# Go to the root folder in the main kaji repository (kaji-project)
# Type:

::

  mkdir -p obs_components/graphite-web
  cd obs_components/graphite-web

# Make your first commit

::

  git clone git@github.com:kaji-project/graphite-web.git .
  cp ../shinken/build_package.sh .
  git add .
  git commit -m "First commit"

# Go to the root folder in the main kaji repository (kaji-project)

:: 

    cd ../..

# Then type:

::

  git submodule add git@github.com:kaji-project/graphite-web.git obs_components/graphite-web


Go to the root folder in the main kaji repository (kaji-project) and type:

::

  git add obs_components/graphite-web


Then commit your new sub repository

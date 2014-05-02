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

  cd obs_components

# Make your first commit

::

  git clone git@github.com:kaji-project/graphite-web.git
  cd graphite-web
  cp ../shinken/build_package.sh .
  cp ../shinken/.gitignore .
  osc checkout home:kaji-project graphite-web -o .
  git add .
  git commit -m "First commit"

# Go to the root folder in the main kaji repository (kaji-project)

:: 

    cd ../..

# Then type:

::

  git submodule add git@github.com:kaji-project/graphite-web.git obs_components/graphite-web
  git add obs_components/graphite-web


Then commit your new sub repository




 Kaji Project
// What is Kaji?

Kaji is a bundle of packages
Shinken 1.4
Adagios
PNP4Nagios
Nagvis
// How to use kaji
/// Ubuntu

For xUbuntu 12.04 run the following:
  sudo sh -c "echo 'deb http://download.opensuse.org/repositories/home:/sfl-monitoring/xUbuntu_12.04/ /' >> /etc/apt/sources.list.d/adagios.list"
  sudo apt-get update
  sudo apt-get install adagios

You can add the repository key to apt. Keep in mind that the owner of the key may distribute updates, packages and repositories that your system will trust (more information). To add the key, run:
  wget http://download.opensuse.org/repositories/home:sfl-monitoring/xUbuntu_12.04/Release.key
  sudo apt-key add - < Release.key
/// Debian

For Debian 7.0 run the following as root:
  echo 'deb http://download.opensuse.org/repositories/home:/sfl-monitoring/Debian_7.0/ /' >> /etc/apt/sources.list.d/adagios.list 
  apt-get update
  apt-get install adagios

You can add the repository key to apt. Keep in mind that the owner of the key may distribute updates, packages and repositories that your system will trust (more information). To add the key, run:
  wget http://download.opensuse.org/repositories/home:sfl-monitoring/Debian_7.0/Release.key
  apt-key add - < Release.key
/// Redhat

For RedHat RHEL-6 run the following as root:
  cd /etc/yum.repos.d/
  wget http://download.opensuse.org/repositories/home:sfl-monitoring/RedHat_RHEL-6/home:sfl-monitoring.repo
  yum install adagios
/// CentOS

For CentOS CentOS-6 run the following as root:
  cd /etc/yum.repos.d/
  wget http://download.opensuse.org/repositories/home:sfl-monitoring/CentOS_CentOS-6/home:sfl-monitoring.repo
  yum install adagios
// RoadMap
/// Version 0.1
Deb packages (Ubuntu/Debian compatible)
Shinken 1.4
Adagios
PNP4Nagios
Nagvis
/// Version 0.2
Shinken/Adagios integration
Adagios/Nagvis integration
/// Version 0.3
Replace PNP4Nagios by Graphite
Shinken 2.0 ?
/// Version 0.4
RPM packages (Red Hat/CentOS compatible)
/// Version 1.0
Deb packages (Ubuntu/Debian compatible)
RPM packages (Red Hat/CentOS compatible)
Shinken 2.0
Adagios
Graphite
Nagvis
New Kaji logo
/// Version 2.0
Deb packages (Ubuntu/Debian compatible)
RPM packages (Red Hat/CentOS compatible)
Shinken 2.0
Adagios
Graphite
Nagvis

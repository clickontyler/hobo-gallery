## About Hobo and .hobo Files

[Hobo](http://clickontyler.com/hobo/) is a Mac OS X application by [Click On Tyler](http://clickontyler.com/) that acts as a GUI layer on top of [HashiCorp](https://www.hashicorp.com/)'s [Vagrant](https://www.vagrantup.com/) software.

Hobo generates `.hobo` files, which are designed to live in your source control where you would normally store your `Vagrantfile`. The Hobo application allows you to edit basic settings within your `.hobo` file and then compile those settings into a proper `Vagrantfile`. Thus, rather than maintaining a `Vagrantfile`, you manage your Vagrant environment with Hobo and your `.hobo` file.

The chief benefit of using a `.hobo` file is that it allows you to manage your `Vagrantfile` content in addition to the provisioning commands that go along with it and that are typically stored in a `bootstrap.sh` file.

Hobo is not designed to replace complex provisioning setups that make use of Chef or Puppet. Hobo is not a tool for serious sys-admins deploying complex Vagrant environments. It's designed to be used by casual hobbyists and professionals who have a need for easily reproducable test environments on their local Macs.

`.hobo` files are self-contained and designed to be shared. Technical managers can create one hobo file representing their company's development environment and then pass that `.hobo` file around to their non-technical employees, who can then open that file in Hobo and launch a Vagrant environment without any command line knowledge. Further, useful `.hobo` files are encouraged to be shared publicly via this repository so that others can find, download, and install them.

## Contributing

We encourage you to contribute useful `.hobo` files to this repository for the benefit of the community. Feel free to fork this repo and submit a pull request. Or, you can simply email your `.hobo` file to [support@clickontyler.com](mailto:support@clickontyler.com) and we'll add it here for you.

## Directory of Hobo Files

This section contains an annotated directory of all the publicly available `.hobo` files available in this repo.

* [Click On Tyler WordPress](https://github.com/clickontyler/hobo-gallery/tree/master/hobo-files/clickontyler/wordpress) - a standard, ready-to-use installation of WordPress on Ubuntu 14.04

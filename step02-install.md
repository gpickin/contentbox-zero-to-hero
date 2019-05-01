#Installation

You can get started quickly with ContentBox by leveraging CommandBox, our CLI and package manager, or with our Docker Images.

Today we're going to install locally with CommandBox, we'll save Docker for my session, last session on the last day of the Conference, Friday.

## Install Slugs

### Module

You can install ContentBox as a ColdBox module into any ColdBox 5.x application. Great for embedding ContentBox and for quick CommandBox Updates.

        install contentbox
 
### Site

You can install ContentBox as a ColdBox 5 site with the ContentBox modules as dependencies. Great for containers or non-installer setups

        install contentbox-site
		server start
 
### Installer

You can install ContentBox as a ColdBox 5 site with the ContentBox modules as dependencies and our installer modules for DSN creation and setup.

        install contentbox-installer
		server start
 
### Bleeding Edge
You can install any of our bleeding edge snapshots by adding a `@be` to the identifier:

	install contentbox@be
	install contentbox-site@be
	install contentbox-installer@be

## Let's start the install

    install contentbox-installer

## DB Connectivity

Host: itb.cloudgq.com

User:

Password:

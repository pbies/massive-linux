	massive-linux
	=============

		Linux scripts to run commands on all Linux machines
		in local network or given from host list

	Getting Started
	---------------

		massive-linux1

		1. Download the script to empty folder
		2. Edit password, addresses, commands
		3. Run the script

		massive-linux2

		1. Prepare 0cmds.txt and 0hosts.txt files
		0cmds.txt is file with commands to issue on all servers
		0hosts.txt is file with host;login;password per line
		2. Run mass-linux-ready to gather SSH keys
		3. Run mass-linux2 to issue commands on all servers

	Prerequisites
	-------------

		Linux, password for root - one for all servers (1) or per server (2).
		Nmap (1), ssh-keyscan, sshpass and ssh packages are needed.

	Installing
	----------

		Download and prepare files.

	Running the tests
	-----------------

		Always test your commands locally before issuing them to all machines!!!

	Purpose
	-------

		Script is made for Linux administrators, to massively run commands on
		all Linux machines.

	Built With
	----------

		Midnight Commander, Sublime Text

	Contributing
	------------

		Edits are allowed on separate branches.

	Versioning
	----------

		When there will be new version, the old one will be overwritten.

	Authors
	-------

		me - Initial work

	License
	-------

		This project is licensed under the GNU GENERAL PUBLIC LICENSE - see
		the LICENSE file for details.

		That means you must fulfill these requirements:
		1. your project have the same license
		2. you mention the original author (me)
		3. can't use scripts in commercial nor government environments if
		they are not free and public without my written permission
		4. you can freely modify and use this project for personal usage

	Acknowledgments
	---------------

		Greetings go to Polish public sector for this idea.

		If you like my work please share your opinion with me!

		pikob1 (at) gmail

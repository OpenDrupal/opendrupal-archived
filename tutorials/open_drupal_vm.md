The Open Drupal VM
------------------

The Open Drupal virtual machine gives us a quick way to get a local development environment set up. A 'virtual machine' is a container that acts as if it were a separate computer. It's just like any other app on your computer except that is it's lets you access a whole other operating environment (so you can do things like use Linux if you're running Windows).

First [download Virtualbox](https://www.virtualbox.org/wiki/Downloads) for your host (the operating system you'll be installing Virtualbox on). After you've done this head over to [https://github.com/OpenDrupal/open-drupal-vm](https://github.com/OpenDrupal/open-drupal-vm) and follow the instructions to download the VirtualBox .oma image file and install the virtual machine.

Great! Now we can start using our new development environment. Boot up your machine and take a look around:

* There's a fresh Drupal site already configured. You can access the code for the site at /home/opendrupal/drupal1
* There are a few other useful programs included, like the SublimeText editor.
* The MySQL database system and Apache web server are installed and configured so you shouldn't have to worry about them.
* You can find the default passwords in the [readme file](https://github.com/OpenDrupal/open-drupal-vm#passwords) of the Open Drupal VM GitHub repository.

### Downloading modules

To download a module click on the 'Terminal' app in the sidebar. Then type in:

```cd /home/opendrupal/sites/drupal1```

This will move you into the Drupal directory. Then we use [Drush](http://www.drush.org/) to download a module, to download the views module type in:

```drush dl views```

And to enable the module using Drush we can use the 'drush en' command:

```drush en -y views```

The '-y' flag is a shortcut so we don't have to type yes in!

### Editing Drupal files

The Open Drupal VM comes with Sublime Text, open the editor and then add the /home/opendrupal/sites/drupal1 folder to the editor. From here you'll be able to navigate through your site files and edit them. Make sure you never hack core!

### Fixing problems

There are some known issues documented in the [Open Drupal VM Github wiki](https://github.com/OpenDrupal/open-drupal-vm/wiki/Troubleshooting). If you encounter something you, open an issue in the [issue queue](https://github.com/OpenDrupal/open-drupal-vm/issues) and a friendly developer may help you out with it!

### Adding syntax highlighting for Sublime Text

To install syntax highlighting, search Google and follow instructions!


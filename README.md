# NetBeans MacOS Bundle
When I originally put this little project together it was intended to be a tempoary quick way to get NetBeans installed on a Mac. I did not anticipate the amount of feedback I have received (which is very much appreciated) and that has caused me to make a few changes along the way.

First off, you should either clone or download this project if you want to use the original install script.

To run it, use the install.sh script. The user is prompted for the password because the script includes "sudo's" to gain permission to the /Applications folder.

### Installation

````
cd Downloads
git clone https://github.com/whallysson/netbeans-macos-bundle.git
cd netbeans-macos-bundle/
./install.sh
````

When the download finishes, it asks for the root password to finish the installation.

Now it's only in your applications and Netbeans 10 will be there. =)

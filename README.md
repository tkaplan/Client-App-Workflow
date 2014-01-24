Editing Bootstrap

To edit bootstrap css file we use less. You must have ruby, gem and npm installed to run the watch and compilation scripts for the less files.

If you don't have less installed, install it with node.js by running the following command:

npm install -g less

Do not forget to use the -g flag as that installs lessc globally.

To allow your project to continue to monitor changes for your custom bootstrap less files and recompile them we must have watchr installed. We do this through gem.

Install watchr via:

gem install watchr

You must also have ruby installed for the next part to work.

You may then navigate to the directory:

<Client-App/bower_components/bootstrap$ watchr watch.rb&

Only modify your using less in your 

<Client-App/bower_components/bootstrap/less directory. If you want to add
partials, just add your my_custom_file_that_I_made_up.less file and include it in your bootstrap.less file by appending it to the end of the file like so:

@import "my_custom_file_that_I_made_up.less";

All less files need to be installed in the Client-App/bower_components/bootstrap/less directory.


That is all I have to say for the basic setup of this project.

Enjoy!

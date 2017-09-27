# AFTrack resource

This is just a try to make it easier to get languages files translated.

<pre>
res/values/strings.xml is the main file 

res/values-de/strings.xml is the German translation (finished)

res/values-it/strings.xml is the Italian translation (finished)

res/values-ru/strings.xml is the Russian translation (only partly, not part of AFTrack at the moment)
</pre>

If you like to add your own translation please
create a fork to your account

With git start to clone this files to your local machine

<pre>
$ git clone https://github.com/your_account/aftrack_resource.git 
</pre>

To add a language to this system please add a folder
e.g res/values-fr and copy the default string.xml (folder 'values') into this new folder
And start the translation

Later on add it to the git repository

<pre>
$ git status
$ git add .
$ git status
</pre>

Commit your work

<pre>
$ git commit -m 'add fr to resource'
</pre>

And bring it back to the git server

<pre>
$ git push origin master
</pre>

When you are ready with changes please open a pull request in your repository to inform me.

[Git](https://stackoverflow.com/questions/390381):  Pull new updates from original GitHub repository into forked GitHub repository


You could also send me a mail with a string.xml file 

Thanks for all

[Homepage](https://afischer-online.de/and/aftrack) to get more info about AFTrack

[Sailing Page](https://afischer-online.de/and/aftrack/sailing/) to get more info about AFTrack and sailing/

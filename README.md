# PB-for-J
Posts Builder for Jekyll<br />
------------------------
If you have not looked into [Jekyll](https://jekyllrb.com/ "Jekyll"), the simple blog-aware static site generator, then I highly reccomend you do!

I wrote this for myself, but Jekyll bloggers might find it useful.
PB for J is a simple ruby script I wrote, to automate the process of creating a new post file in your Jekyll blog, located in the _posts directory.

The format for a Jekyll post file name: 

****************************************************************

2017-05-10-welcome-to-jekyll.markdown

****************************************************************

As you can see from above, the Jekyll post file name, requires the current date in the name itself, followed by your chosen name.
PB for J automatically syncs your computer's current date and adds it to the file name.
Once it has added the date within the post file name, it will prompt you for the rest of the file name ("welcome-to-jekyll").

Inside every Jekyll post file, a YAML [Front Matter](https://jekyllrb.com/docs/frontmatter/ "Jekyll Front Matter") block is required at the top, such as the one below:

>--- <br />
>layout: post <br />
>title: "PB for J is awesome!" <br />
>date: 2017-05-25 16:26:32 -0500 <br />
>categories: Jekyll <br />
>--- <br />
(note: That is the default file settings above, if user does not provide any. You can easily change them later.) <br />
(The default post file name is: 2017-05-25-pb-for-j.markdown) (The date will be different of course.) 


PB for J, does not require you to know any Ruby, or any programming at all. 

1.) Jekyll bloggers can simply download the zip file. <br />

2.) Once it is downloaded, unzip it and drag the "pbforj.rb" file to your Jekyll _posts directory. <br />

3.) Once the pbforj.rb file is placed within your _posts directory, go download [Ruby](https://www.ruby-lang.org/en/downloads/ "Ruby") if you do not already have it on your system. <br />

4.) Once Ruby is successfully installed on your system, make sure Ruby can be accessed through your terminal. Try typing "ruby -v" to check. Windows users may have to include it in their path manually. <br />

5.) Once you have verified that ruby is accessible through your terminal, you can now use PB for J. <br />

6.) To use PB for J, move into your Jekyll _posts directory, where you should find the pbforj.rb file from earlier. <br />

7.) To use PB for J to create a new post file, type "ruby pbforj.rb" (without the parentheses). PB for J with execute and prompt you for the: Name of the file, Title of your new post, and the extension of your file (eg. markdown, html, etc.), just leave blank if you use markdown. <br />
<br />
YOUR DONE! NOW GET BLOGGING WITH JEKYLL!
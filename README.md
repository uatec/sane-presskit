Why am I seeing this page?

The installation procedure is almost done, but you'll probably need another thirty to sixty minutes to fully complete installation. Don't worry - things aren't in much of a hurry, you can always close this tab now and return later.

If you are ready, you will need FTP & XML-editing capabilities. Please complete the following steps to finish the installation.

Required actions

Edit the _data.xml file that was created in the folder containing install.php & update it with the correct information.
Upload header.png (1200 pixels wide, up to 240 pixels high) to the images directory.
Upload appropriate *.png files to the images directory. No further action is required to make the images show up.
Optional actions

(Optional) Archive all the images and upload the file as images.zip. No further action is required to make the download show up.
(Optional) Upload logo.png or icon.png. No further action is required to make the images show up.
(Optional) Archive the logo, icon and variations on them and upload the file as logo.zip. No further action is required to make the download show up.
(Optional) Upload appropriate *.mov or *.mp4 files in the trailers directory. Update _data.xml accordingly for this step, the <mov> and <mp4> tags are needed in the trailer entry for these downloads to show up.
Additional services

(Optional) Enable Google Analytics to track traffic to your presskit() by adding <analytics>your property id</analytics> to your _data.xml file.



When this is all over, you probably want to add a project or some. Take a look at the files in the _template folder to see how you create a project. To easily create a project, duplicate the _template folder and rename it to the projects name in lowercase, replacing any white spaces with underscores. Imagine you have a project called "Super Crate Box", it would reside in a folder called "super_crate_box".
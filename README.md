
<div align="center">
<img src="https://i.imgur.com/H71y4Pp.png" alt="gdrive-dir2html" height="">
</div>
 <div align="center">
 <img alt="gdrive-dir2html-license" src="https://img.shields.io/badge/Open_source-MIT-red.svg?logo=git&logoColor=green"/>
<img src="https://img.shields.io/github/last-commit/alx-xlx/gdrive-dir2html.svg?logo=Sublime+Text&logoColor=green&label=Active"/>
<img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/alx-xlx/gdrive-dir2html">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/alx-xlx/gdrive-dir2html">
<img alt="gdrive-dir2html-softwareheritage.org" src="https://archive.softwareheritage.org/badge/origin/https://github.com/Unipisa/CMM/"/>
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/alx-xlx/gdrive-dir2html">
<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Falx-xlx%2Fgdrive-dir2html&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Views&edge_flat=false"/>

</div>
 
# gdrive-dir2html

This is a small Jupyter Notebook Script that will generate an standalone single page HTML index of all the Files and Folders in your Google Drive. It can also generate short information like Size and Modified date of these Files & Directories.

It is an alternative to [Snap2HTML](http://www.rlvision.com/snap2html/about.php) but for Linux Machine


# What is it used for ?

There are many reasons for using it. These are often used by users who have large amount of data stored and they do not want to use normal search. Instead they can generate the index and use the search mechanism on gdrive-dir2html to pin point the required files/folders. Likewise, you may have multiple HDD, instead of plugging them each to find your files/folders you can simply generate the dir2html and move from there.


[**example.html**](https://alx-xlx.github.io/gdrive-dir2html/example.html) - https://alx-xlx.github.io/gdrive-dir2html/example.html

**example.png**

![](example.png)

# How to generate Google Drive Index HTML

### 1. Run this Colab Script to Index Google Drive
<!-- Open in Colab in Center -->
<a href="https://colab.research.google.com/github/alx-xlx/gdrive-dir2html/blob/master/gdrive_dir2html.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" alt="Open In Colab" class='centre' data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" style="max-width:100%;display:block;margin-left:auto;margin-right:auto;"></a>

### 2. Click on Connect

### 3. Connect to your Google Drive
under `Mount Google Drive` you will see a play button, click on it. Allow all the Permissions.

If success you will now see the Google Drive listed as drive on your Notebook's left Panel (you need to select the Files Tab to see it)

### 4. Clone the `gdrive-dir2html` to your Notebook
Run the next cell on your notebook marked as `Run this code to Clone gdrive-dir2html Repo`

### 5. Generate the HTML index of your Google Drive
Run the last code cell, it will prompt to enter the directory you need to index.
If you need to Index any specific directory then browse to that directory in Files TAB on your left Panel and copy the PATH and Paste it to the Prompt. OR if you want to Index your whole Google Drive then you can simply enter `/content/drive`

Press ENTER

### 6. Download Google Drive Index HTML file
on the left Files Panel you will now see the Generated Index File. If not then refresh the File System (NOT your browser)

Example: `index-28-09-2022-05-43-57.html`


<!-- https://i.imgur.com/hCFNHhN.gif -->

<!-- ![](https://i.imgur.com/sj4PEUo.gif) -->

<p align="center"><img src="https://i.imgur.com/sj4PEUo.gif" alt="LOGO"></p>

OR

### 2. Run Locally to Index Local Drives

The program only takes two arguments, the directory to be indexed and the output file name without the extension, so:

```gdrive-dir2html.py /home/user filelist```
 
Will index the contents of /home/user and save them to filelist.html on the current directory. Simple as that





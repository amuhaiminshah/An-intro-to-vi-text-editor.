# An-intro-to-vi-text-editor.
The default editor that comes with the UNIX operating system is called vi (visual editor). Using vi editor, we can edit an existing file or create a new file from scratch. we can also use this editor to just read a text file.






# Let's dive into it.
### 1-Lesson:
There are <b> two </b> modes. One is < insert mode > the another is < command mode >. So when you first open the <b> < vi,< file name > </b>  so it is always in <b> < command mode > </b>, if you wanna go to the editing mode so simply press <b> < i > </b> so then you can write, basically <b> < i > </b> means <b> < insert > </b>. If you wanna go to command mode so simply press <b> < Esc > </b>, where you can type commands.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/Vieditor.jpg" alt="vi editor"> 

### 2-Lesson:
#### 1-Open the terminal and write vi < file name >.
##### For example:
###### Input:
<pre> muhiamen@sysbox:~$ vi intro-to-vi </pre>
###### Output:
<pre>
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
"intro-to-vi" 1 line, 27 characters
</pre>
 
  
  
#### 2-Such this type of display will come:
##### For example:
<pre> 
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
"intro-to-vi" 0 lines, 0 characters
</pre>
##### NOTE: 
In the above example in the double cotation there is the name of file, there is also written that there are 0 lines, 0 characters

  
#### 3-Now we are in command mode so press <b> < i > </b> to get into instert mode.
##### For example:
<pre>
I am doing practice of vi.
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
"intro-to-vi" 0 lines, 0 characters
</pre>
###### NOTE:
You might be thing that we have write some thing but still he is show us 0 lines, 0 characters it's because that we have't save our work yet.
  
  
  
### 3-How to save work:
##### <b> < :w > </b>  This command is used to save work without exit.
##### For example:
###### Input:
<pre>
I am doing practice of vi.
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
"intro-to-vi" 0 line, 0 characters written
</pre>
  
###### Output:
<pre>
I am doing practice of vi.
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
"intro-to-vi" 1 line, 27 characters
</pre>
###### NOTE:
Now you can see our work is save.
  
##### <b> < :wq > </b> This command is used to save work with exit.
###### For example:
###### Input:
<pre>
I am doing practice of vi.
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
:wq
</pre>
###### Output:
<pre> muhiamen@sysbox:~$ </pre>

##### <b> < :w! > </b> This command discard all changes, since the last save, and exit.
###### For  example:
###### Input:
<pre> 
Don't save this line. 
I am doing practice of vi.
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
:q!
</pre>

###### NOTE:
It will exit from the vi so again write the command of vi.
  
###### Output:
<pre>
I am doing practice of vi.
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
~                                                                                                                                             
"intro-to-vi" 1 line, 27 characters
</pre>


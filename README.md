## Laboratory 0 - OOP

### Stepts taken:  

1. OS installation - Ubuntu 22.04.1
2. `build-essentials` installaion  
3. `zsh` and `oh-my-zsh` intallation and setup  
4.  Creation of `lab_0.c` and Makefile  
5. `git` setup, repository creation, pushing the repo  

#### OS installation
The UNIX-based operating system chosen was Ubuntu, set up on a separate disk drive, accessible via dual boot.
Accessed the new OS after successful installation:  

![Fresh install Desktop screenshot](/Screenshots/Hello_Ubuntu.png)

#### `build-essentials`, `zsh`, `oh-my-zsh` setup
Opening up the Terminal, I have installed the aforementioned tools, which include gcc, g++, make and several other tools  

![Build essentials tool bundle install screenshot](/Screenshots/gcc.png)  

Following, I have installed `zsh` and set it as the default shell:  

![zsh setup screenshot](/Screenshots/zsh.png)  

Restarting the Terminal, we now work on `zsh`. We can now setup the `oh-my-zsh` extension:  

![oh-my-zsh setup screenshot](/Screenshots/oh-my-zsh.png)  

Notice the differences in the terminal prefixes.  
We then edit the `~/.zshrc` file to set a custom theme: agnoster, as it is more visually appealing.  

#### The C code:
`lab_0.c` includes a basic "Hello World" script  
The Makefile includes 2 targets:  
* all - creates a `hello_world.exe` from the C file  
* clear - deletes any existing .o and .exe files within the directory  

#### `git` setup
After successfully installing `git`, we create a new repository in the directory containing our code and add our files to it:  
![Git init screenshot](/Screenshots/git1.png)  

Then, we create an SSH key and use it for authentification in order to be able to push our repository to GitHub  
![Git push screenshot](/Screenshots/git2.png)  

The fact that the files are visible on GitHub proves that everything went successfully

Furthermore, all the screenshots made during the process have been added to a subdirectory and later pushed to the repo:  
![Moving the screenshots](/Screenshots/screenies.png)  

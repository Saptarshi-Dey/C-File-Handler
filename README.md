# <ins>Contact Manager app using C-File-Handler</ins>

## The clear variable is a character array that stores the command to clear the console. It depends from browser to browser.<br> The reason for creating 2 seperate files is to make compiling easy. The first one is the cross platform version. The second one will only compiler on windows. 
## The ***conio.h*** is a header file only available for the Windows platform because of which we can't use the ***getch()*** function. <br> In Linux, we have to use the Ncurses library (***curses.h*** or ***ncurses.h***) to mimic the usage of ***getch()***. 

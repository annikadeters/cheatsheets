# Shell Commands

$ = shell prompt, It appears when the terminal is ready to accept a command.


directories = folders (organized into a filesystem)
* First directory = root directory

Command | Description
-------- | -----------
ls | lists the files and folders inside the folder you are in
pwd | “print working directory” /  It outputs the name of the directory you are currently in, called the working directory.
cd | “change directory” / cd switches you into the directory you specify. In other words, cd changes the working directory. Nur das eingeben und man kommt wieder ins root.
cd ../../action/ | 
argument | When a file, directory or program is passed into a command, it is called an argument. e.g. cd 2015 - 2015 ist the argument, which you want to go into (folder/directory 2015). The cd command takes a directory name as an argument, and switches into that directory. To navigate directly to a directory, use cd with the directory’s path as an argument. Here, cd jan/memory/
cd .. | To move up one directory, use cd ..
cd ../feb | different directory, same level
mkdir | “make directory” / It takes in a directory name as an argument, and then creates a new directory in the current working directory.
touch | creates a new file inside the working directory. It takes in a filename as an argument, and then creates an empty file in the current working directory.
ls -a | modifies the behavior of the ls command to also list the files and directories starting with a dot (.). Files started with a dot are hidden, and don’t appear when using ls alone. = option
option | Options modify the behavior of commands. e.g. -a
ls -l | lists all contents of a directory in long format, lists files and directories as a table. 
ls -t | order files and directories by the time they were last modified.
ls -alt | In addition to using each option separately, like ls -a or ls -l, multiple options can be used together, like ls -alt. Here, ls -alt lists all contents, including hidden files and directories, in long format, ordered by the date and time they were last modified.
cp | copies files or directories.
cp xx | To copy a file into a directory, use cp with the source file as the first argument and the destination directory as the second argument. e.g. cp biopic/cleopatra.txt historical/
cp xx | To copy multiple files into a directory, use cp with a list of source files as the first arguments, and the destination directory as the last argument. e.g. cp biopic/ray.txt biopic/notorious.txt historical/
mv | moves files. It’s similar to cp in its usage. 
mv xx |To move a file into a directory, use mv with the source file as the first argument and the destination directory as the second argument. e.g. mv superman.txt superhero/ 
mv xx | To move multiple files into a directory, use mv with a list of source files as the first arguments, and the destination directory as the last argument. e.g. mv wonderwoman.txt batman.txt superhero/ 
mv xx | To rename a file, use mv with the old file as the first argument and the new file as the second argument. e.g. mv batman.txt spiderman.txt
rm | deletes files and directories; argument gets deleted
rm -r | The -r is an option that modifies the behavior of the rm command. The -r stands for “recursive,” and it’s used to delete a directory and all of its child directories. Be careful when you use rm! It deletes files and directories permanently. There isn’t an undelete command, so once you delete a file or directory with rm, it’s gone.
echo | Zeigt die angegebenen Zeichen
echo xx >>> | ???? Datei wird erstellt?
cat | Datei, Dateiname wird angezeigt
less | Datei(-inhalte) werden angezeigt, in denen man navigieren kann
open | Datei wird im VS Code angezeigt/geöffnet
tree | Verzeichnis in Baumstruktur (muss vorher über brew install tree - Befehl installiert werden) 

### Wildcards

cp * satire/

In addition to using filenames as arguments, we can use special characters like * to select groups of files. These special characters are called wildcards. The * selects all files in the working directory. so here we use cp to copy all files into the satire/ directory.

cp m*.txt scifi/

Here, m*.txt selects all files in the working directory starting with “m” and ending with “.txt”, and copies them to scifi/.




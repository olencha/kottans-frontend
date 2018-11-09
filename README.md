## Git and GitHub

<p> That's all new for me. I never used git before, but it's seems very useful. I learned how to use terminal (basic
    commands like git log, git clone, git push etc.), how to find bugs in previous version, how to work with repository
    and more importent - how to collaborate with team throught GitHub (pull requests, forks, branches etc).</p>

<p> Thanks for so interesting compilation of training materials. I really delighted when Udacity suggested looking for
    bugs
    in games. Gamification help learn faster.
</p>
<p>
    Also extra material "Как учиться и справляться с негативными мыслями" created for me good atmosfere, you care about
    mind health of students . :)
</p>

<hr>

## Linux CLI, and HTTP
![task1 screenshot](/task_linux_cli/task_linux_cli_1.png)
![task1 second screenshot](/task_linux_cli/task_linux_cli_2.png)

<p>I need to summarize information in one place. Thanks for this task. It was excellent addition to the previous task. I understand the value of command line, but need some time to comprehend how to use it in work.</p>

<p> NAVIGATING THE FILE SYSTEM</p>
<p> From the command line, you can navigate through files and folders on your computer:</p>
<ul>
    <li> <b>pwd</b> outputs the name of the current working directory.</li>
    <li> <b>ls</b> lists all files and directories in the working directory.</li>
    <li> <b>cd</b> switches you into the directory you specify.</li>
    <li> <b>mkdir</b> creates a new directory in the working directory.</li>
    <li> <b>touch</b> creates a new file inside the working directory.</li>
</ul>

<p> VIEWING AND CHANGING THE FILE SYSTEM</p>
<p>Options modify the behavior of commands:</p>
<ul>
    <li> <b>ls -a</b> lists all contents of a directory, including hidden files and directories</li>
    <li> <b>ls -l</b> lists all contents in long format</li>
    <li> <b>ls -t</b> orders files and directories by the time they were last modified</li>
    <li> Multiple options can be used together, like <b>ls -alt</b></li>
</ul>
<p>From the command line, you can also copy, move, and remove files and directories:</p>
<ul>
    <li><b>cp</b> copies files</li>
    <li><b>mv</b> moves and renames files</li>
    <li><b>rm</b> removes files</li>
    <li><b>rm -r</b> removes directories</li>
</ul>
<p>Wildcards are useful for selecting groups of files and directories</p>

<p>REDIRECTING INPUT AND OUTPUT</p>
<p>Redirection reroutes standard input, standard output, and standard error.</p>
<p>The common redirection commands are:</p>
<ul>
    <li> <b>[ > ]</b> redirects standard output of a command to a file, overwriting previous content.</li>
    <li> <b>[ >> ]</b> redirects standard output of a command to a file, appending new content to old content.</li>
    <li> <b>[ &lt; ]</b> standard input to a command.</li>
    <li> <b>[ | ]</b> redirects standard output of a command to another command.</li>
</ul>
<p>A number of other commands are powerful when combined with redirection commands:</p>
<ul>
    <li><b>sort</b>: sorts lines of text alphabetically.</li>
    <li><b>uniq</b>: filters duplicate, adjacent lines of text.</li>
    <li><b>grep</b>: searches for a text pattern and outputs it. -R stands for "recursive" and l stands for "files with
        matches". Here grep -Rl searches the /home/ccuser/workspace/geography directory for the string "Arctic" and
        outputs filenames
        with
        matched results.</li>
    <li><b>sed</b>: searches for a text pattern, modifies it, and outputs it.</li>
</ul>
<p>
    Example: sed $ sed 's/snow/rain/' forests.txt sed stands for "stream editor" . It accepts standard input and
    modifies
    it based on an expression, before displaying it as output data. It is similar to "find and replace" . Let's look at
    the
    expression 's/snow/rain/' : s: stands for"substitution" . it is always used when using sed for substitution. snow:
    the
    search string, the text to find.rain: the replacement string, the text to add in place.
</p>

<p> ENVIRONMENT</p>
<p>The environment refers to the preferences and settings of the current user.</p>
<p>The nano editor is a command line text editor used to configure the environment.</p>
<ul>
    <li> <b>~/.bash_profile</b> is where environment settings are stored. You can edit this file with nano.
        environment variables are variables that can be used across commands and programs and hold information about
        the environment.
        export VARIABLE="Value" sets and exports an environment variable.</li>
    <li><b>USER</b> is the name of the current user.</li>
    <li><b>PS1</b> is the command prompt.</li>
    <li><b>HOME</b> is the home directory. It is usually not customized.</li>
    <li><b>PATH</b> returns a colon separated list of file paths. It is customized in advanced cases.</li>
    <li><b>env</b> returns a list of environment variables.</li>
    <li>The <b>less</b> command is similar to cat, but is better adapted to handling larger files. It displays files in the
        terminal one page at a time.</li>
</ul>


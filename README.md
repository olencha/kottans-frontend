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

<p>I need to summarize information in one place. Thanks for this task. It was excellent addition to the previous task. I understand the value of command line,now I know how to use it.</p>

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
<ul>
    <li><b>The nano editor</b> is a command line text editor used to configure the environment.</li>
    <li> <b>~/.bash_profile</b> is where environment settings are stored. You can edit this file with nano.
        environment variables are variables that can be used across commands and programs and hold information about
        the environment.</li>
    <li> <b>exportVARIABLE="Value"</b>  sets and exports an environment variable.</li>
    <li><b>USER</b> is the name of the current user.</li>
    <li><b>PS1</b> is the command prompt.</li>
    <li><b>HOME</b> is the home directory. It is usually not customized.</li>
    <li><b>PATH</b> returns a colon separated list of file paths. It is customized in advanced cases.</li>
    <li><b>env</b> returns a list of environment variables.</li>
    <li>The <b>less</b> command is similar to cat, but is better adapted to handling larger files. It displays files in the
        terminal one page at a time.</li>
</ul>

### HTTP
<p>
    I already knew how DNS, domain, IP works together. Also about difference between http and https (how to get digital certificate). New to me was how to develope it all from scratch. I will try to apply the knowledge practically and return to this question.
 </p>   
<p>
<b>For future:</b> Come back here to repeat information after practical apllication.
</p>
<p>
<a href="https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177" rel="nofollow">HTTP: The Protocol Every Web Developer Must Know - Part 1</a>
</p>
<p>
<a href="https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155" rel="nofollow">HTTP: The Protocol Every Web Developer Must Know - Part 2</a>
</p>

## Git Collaboration

![git version control](/task_git_collaboration/github-collaboration.png)
![github collaboration](/task_git_collaboration/version-control-with-git.png)

<p>
Detailed and useful courses. Feel myself like professional Git and Github user :) I have definitely increased my knowledge,because of clear, understandable learn materials. Now, I better understand the difference between git fetch and git pull, how to work with remote repository, local-fork-original repositories and etc.
</p>
<p>
I will:
</p>
<ul>
    <li>use git log --oneline, --author=, --grep=, shortlog (so easy!)</li>
    <li>create backup branches</li>
    <li>pull/fetch before push when work with team</li>
    <li>have to deal with git rebase -i</li>
</ul>
<p>
Also I liked additional information about CONTRIBUTING.md, README.md, writting small, focused commits. It help think in way of developer that have expirience in that.
</p>

## Intro to HTML and CSS
![udacity html/css course](/task_html_css_intro/udacity_html_css_class.png)
![htmlacademy classes](/task_html_css_intro/html_academy_tasks.png)

<p>
I repeated and systematized my knowledge in HTML and CSS. Of course, I will use what I have learned. It was important task for me, because reminded that I must know basic details firstly. 
</p>

## Responsive Web Design
![udacity responsive web design](/task_responsive_web_design/udacity_responsive_web_design.png)
![flexbox froggy game](/task_responsive_web_design/flexbox_froggy.png)

<p>
I was learn how to create responsive pages. It was interesting about mobile-first (developing sites by starting small). Also I learned common responsive patterns - Column Drop, Mostly fluid, Layout Shifter, Off Canvas. Also, cool tip about make buttons at least 48x48px. 
</p>
<p>
I liked flexbox froggy game. It helped me to repeat flexbox skills and explained the knowledge gaps. For example, I didn't know that when a column is selected as a direction, justify-content affects the vertical alignment, and align-items on the horizontal one.
</p>
<p>
I will definitely use new knowledge.
</p>
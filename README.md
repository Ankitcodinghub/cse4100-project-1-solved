# cse4100-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE4100 Project 1 Solved](https://www.ankitcodinghub.com/product/cse4100-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94207&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE4100 Project 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Project Overview

In this project, the students will learn and become familiar with the concepts of system-level process control, process signalling, interprocess communication and running processes and jobs in the background in Linux Shell. Students will learn this by programming a simple yet customized Linux shell that supports all the aforementioned functionalities in their own programmed shell.

Linux Shell:

A shell is an interactive command-line terminal program whose primary purpose is to execute user-provided commands and run other programs. A shell repeatedly prints a prompt, waits for a command line on the terminal via stdin, and then performs action as directed by the contents of the command line.

Project Pre-requisites

Familiarity with c/c++ programming and Linux shell commands.

This project consists of three incremental phases, where each phase is must pre-requisite for the next phase, i.e., You will be extending the functionality of your shell in every project phase.

Project Phase I: Building and Testing Your Shell Points: 30

Task Specifications:

Your first task is to write a simple shell and starting processes is the main function of linux shells. So, writing a shell means that you need to know exactly what is going on with processes and how they start.

Your shell should be able to execute the basic internal shell commands such as,

<ul>
<li>– &nbsp;cd, cd..: to navigate the directories in your shell</li>
<li>– &nbsp;ls: listing the directory contents</li>
<li>– &nbsp;mkdir, rmdir: create and remove directory using your shell</li>
<li>– &nbsp;touch, cat, echo: creating, reading and printing the contents of a file</li>
<li>– &nbsp;exit: exit all the child processes and shell quits
A command is always executed by the child process created via forking by the parent process except cd.
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Shell program

Hints:

The shell mainly relies on fork( ) and exec( ) system calls. These two system calls are actually the building blocks for how most programs are executed on Linux. First, an existing process forks itself into two separate ones. Then, the child uses exec( ) to replace itself with a new program.

Your shell is constantly running loop with three functionalities inside;

do {

Shell Prompt: print your prompt

printf (“CSE4100:P4-myshell &gt;”);

Reading: Read the command from standard input. input = myshell_readinput ();

Parsing: transform the input string into command line arguments args = myshell_parseinput (input);

Execute: Execute the command by forking a child process and return to parent process myshell_execute(args);

} while{true};

Note: Please consult the man pages for the fork(), exec(), wait() and other related system calls. Evaluation:

– Your shell should perform all the functionalities explained in task specifications above.

</div>
</div>
<div class="layoutArea">
<div class="column">
Project I: MyShell Instructor: Prof. Youngjae Kim

</div>
</div>
<div class="layoutArea">
<div class="column">
fork ()

return to parent ()

</div>
<div class="column">
Child process

</div>
<div class="column">
Execute ls command

</div>
</div>
<div class="layoutArea">
<div class="column">
CSE4100-SP-P1 &gt; ls .

</div>
</div>
<div class="layoutArea">
<div class="column">
Parent process

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Project Phase II: Redirection and Piping in Your Shell Points:

Task Specifications:

In this phase, you will be extending the functionality of the simple shell example that you programmed in project phase I. Start by creating a new process for each command in the pipeline and making the parent wait for the last command. This will allow running simple commands such as “ls -al | grep filename”. The key idea is; passing output of one process as input to another. Note that, you can have multiple chains of pipes as your command line argument.

</div>
</div>
<div class="layoutArea">
<div class="column">
CSE4100-SP-P1 &gt; ls -al | grep file .

</div>
</div>
<div class="layoutArea">
<div class="column">
Parent process

</div>
</div>
<div class="layoutArea">
<div class="column">
Shell program

</div>
<div class="column">
fork()

fork()

</div>
<div class="column">
Child process 1

Child process

</div>
<div class="column">
Execute ls command Output ()

Execute grep command

</div>
</div>
<div class="layoutArea">
<div class="column">
Hints:

The Pipe is a command in Linux that lets you use two or more commands such that output of one command serves as input to the next. In short, the output of each process acts as input to the next one like a pipeline. The simplest way to solve multiple pipes in your command line arguments; is to use a recursive function that is called until there are no more piped commands during parsing.

Note: Please consult the man pages for the dup(), dup2() system calls. Evaluation:

<ul>
<li>– &nbsp;Following shell commands with piping can be evaluated, e.g.,</li>
<li>– &nbsp;ls -al | grep filename</li>
<li>– &nbsp;cat filename | less</li>
<li>– &nbsp;cat filename | grep -v “abc” | sort – r</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Project Phase III: Run Processes in Background in Your Shell Points:

Task Specifications:

It is the last phase of your MyShell project, where you enable your shell to run processes in background. Linux shells support the notion of job control, which allows users to move jobs back and forth between background and foreground, and to change the process state (running, stopped, or terminated) of the processes in a job.

Your shell must start a command in the background if an ‘&amp;’ is given in the command line arguments. Besides, your shell must also provide various built-in commands that support job control.

For example:

• jobs: List the running and stopped background jobs.

• bg&lt;job&gt;: Change a stopped background job to a running background job.

• fg&lt;job&gt;: Change a stopped or running background job to a running in the foreground. • kill&lt;job&gt;: Terminate a job.

Note that, one should not be required to separate the ‘&amp;’ from the command by a space. For example, the commands ‘sort foo.txt &amp;’, and ‘sort foo.txt&amp;’ and ‘sort foo.txt &amp;’ (blanks after the ampersand) are all valid.

</div>
</div>
<div class="layoutArea">
<div class="column">
fork()

fork()

</div>
<div class="column">
Child process 1

Child process

</div>
<div class="column">
Execute ls in background

Execute cat

</div>
</div>
<div class="layoutArea">
<div class="column">
CSE4100-SP-P1 &gt; ls -al &amp; . CSE4100-SP-P1 &gt; cat file ..

Shell program

Hints:

When pressing ctrl-c causes a SIGINT signal to be delivered to each process in the foreground job. The default action for SIGINT is to terminate the process. Similarly, pressing ctrl-z causes a SIGTSTP signal to be delivered to each process in the foreground job. The default action for SIGTSTP is to place a process in the stopped state, where it remains until it is awakened by the receipt of a SIGCONT signal.

Note: Please consult the registering signal handlers in chapter 8 to complete this project phase. SIGINT, SIGSTP and SIGCONT are must read items.

Evaluation:

<ul>
<li>– &nbsp;Any command from project phase II can be given with ‘&amp;’ at the end of commandline</li>
<li>– &nbsp;ls -al | grep filename &amp; – catsample|grep-va&amp;</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Parent process

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
return signal when done

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Project Submission: How to Submit Your Shell Project

Submission Due: ~4/14(Thu) 23:39pm (late : ~4/17(Sun) 23:59pm -10% deduction per day)

Hand-In Specifications:

The submission should contain only source code file(s), include file(s), a makefile (all lower case please), and the readme file. No executable program should be included. The person marking your project will be automatically rebuild your shell program from the provided source code. You also submit one document for 3 phases.

Note: Please make sure to compile your source code on CSPRO server, as the TA will build and compile your submitted project on that server. If the submitted code does not compile it cannot be scored!!!

Source Code Management:

As described above, the files in the submitted directory would be:

<ul>
<li>– &nbsp;makefile (mandatory)</li>
<li>– &nbsp;myshell.c (mandatory)</li>
<li>– &nbsp;myshell.h (mandatory)</li>
<li>– &nbsp;Readme (Optional but not a Mandatory requirement)
How to Submit:

After completing each of the project phase, you need to submit your compressed/zipped source files. Please make sure that your source files contain appropriate Makefile, so that it can be compiled, build and executed for testing purpose.

All students are requested to upload the compressed source files on eclass(cyber campus).

Please use the following mentioned format for the attachment.

Attachment File:
</li>
</ul>
<ul>
<li>– &nbsp;Phase1 folder(source code(myshell.c, myshell.h), Makefile, readme) (30 point)</li>
<li>– &nbsp;Phase2 folder(source code(myshell.c, myshell.h), Makefile, readme) (30 point)</li>
<li>– &nbsp;Phase3 folder(source code(myshell.c, myshell.h), Makefile, readme) (40 point)</li>
<li>– &nbsp;Document (about phase 1, 2, 3) (20 point)
Create a student ID folder, save the reports and folders in it, and compress the folder as follows in the location where the student ID folder is located.
</li>
</ul>
– tar –cvzf [HW1]20201234.tar.gz ./20201234

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Best Practices the system programmers must comply to: You Must DO:

<ol>
<li>You must read the entire Chapter 8 (Processes, Process Controls, and Signals) of the book to fully understand, learn and complete this project.</li>
<li>Read the complete project specifications before programming your shell project.</li>
<li>You may find it useful to check the Linux man pages on fork(), exec(), getenv(), access(),
waitpid(), opendir(), and other related features mentioned in those man pages.
</li>
<li>Source code commenting is a professional programmer’s practice and a must do in this
project as well.
</li>
<li>Make sure to include a Readme file in your project explaining the basics of each project
phase in your own way, so we can know your understanding about the each phase concepts.
</li>
</ol>
You Must NOT DO:

<ol>
<li>Do not hand-in any binary or object code files in your source code directory.</li>
<li>Do not include any hardcoded paths in your makefile.</li>
<li>Makefile should include all dependencies (libraries etc) required to build your program.</li>
<li>Do not copy or share your source code, it is strictly prohibited otherwise you will be
given penalty for such an action.
</li>
</ol>
Programmers Pro-Tips:

<ol>
<li>Add your details on the header of your source files. (project, name, copyrights etc)</li>
<li>Your source file should be well structured and written in multiple functions to allow
others to understand your source easily. (Please do not make us do mental workout)
</li>
<li>Each function needs to be relatively short (less than one screen at a good font size is a
good rule of thumb! by professional programmers.)
</li>
</ol>
</div>
</div>
</div>
</div>

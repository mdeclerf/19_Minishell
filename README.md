# 19_Minishell
The objective of this project is for you to create a simple shell

Done with the amazing goffauxs (github.com/goffauxs) and Julie Van Audenhaege

Minishell : 
<ul>
<li>Display a prompt when waiting for a new command.</li>
<li>Have a working history.</li>
<li>Search and launch the right executable (based on the PATH variable or using a relative or an absolute path).</li>
<li>Handle ’ (single quote) which should prevent the shell from interpreting the metacharacters in the quoted sequence.</li>
<li>Handle " (double quote) which should prevent the shell from interpreting the metacharacters in the quoted sequence except for $ (dollar sign).</li>
<li>Implement redirections:
◦ < should redirect input.
◦ > should redirect output.
◦ << should be given a delimiter, then read the input until a line containing the delimiter is seen. However, it doesn’t have to update the history!
◦ >> should redirect output in append mode. </li>
<li>Implement pipes (| character). The output of each command in the pipeline is connected to the input of the next command via a pipe.</li>
<li>Handle environment variables ($ followed by a sequence of characters) which should expand to their values.</li>
<li>Handle $? which should expand to the exit status of the most recently executed foreground pipeline.</li>
<li>Handle ctrl-C, ctrl-D and ctrl-\ which should behave like in bash.</li>
<li>In interactive mode:
◦ ctrl-C displays a new prompt on a new line.
◦ ctrl-D exits the shell.
◦ ctrl-\ does nothing.</li>
<li>Your shell must implement the following builtins:
◦ echo with option -n
◦ cd with only a relative or absolute path
◦ pwd with no options
◦ export with no options
◦ unset with no options
◦ env with no options or arguments
◦ exit with no options</li>
</ul>

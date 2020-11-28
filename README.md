# SVN-Enumeration

<h2>TOP 10 SVN Commands</h2>

<h4>Link : https://www.thegeekstuff.com/2011/04/svn-command-examples/#:~:text=SVN%20Checkout%20%E2%80%93%20Create%20working%20copy,%2C%20delete%2C%20or%20add%20contents.</h3>


<h3>SVN Checkout – Create working copy</h3>

<h4>Desc : SVN checkout creates the working copy, from where you can do edit, delete, or add contents. You can checkout a file, directory, trunk or whole project. To checkout you should know URL of the components you want to checkout.</h4>

<h5>Command : svn co URL OUTPATH</h5>

<h3>SVN List – Lists directory entries</h3>

<h4>Desc : svn list is useful when you want to view the content of the SVN repository, without downloading a working copy.</h4>

<h4>Command : svn list svn://url</h4>

<h5>Variation 1 (XML Output) : svn list --xml svn://url</bh5>
<h5><b>Variation 2 (Verbose) : svn list -v svn://url</h5>
<h5><b>Variation 3 (Check Revisions) : svn list -r `revisionnumber` svn://url</h5>
<h5><b>Example (Revision 2 ) : svn list -r 2 svn://url</h5>


<h3>Note : Sometimes deleted files can be recovered from revisions that is not available in the current repo. (IMPORTANT CHECK)<h3>


# roam2github-actions
props to Erik Newhard for streamlining the automated backup process for Roam Research graphs ([everruler12/roam2github](https://github.com/everruler12/roam2github))

setup instructions if you'd like to automate the backup of your own graphs: https://www.notion.so/Roam2Github-Update-Instructions-c594a2931b694010814001c8a20fa960

after over a year of failed backups, I had to give this workflow 20 min (2x default) for it to finish properly.

I also reduced the frequency to daily and pleased I'm able to view text differences over time.

the workflow is being forced to run under node 16 as the use of node 12 is depreciated.

my graphs are over 50MB so checking in EDN/JSON into [Git LFS](https://www.atlassian.com/git/tutorials/git-lfs#what-is-git-lfs) is desirable long-term (and probably only need to be done once a week)

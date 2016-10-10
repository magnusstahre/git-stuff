#git stuff

##git crawl

A shell script that extends the git api allowing one to 'crawl' through their commits.

###Setup

Copy git-crawl to a directory that is accessible by PATH. Make sure the script can be executed by your user (ie - `chmod u+x git-crawl`).

###Usage

1. Checkout a commit that you want to crawl from
2. `git crawl <destination commit>`
3. repeat 2 until you reach your desired commit

###Tip for Crawling Commits Sequentially ('git crawl next', eg)

1. `git checkout master~10` to rewind ten commits on master
2. `git crawl master` moves one step closer

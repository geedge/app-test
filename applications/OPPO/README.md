git branch [--color[=<when>] | --no-color] [--show-current]
	[-v [--abbrev=<n> | --no-abbrev]]
	[--column[=<options>] | --no-column] [--sort=<key>]
	[--merged [<commit>]] [--no-merged [<commit>]]
	[--contains [<commit>]] [--no-contains [<commit>]]
	[--points-at <object>] [--format=<format>]
	[(-r | --remotes) | (-a | --all)]
	[--list] [<pattern>…​]

$ git clone git://git.kernel.org/pub/scm/.../linux-2.6 my2.6
$ cd my2.6
$ git branch my2.6.14 v2.6.14 <1>.
$ git switch my2.6.14

git branch [--track[=(direct|inherit)] | --no-track] [-f]
	[--recurse-submodules] <分支名> [<起始点>]
git branch (--set-upstream-to=<上游> | -u <上游>) [<分支名>]
git branch --unset-upstream [<分支名>]
git branch (-m | -M) [<旧分支>] <新分支>
git branch (-c | -C) [<旧分支>] <新分支>
git branch (-d | -D) [-r] <分支名>…​
git branch --edit-description [<分支名>]
git-check-ref-format[1], git-fetch[1], git-remote[1], ‘`了解历史：什么是分支？’ 在 Git User’s Manual。
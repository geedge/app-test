git branch [--color[=<when>] | --no-color] [--show-current]
	[-v [--abbrev=<n> | --no-abbrev]]
	[--column[=<options>] | --no-column] [--sort=<key>]
	[--merged [<commit>]] [--no-merged [<commit>]]
	[--contains [<commit>]] [--no-contains [<commit>]]
	[--points-at <object>] [--format=<format>]
	[(-r | --remotes) | (-a | --all)]
	[--list] [<pattern>…​]
git branch [--track[=(direct|inherit)] | --no-track] [-f]
	[--recurse-submodules] <分支名> [<起始点>]
git branch (--set-upstream-to=<上游> | -u <上游>) [<分支名>]
git branch --unset-upstream [<分支名>]
git branch (-m | -M) [<旧分支>] <新分支>
git branch (-c | -C) [<旧分支>] <新分支>
git branch (-d | -D) [-r] <分支名>…​
git branch --edit-description [<分支名>]
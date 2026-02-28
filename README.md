```
 █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗
██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝
██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
███████╗██╗  ██╗███████╗██╗     ██╗
██╔════╝██║  ██║██╔════╝██║     ██║
███████╗███████║█████╗  ██║     ██║
╚════██║██╔══██║██╔══╝  ██║     ██║
███████║██║  ██║███████╗███████╗███████╗
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝
```

# Awesome Shell [![Awesome][awesome-badge]][awesome-link]

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php. This awesome collection is also available on 🌎 [Unix-Shell.ZEEF.com](unix-shell.zeef.com/caleb.xu).
- [Shells](#shells)
- [Command-Line Productivity](#command-line-productivity)
  - [Directory Navigation](#directory-navigation)
- [Customization](#customization)
- [For Developers](#for-developers)
- [System Utilities](#system-utilities)
- [Downloading and Serving](#downloading-and-serving)
- [Multimedia and File Formats](#multimedia-and-file-formats)
- [Applications](#applications)
- [Games](#games)
- [Shell Package Management](#shell-package-management)
- [Shell Script Development](#shell-script-development)
- [Guides](#guides)
- [**Awesome Zsh**][awesome-zsh]&nbsp; [![Awesome][awesome-badge]][awesome-zsh]
- [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
- [**Awesome Bash**][awesome-bash] [![Awesome][awesome-badge]][awesome-bash]
- [Other Awesome Lists](#other-awesome-lists)

## Shells

*Choose your base shell.*

* 🌎 [bash](www.gnu.org/software/bash/) - GNU Project's shell (Bourne Again SHell)
* 🌎 [elvish](elv.sh/) - Friendly, expressive shell features like anonymous functions and data structures
* 🌎 [es](wryun.github.io/es-shell/) - The extensible shell, based on Plan 9's <b><code>&nbsp;&nbsp;&nbsp;315⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [rc](https://github.com/rakitzis/rc)) shell
* 🌎 [fish](fishshell.com) - Smart and user-friendly command line shell
* <b><code>&nbsp;&nbsp;1634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [ion](https://github.com/redox-os/ion)) - A modern system shell that features a simple, yet powerful, syntax. It is written entirely in Rust.
* <b><code>&nbsp;&nbsp;&nbsp;599⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [ksh93](https://github.com/att/ast)) - Korn Shell
* <b><code>&nbsp;&nbsp;&nbsp;233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [mksh](https://github.com/MirBSD/mksh)) - MirBSD Korn Shell
* <b><code>&nbsp;&nbsp;1851⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [murex](https://github.com/lmorg/murex)) - A smarter shell and scripting environment with advanced features designed for usability, safety and productivity (eg smarter DevOps tooling)
* <b><code>&nbsp;&nbsp;1516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [ngs](https://github.com/ngs-lang/ngs)) - Fully featured scripting language created specifically for Ops. REPL is being developed.
* <b><code>&nbsp;38553⭐</code></b> <b><code>&nbsp;&nbsp;2057🍴</code></b> [nushell](https://github.com/nushell/nushell)) - A modern shell written in Rust
* <b><code>&nbsp;&nbsp;&nbsp;423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [oksh](https://github.com/ibara/oksh)) - Portable OpenBSD ksh
* 🌎 [osh](www.oilshell.org) - Bash compatible, with new/modern Unix shell language called Oil
* 🌎 [pdksh](cvsweb.openbsd.org/cgi-bin/cvsweb/src/bin/ksh/) - Public domain Korn shell
* 🌎 [powershell](docs.microsoft.com/en-us/powershell/scripting/overview) a cross-platform task automation and configuration management framework, consisting of a command-line shell and scripting language
* <b><code>&nbsp;&nbsp;&nbsp;170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [shell++](https://github.com/alexst07/shell-plus-plus)) - Friendly and modern functional and object oriented shell script language
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [shenv](https://github.com/shenv/shenv)) - Simple shell version management
* 🌎 [tcsh](www.tcsh.org/) - C shell with file name completion and command line editing
* 🌎 [xonsh](xon.sh) - Python-ish, BASHwards-looking shell language and command prompt
* <b><code>&nbsp;&nbsp;&nbsp;511⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [yash](https://github.com/magicant/yash)) - A POSIX-compliant command line shell with built-in support for completion and prediction based on command history
* 🌎 [zsh](www.zsh.org) - Powerful shell with scripting language

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* <b><code>&nbsp;&nbsp;&nbsp;290⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [AdvancedNewFile](https://github.com/tanrax/terminal-AdvancedNewFile)) - Fast creation of files and directories in a recursive way. Inspired by the Vim plugin.
* <b><code>&nbsp;27224⭐</code></b> <b><code>&nbsp;&nbsp;1434🍴</code></b> [ag](https://github.com/ggreer/the_silver_searcher)) - Super fast string search through a directory hierarchy
* <b><code>&nbsp;&nbsp;&nbsp;615⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [aliases](https://github.com/sebglazebrook/aliases)) - Contextual, dynamic, organized aliases for bash
* <b><code>&nbsp;&nbsp;1278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [arttime](https://github.com/reportaman/arttime)) - Beauty of text art meets functionality of clock, timer, pomodoro++ time manager
* <b><code>&nbsp;&nbsp;6009⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;270🍴</code></b> [autoenv](https://github.com/hyperupcall/autoenv)) - Directory-based environments.
* <b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [await](https://github.com/slavaGanzin/await)) - single binary that run list of commands in parallel and waits for their termination
* <b><code>&nbsp;&nbsp;&nbsp;815⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [bartib](https://github.com/nikolassv/bartib)) - A simple timetracker for the command line. It saves a log of all tracked activities as a plaintext file and allows you to create flexible reports.
* <b><code>&nbsp;&nbsp;1297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [bashhub](https://github.com/rcaloras/bashhub-client)) - :cloud: Bash history in the cloud. Indexed and searchable.
* <b><code>&nbsp;&nbsp;1757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [boilr](https://github.com/tmrts/boilr)) - A blazingly fast CLI tool for creating projects from boilerplate templates.
* <b><code>&nbsp;&nbsp;1318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [boom](https://github.com/holman/boom)) - Store links and snippets in the command line
* <b><code>&nbsp;&nbsp;1611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [borg](https://github.com/ok-borg/borg)) - A terminal based search engine for bash commands
* <b><code>&nbsp;12443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [broot](https://github.com/Canop/broot)) - A better way to navigate directories
* <b><code>&nbsp;18569⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;460🍴</code></b> [browsh](https://github.com/browsh-org/browsh)) - The modern text-based browser
* <b><code>&nbsp;&nbsp;7081⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [Buku](https://github.com/jarun/Buku)) - Powerful command-line bookmark manager
* 🌎 [byobu](www.byobu.org) - Text-based window manager and terminal multiplexer
* <b><code>&nbsp;&nbsp;&nbsp;545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [cod](https://github.com/dim-an/cod)) — A completion daemon for shell that learns when you invoke `--help` commands
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [CloudClip](https://github.com/skywind3000/CloudClip)) - Your own clipboard in the cloud, copy and paste text with gist between different systems
* <b><code>&nbsp;&nbsp;3243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;156🍴</code></b> [ddgr](https://github.com/jarun/ddgr)) - DuckDuckGo from the terminal
* <b><code>&nbsp;&nbsp;2571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [desk](https://github.com/jamesob/desk)) - A lightweight workspace manager for the shell
* <b><code>&nbsp;14717⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;758🍴</code></b> [direnv](https://github.com/direnv/direnv)) - An environment switcher for the shell, compare with autoenv
* <b><code>&nbsp;&nbsp;3010⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [dnote](https://github.com/dnote/dnote)) - A simple command line notebook with multi-device sync and web interface
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [eureka](https://github.com/simeg/eureka/)) - :bulb: CLI tool to input and store your ideas without leaving the terminal
* <b><code>&nbsp;&nbsp;5921⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [fasd](https://github.com/clvv/fasd)) - Command-line productivity booster, offers quick access to files and directories
* <b><code>&nbsp;41839⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;984🍴</code></b> [fd](https://github.com/sharkdp/fd)) - A simple, fast and user-friendly alternative to find.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [foxy](https://github.com/s-p-k/foxy)) - Plain text bookmarks for Firefox and surf browsers.
* <b><code>&nbsp;&nbsp;4402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90🍴</code></b> [fselect](https://github.com/jhspetersson/fselect)) - Find files with SQL-like queries.
* <b><code>&nbsp;&nbsp;&nbsp;669⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [funky](https://github.com/bbugyi200/funky)) - Extends functionality of shell functions making them more powerful and flexible.
* <b><code>&nbsp;&nbsp;&nbsp;563⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [fz](https://github.com/changyuheng/fz)) - Seamless fuzzy tab completion for z
* <b><code>&nbsp;78207⭐</code></b> <b><code>&nbsp;&nbsp;2698🍴</code></b> [fzf](https://github.com/junegunn/fzf)) - A command-line fuzzy finder
* <b><code>&nbsp;&nbsp;&nbsp;757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [gitmux](https://github.com/arl/gitmux)) - Show Git status in Tmux status bar
* <b><code>&nbsp;&nbsp;6188⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;534🍴</code></b> [googler](https://github.com/jarun/googler)) - Google Search, Google Site Search, Google News from the terminal
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [googlr](https://github.com/Astranno/googlr)) - Command line tool that lets you search Google from your terminal.
* <b><code>&nbsp;&nbsp;&nbsp;802⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [has](https://github.com/kdabir/has)) - `has` helps you check presence of various command line tools and their versions on path
* <b><code>&nbsp;&nbsp;5782⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [how2](https://github.com/santinic/how2)) - `how2` finds the simplest way to do something in a unix shell. It's like `man`, but you can query it in natural language.
* <b><code>&nbsp;16772⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;535🍴</code></b> [navi](https://github.com/denisidoro/navi)) - An interactive cheatsheet tool for the command-line
* <b><code>&nbsp;&nbsp;&nbsp;490⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [hhighlighter](https://github.com/paoloantinori/hhighlighter)) - Colorize words in a command output
* <b><code>&nbsp;&nbsp;1303⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [hr](https://github.com/LuRsT/hr)) - `<hr />` for your terminal
* <b><code>&nbsp;&nbsp;&nbsp;378⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [hss](https://github.com/six-ddc/hss)) - An interactive parallel ssh client featuring autocomplete and asynchronous execution
* <b><code>&nbsp;&nbsp;4464⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [hstr](https://github.com/dvorka/hstr)) - Bash History Suggest Box
* <b><code>&nbsp;&nbsp;1817⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [k](https://github.com/supercrabtree/k)) - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [k alias](https://github.com/lingtalfi/k)) - get kool aliases (and more) working with a simple one-liner
* <b><code>&nbsp;&nbsp;9091⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;360🍴</code></b> [lf](https://github.com/gokcehan/lf)) - Terminal file manager written in Go, inspired by ranger
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [lf.sh](https://github.com/suewonjp/lf.sh)) - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc)
* <b><code>&nbsp;&nbsp;&nbsp;244⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [lowcharts](https://github.com/juan-leon/lowcharts)) - Draw low-resolution graphs in terminal
* 🌎 [Lmod](lmod.readthedocs.io/en/latest/) - Lua-based Environment Modules that enhances Tcl-based modules while being backward compatible (compare to modules)
* <b><code>&nbsp;&nbsp;&nbsp;690⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [loop](https://github.com/Miserlou/Loop)) - Write and control complex loops with as one-liners
* <b><code>&nbsp;&nbsp;2090⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [marker](https://github.com/pindexis/marker)) - Bookmark your shell commands
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [mackup](https://github.com/lra/mackup/)) - Keep your application settings in sync (OS X/Linux)
* <b><code>&nbsp;&nbsp;7611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;192🍴</code></b> [mcfly](https://github.com/cantino/mcfly)) - Fly through your shell history. Great Scot!
* [modules](http://modules.sourceforge.net/) - Classical Tcl-based Environment Modules managing the shell environment (compare to Lmod, direnv, and autoenv)
* <b><code>&nbsp;21324⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;796🍴</code></b> [nnn](https://github.com/jarun/nnn)) - File browser and disk usage analyzer with excellent desktop integration
* <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [ok-sh](https://github.com/secretGeek/ok-bash)) - Do you work on many different projects? And in each project, are there commands you use that are specific to that project? You need a .ok file.
* 🌎 [parallel](www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
* 🌎 [pass](www.passwordstore.org/) - Manage passwords from the command line with GPG encryption and optional git integration.
* <b><code>&nbsp;&nbsp;5230⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [pathpicker](https://github.com/facebook/PathPicker)) - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command.
* <b><code>&nbsp;&nbsp;&nbsp;405⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [pdd](https://github.com/jarun/pdd)) - Tiny date, time diff calculator with timers
* <b><code>&nbsp;&nbsp;3334⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [percol](https://github.com/mooz/percol)) - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [q](https://github.com/cal2195/q)) - Vim like macro registers for your Bash and Zsh Shell
* <b><code>&nbsp;&nbsp;&nbsp;582⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [qfc](https://github.com/pindexis/qfc)) - File-completion widget for Bash and Zsh
* <b><code>&nbsp;&nbsp;1050⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [resh](https://github.com/curusarn/resh)) - Contextual shell history for Zsh and Bash
* <b><code>&nbsp;60367⭐</code></b> <b><code>&nbsp;&nbsp;2402🍴</code></b> [rg](https://github.com/BurntSushi/ripgrep)) - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep
* 🌎 [screen](www.gnu.org/software/screen/) - GNU terminal multiplexer
* <b><code>&nbsp;&nbsp;&nbsp;114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [shell-history](https://github.com/pawamoy/shell-history)) - Visualize your shell usage with Highcharts
* <b><code>&nbsp;&nbsp;&nbsp;451⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [SHML](https://github.com/odb/shml)) - Style framework for the terminal (Shell Markup Language)
* <b><code>&nbsp;&nbsp;&nbsp;315⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [slugify](https://github.com/benlinton/slugify)) - Command that converts filenames and directories to a web friendly format
* <b><code>&nbsp;&nbsp;&nbsp;302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [sman](https://github.com/tokozedg/sman)) - :bug: A command-line snippet manager
* <b><code>&nbsp;&nbsp;6057⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [spark](https://github.com/holman/spark)) - ▁▂▃▅▂▇ in your shell
* <b><code>&nbsp;&nbsp;&nbsp;374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [spark.fish](https://github.com/jorgebucaran/spark.fish)) - ▁▂▃▅ Sparkline Generator
* <b><code>&nbsp;&nbsp;&nbsp;270⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [sheet](https://github.com/oscardelben/sheet)) -  Text snippets for the command line
* <b><code>&nbsp;&nbsp;&nbsp;953⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [spot](https://github.com/rauchg/spot)) - Tiny file search utility
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [snips](https://github.com/srijanshetty/snips)) - Command line tool to manage snippets of code.
* <b><code>&nbsp;&nbsp;&nbsp;650⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;148🍴</code></b> [sqlline](https://github.com/julianhyde/sqlline)) - Shell for issuing SQL to relational databases via JDBC (multiline, completion, highlighting, dialect support)
* <b><code>&nbsp;&nbsp;1202⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [sshfs](https://github.com/osxfuse/sshfs)) - A tool for mounting remote file systems over SSH
* <b><code>&nbsp;&nbsp;&nbsp;162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [sudocabulary](https://github.com/badarsh2/Sudocabulary)) - Learn English Vocabulary from your terminal
* 🌎 [surfraw](gitlab.com/surfraw/Surfraw) - browse specific site and search the web from your terminal without browser.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [task-manager](https://github.com/lingtalfi/task-manager)) - Execute all your scripts with just two or three keystrokes.
* <b><code>&nbsp;&nbsp;&nbsp;211⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [td-cli](https://github.com/darrikonn/td-cli)) - A todo command line manager to organize and manage your todos across multiple projects.
* <b><code>&nbsp;&nbsp;1791⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [tere](https://github.com/mgunyho/tere)) - A faster alternative to cd + ls
* <b><code>&nbsp;95564⭐</code></b> <b><code>&nbsp;&nbsp;3846🍴</code></b> [thefuck](https://github.com/nvbn/thefuck)) - Fix common shell mistakes by using an easy to remember command
* <b><code>&nbsp;&nbsp;&nbsp;738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [tldr](https://github.com/raylee/tldr-sh-client)) - A fully-functional bash client for tldr, simplified and community-driven man pages
* 🌎 [tmux](tmux.github.io/) - Amazing terminal multiplexer
* <b><code>&nbsp;&nbsp;&nbsp;200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [undollar](https://github.com/xtyrrell/undollar)) - undollar bites the dollar sign off the tip of the command you just pasted into your terminal
* <b><code>&nbsp;&nbsp;9832⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;383🍴</code></b> [usql](https://github.com/xo/usql)) - Universal command-line interface for SQL databases.
* <b><code>&nbsp;&nbsp;&nbsp;461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [v](https://github.com/rupa/v)) - z for vim.
* <b><code>&nbsp;&nbsp;3667⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;144🍴</code></b> [wemux](https://github.com/zolrath/wemux)) - Multi-User Tmux Made Easy
* <b><code>&nbsp;&nbsp;3761⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [xiki](https://github.com/trogdoro/xiki)) - Makes the shell console more friendly and powerful
* <b><code>&nbsp;&nbsp;4705⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [xplr](https://github.com/sayanarijit/xplr)) -  A hackable, minimal, fast TUI file explorer
* <b><code>&nbsp;10757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;332🍴</code></b> [xsv](https://github.com/BurntSushi/xsv)) - a fast CSV command line toolkit written in Rust
* <b><code>&nbsp;&nbsp;5924⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [xxh](https://github.com/xxh/xxh)) - Bring your favorite shell wherever you go through the SSH.

### Directory Navigation

* <b><code>&nbsp;&nbsp;&nbsp;120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [aliasme](https://github.com/Jintin/aliasme)) - alias helper to change directory quickly
* <b><code>&nbsp;16836⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;711🍴</code></b> [autojump](https://github.com/wting/autojump)) - A cd command that learns - easily navigate directories from the command line
* <b><code>&nbsp;&nbsp;1957⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;291🍴</code></b> [bashmarks](https://github.com/huyng/bashmarks)) - Directory bookmarks for the shell
* <b><code>&nbsp;&nbsp;&nbsp;929⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [bd](https://github.com/vigneshwaranr/bd)) - Quickly go back to a parent directory
* <b><code>&nbsp;&nbsp;&nbsp;370⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [commacd](https://github.com/shyiko/commacd)) - A faster way to move around in Bash
* <b><code>&nbsp;&nbsp;2682⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [enhancd](https://github.com/b4b4r07/enhancd)) - :rocket: A next-generation cd command with an interactive filter
* <b><code>&nbsp;&nbsp;&nbsp;902⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [goto](https://github.com/iridakos/goto)) - A shell utility for navigation to aliased directories supporting auto-completion
* <b><code>&nbsp;&nbsp;1912⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [jump](https://github.com/gsamokovarov/jump)) - Jump helps you navigate your file system faster by learning your habits.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [lazy-cd](https://github.com/pedramamini/lazy-cd)) - Simple bash commands for bookmarked navigation of the file system, complete with bash-completion.
* <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [up](https://github.com/shannonmoeller/up)) - Ascend directories by name or count; for bash, zsh, and fish.
* <b><code>&nbsp;16935⭐</code></b> <b><code>&nbsp;&nbsp;1182🍴</code></b> [z](https://github.com/rupa/z)) - z is the new j, yo
* <b><code>&nbsp;&nbsp;3121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [z.lua](https://github.com/skywind3000/z.lua)) - A new cd command that helps you navigate faster by learning your habits
* <b><code>&nbsp;33844⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;738🍴</code></b> [zoxide](https://github.com/ajeetdsouza/zoxide)) - A faster way to navigate your filesystem, written in Rust
* <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [zpyi](https://github.com/sakshamsharma/zpyi)) - Python in Zsh - Easy python scripting in shell

## Customization

*Custom prompts, color themes, etc.*

* <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [aphrodite-terminal-theme](https://github.com/win0err/aphrodite-terminal-theme)) — Minimalistic Aphrodite theme (prompt) for sexy terminals that works in bash, fish and zsh
* <b><code>&nbsp;&nbsp;&nbsp;454⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [base16-builder](https://github.com/base16-builder/base16-builder)) - Base16-Builder
* <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors)) - Powerful prompt with screen, tmux, git support and many more
* <b><code>&nbsp;&nbsp;6901⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;990🍴</code></b> [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt)) - An informative and fancy Bash prompt for Git users
* <b><code>&nbsp;&nbsp;&nbsp;907⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;168🍴</code></b> [bash-powerline](https://github.com/riobard/bash-powerline)) - Powerline-style Bash prompt in pure Bash script
* <b><code>&nbsp;&nbsp;1559⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [bashstrap](https://github.com/barryclark/bashstrap)) - A quick way to spruce up OSX terminal
* <b><code>&nbsp;&nbsp;2852⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;380🍴</code></b> [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train.zsh)) - :bullettrain_side: An oh-my-zsh shell theme based on the Powerline Vim plugin
* <b><code>&nbsp;&nbsp;1584⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [emojify](https://github.com/mrowa44/emojify)) Emoji on the command line :scream:
* 🌎 [flatui-terminal-theme](dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
* <b><code>&nbsp;&nbsp;&nbsp;989⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [geometry](https://github.com/geometry-zsh/geometry)) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* <b><code>&nbsp;&nbsp;&nbsp;329⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97🍴</code></b> [git-prompt](https://github.com/lvv/git-prompt)) - Bash prompt with Git, SVN and HG modules
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [gittify](https://github.com/momeni/gittify)) - A colorful Bash prompt + customized Git aliases
* <b><code>&nbsp;10114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;626🍴</code></b> [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh)) - Color Scheme for Gnome Terminal
* <b><code>&nbsp;&nbsp;4633⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;415🍴</code></b> [liquidprompt](https://github.com/nojhan/liquidprompt)) - A full-featured & carefully designed adaptive prompt for Bash & Zsh
* <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize)) -  Colorization for mysql comand-line client
* <b><code>&nbsp;&nbsp;3696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;282🍴</code></b> [oh-my-git](https://github.com/arialdomartini/oh-my-git)) - An opinionated git prompt for bash and zsh
* 🌎 [oh-my-posh](ohmyposh.dev) - Prompt theme engine for any shell and platform written in go.
* <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [polyglot](https://github.com/agkozak/polyglot)) - An informative Git prompt that works in bash, zsh, ksh, mksh, pdksh, oksh, dash, yash, busybox sh, and osh
* <b><code>&nbsp;53123⭐</code></b> <b><code>&nbsp;&nbsp;2399🍴</code></b> [powerlevel10k](https://github.com/romkatv/powerlevel10k)) - Super flexible awesome powerline ZSH theme
* <b><code>&nbsp;&nbsp;1154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;152🍴</code></b> [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt)) - Bash prompt with colors, Git statuses, and Git branches
* 🌎 [starship](starship.rs/) - Fast, customisable, cross-shell prompt written in rust
* <b><code>&nbsp;&nbsp;1128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;239🍴</code></b> [synth-shell](https://github.com/andresgongora/synth-shell)) - Greeter with a customizable status report and a fancy bash prompt

## For Developers

*Command-line development, version control, and deployment.*

* 🌎 [1Password SSH Agent](developer.1password.com/docs/ssh/) - Authenticate Git and SSH workflows with biometric unlock using 1Password
* 🌎 [ack](beyondgrep.com/) - A grep-like search tool optimized for source code.
* <b><code>&nbsp;&nbsp;&nbsp;713⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [add-gitignore](https://github.com/TejasQ/add-gitignore)) - Interactive CLI that generates a .gitignore for your project based on your needs.
* <b><code>&nbsp;&nbsp;&nbsp;685⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [bcal](https://github.com/jarun/bcal)) - Byte CALculator for storage conversions and calculations
* <b><code>&nbsp;&nbsp;&nbsp;710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [bitwise](https://github.com/mellowcandle/bitwise)) - Terminal based interactive bit manipulator in curses.
* <b><code>&nbsp;12623⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;755🍴</code></b> [bocker](https://github.com/p8952/bocker)) - Docker implemented in 100 lines of bash
* <b><code>&nbsp;22588⭐</code></b> <b><code>&nbsp;&nbsp;1101🍴</code></b> [cloc](https://github.com/AlDanial/cloc)) - Count Lines of Code
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [doclt](https://github.com/omgimanerd/doclt)) - A command line interface to Digital Ocean
* <b><code>&nbsp;31880⭐</code></b> <b><code>&nbsp;&nbsp;2021🍴</code></b> [dokku](https://github.com/dokku/dokku)) - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen.
* <b><code>&nbsp;&nbsp;4902⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;155🍴</code></b> [forgit](https://github.com/wfxr/forgit)) - Utility tool for `git` taking advantage of fuzzy finder fzf.
* <b><code>&nbsp;&nbsp;1134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [git-extra-commands](https://github.com/unixorn/git-extra-commands)) - Many Git extra utilities. Churn, cut-branch, improved-merge and many more.
* <b><code>&nbsp;17989⭐</code></b> <b><code>&nbsp;&nbsp;1221🍴</code></b> [git-extras](https://github.com/tj/git-extras)) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more
* <b><code>&nbsp;&nbsp;3423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;261🍴</code></b> [git-open](https://github.com/paulirish/git-open)) - Type `git open` to open the GitHub page or website for a repository in your browser
* <b><code>&nbsp;&nbsp;6945⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;281🍴</code></b> [git-quick-stats](https://github.com/arzzen/git-quick-stats)) - Git quick statistics is a simple and efficient way to access various statistics in git repository.
* <b><code>&nbsp;&nbsp;&nbsp;393⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [git-semver](https://github.com/markchalloner/git-semver)) - Git plugin for easing semantic versioning and changelog validation
* <b><code>&nbsp;&nbsp;&nbsp;745⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [git-sh](https://github.com/rtomayko/git-sh)) - A customized Bash environment suitable for Git work
* <b><code>&nbsp;&nbsp;1833⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [gita](https://github.com/nosarthur/gita)) - A command-line tool to manage multiple git repos.
* <b><code>&nbsp;22946⭐</code></b> <b><code>&nbsp;&nbsp;2212🍴</code></b> [hub](https://github.com/github/hub)) - hub helps you win at git.
* <b><code>&nbsp;31702⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;683🍴</code></b> [just](https://github.com/casey/just)) - Task runner for saving and running project-specific commands.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [licins](https://github.com/dogoncouch/licins)) - Insert commented software licenses into source code.
* <b><code>&nbsp;&nbsp;&nbsp;381⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [mkdkr](https://github.com/rosineygp/mkdkr)) - Makefile + Docker = CI Pipeline
* 🌎 [mr](myrepos.branchable.com) - Multiple Repository management tool
* <b><code>&nbsp;&nbsp;&nbsp;710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [nve](https://github.com/ehmicky/nve)) - Run any command on specific Node.js versions.
* <b><code>&nbsp;&nbsp;3991⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;280🍴</code></b> [overcommit](https://github.com/sds/overcommit)) - A fully configurable and extendable Git hook manager
* 🌎 [pre-commit](pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
* <b><code>&nbsp;&nbsp;4132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;383🍴</code></b> [rebound](https://github.com/shobrook/rebound)) - Instantly browse Stack Overflow results in your terminal when you get a compiler error
* <b><code>&nbsp;&nbsp;&nbsp;370⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [repren](https://github.com/jlevy/repren)) - Command-line search-and-replace and file-renaming swiss army knife
* <b><code>&nbsp;&nbsp;6183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [slap](https://github.com/slap-editor/slap)) - Sublime-like terminal-based text editor that runs on Node.js
* <b><code>&nbsp;&nbsp;&nbsp;568⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [shipit](https://github.com/sapegin/shipit)) - Minimalistic SSH deployment
* <b><code>&nbsp;&nbsp;&nbsp;156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [starring](https://github.com/ritz078/starring)) - Automatically star the npm-packages that you are using on GitHub.
* <b><code>&nbsp;&nbsp;&nbsp;609⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [tag](https://github.com/aykamko/tag)) - Instantly jump to your ag matches.
* 🌎 [trunk](www.npmjs.com/package/@trunkio/launcher) - Blazingly fast meta code checker and formatter
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [vmn](https://github.com/final-israel/vmn)) - git-based automatic versioning and state recovery solution agnostic to language or architecture
* <b><code>&nbsp;&nbsp;&nbsp;355⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [wipe-modules](https://github.com/bntzio/wipe-modules)) - A little agent that removes the node_modules folder of non-active projects

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

* 🌎 [atop](www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
* <b><code>&nbsp;57420⭐</code></b> <b><code>&nbsp;&nbsp;1463🍴</code></b> [bat](https://github.com/sharkdp/bat)) - A `cat` clone with wings
* <b><code>&nbsp;&nbsp;1350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [bmon](https://github.com/tgraf/bmon)) - Real-time network bandwidth monitor and rate estimator with human-friendly visual output
* <b><code>&nbsp;30606⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;927🍴</code></b> [btop](https://github.com/aristocratos/btop)) - Linux/OSX/FreeBSD resource monitor
* <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [catcli](https://github.com/deadc0de6/catcli)) -  The command line catalog tool for your offline data
* <b><code>&nbsp;&nbsp;3204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [ccat](https://github.com/owenthereal/ccat)) - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting.
* <b><code>&nbsp;24424⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;658🍴</code></b> [exa](https://github.com/ogham/exa)) - A modern version of `ls`.
* <b><code>&nbsp;&nbsp;8824⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;314🍴</code></b> [progress](https://github.com/Xfennec/progress)) - Linux tool to show progress for `cp`, `rm`, `dd`, and more...
* <b><code>&nbsp;&nbsp;1172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;263🍴</code></b> [stronghold](https://github.com/alichtman/stronghold)) - Easily configure MacOS security settings from the terminal.
* <b><code>&nbsp;31808⭐</code></b> <b><code>&nbsp;&nbsp;1689🍴</code></b> [glances](https://github.com/nicolargo/glances)) - Glances an Eye on your system
* <b><code>&nbsp;20261⭐</code></b> <b><code>&nbsp;&nbsp;1174🍴</code></b> [goaccess](https://github.com/allinurl/goaccess)) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems.
* <b><code>&nbsp;&nbsp;1923⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [hblock](https://github.com/hectorm/hblock)) - Hosts-file based adblocker
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [histstat](https://github.com/vesche/histstat)) - History for netstat
* <b><code>&nbsp;&nbsp;5976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;577🍴</code></b> [htop](https://github.com/hishamhm/htop)) - A ncurses based interactive process viewer which aims to be a better `top`
* 🌎 [lnav](lnav.org) - An advanced log file viewer for the small-scale
* <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [logdissect](https://github.com/dogoncouch/logdissect)) - CLI utility and Python API for analyzing log files and other data.
* <b><code>&nbsp;&nbsp;&nbsp;512⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [ls++](https://github.com/trapd00r/ls--)) - Colorized ls on steroids
* <b><code>&nbsp;15490⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;485🍴</code></b> [lsd](https://github.com/Peltoche/lsd)) - LSDeluxe, rewrite of GNU ls with lot of added features like colors, icons, tree-view and more formatting options.
* <b><code>&nbsp;&nbsp;&nbsp;533⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [lsp](https://github.com/dborzov/lsp)) - An improved `ls`, with file descriptions in plain language and intelligent file grouping
* <b><code>&nbsp;&nbsp;1862⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [maza](https://github.com/tanrax/maza-ad-blocking)) - Local ad blocker. Like Pi-hole but local and using your operating system.
* <b><code>&nbsp;&nbsp;3143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;364🍴</code></b> [mtr](https://github.com/traviscross/mtr)) - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
* 🌎 [ncdu](dev.yorhel.nl/ncdu) - NCurses Disk Usage
* <b><code>&nbsp;&nbsp;&nbsp;478⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [nmtui](https://github.com/NetworkManager/NetworkManager)) - Text User Interface for controlling NetworkManager
* <b><code>&nbsp;&nbsp;1272⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;139🍴</code></b> [powertop](https://github.com/fenrus75/powertop)) - Battery/Power usage and device stats monitoring command-line tool, with tune-up options.
* <b><code>&nbsp;&nbsp;1266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77🍴</code></b> [prettyping](https://github.com/denilsonsa/prettyping)) - Making the output of `ping` prettier, more colorful, more compact, and easier to read.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [procdog](https://github.com/jlevy/procdog)) - Lightweight command-line control of long-lived processes like servers
* <b><code>&nbsp;&nbsp;&nbsp;428⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [quick-secure](https://github.com/marshyski/quick-secure)) - Quickly secure and harden UNIX/Linux systems
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [rng](https://github.com/nickolasburr/rng)) - Copy range of lines from file or stdin to stdout.
* <b><code>&nbsp;&nbsp;2012⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [tiptop](https://github.com/nschloe/tiptop)) - Graphical command-line system monitor.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [wifi-wand](https://github.com/keithrbennett/wifiwand)) - a Ruby command line application for managing WiFi on MacOS (install by `gem install wifi-wand`)
* <b><code>&nbsp;&nbsp;1153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [xiringuito](https://github.com/ivanilves/xiringuito)) - SSH-based "VPN for poors"

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* <b><code>&nbsp;40139⭐</code></b> <b><code>&nbsp;&nbsp;3817🍴</code></b> [aria2](https://github.com/aria2/aria2)) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink
* <b><code>&nbsp;&nbsp;&nbsp;870⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [balls](https://github.com/jneen/balls)) - Bash on Balls
* <b><code>&nbsp;&nbsp;1548⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [bashttpd](https://github.com/avleen/bashttpd)) - A web server written in Bash
* <b><code>&nbsp;&nbsp;&nbsp;317⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [bashhub-server](https://github.com/nicksherron/bashhub-server)) - Private cloud shell history. Open source server for bashhub
* <b><code>&nbsp;&nbsp;1034⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [bitpocket](https://github.com/sickill/bitpocket)) - "DIY Dropbox" or "2-way directory (r)sync with proper deletion"
* <b><code>&nbsp;&nbsp;6623⭐</code></b> <b><code>&nbsp;&nbsp;1058🍴</code></b> [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader)) - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox
* <b><code>&nbsp;37615⭐</code></b> <b><code>&nbsp;&nbsp;3819🍴</code></b> [httpie](https://github.com/httpie/httpie)) - HTTPie is a command line HTTP client, a user-friendly cURL replacement
* <b><code>&nbsp;&nbsp;4204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [HTTPLab](https://github.com/gchaincl/httplab)) - The interactive web server, let you inspect HTTP requests and forge responses.
* <b><code>&nbsp;&nbsp;&nbsp;622⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [Kapow!](https://github.com/BBVA/kapow)) - If you can script it, you can HTTP it.
* <b><code>&nbsp;&nbsp;&nbsp;183⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [ngincat](https://github.com/jaburns/ngincat)) - Tiny Bash HTTP server using netcat
* <b><code>&nbsp;&nbsp;2653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [resty](https://github.com/micha/resty)) - Little command line REST client that you can use in pipelines
* <b><code>&nbsp;&nbsp;1475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [shell2http](https://github.com/msoap/shell2http)) - HTTP-server to execute shell commands. Designed for development, prototyping or remote control
* <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [tshare](https://github.com/trikko/tshare)) - File sharing from commandline.
* <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [vesper](https://github.com/chris-rock/vesper)) - 🍸Vesper is a HTTP framework for Bash/Unix Shell
* <b><code>&nbsp;&nbsp;7614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [xh](https://github.com/ducaale/xh)) - Friendly and fast tool for sending HTTP requests
* <b><code>148922⭐</code></b> <b><code>&nbsp;12069🍴</code></b> [yt-dlp](https://github.com/yt-dlp/yt-dlp)) - Command-line program to download videos from YouTube.com and other video sites

## Multimedia and File Formats

*Tools for handling video and audio files.*

* <b><code>&nbsp;&nbsp;&nbsp;114⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [adb-export](https://github.com/sromku/adb-export)) - Export Android content providers to CSV format
* <b><code>&nbsp;&nbsp;1070⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;588🍴</code></b> [Android-Kitchen](https://github.com/dsixda/Android-Kitchen)) - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux
* <b><code>&nbsp;14777⭐</code></b> <b><code>&nbsp;&nbsp;1987🍴</code></b> [Beets](https://github.com/beetbox/beets)) - Music library manager and MusicBrainz tagger
* <b><code>&nbsp;&nbsp;6052⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;508🍴</code></b> [cmus](https://github.com/cmus/cmus)) - Cross-platform cli audio player.
* <b><code>&nbsp;&nbsp;7865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [dasel](https://github.com/tomwright/dasel)) - Query and update data structures using selectors from the command line. Comparable to <b><code>&nbsp;33745⭐</code></b> <b><code>&nbsp;&nbsp;1703🍴</code></b> [jq](https://github.com/stedolan/jq)) / <b><code>&nbsp;&nbsp;2914⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [yq](https://github.com/kislyuk/yq)) but supports JSON, YAML, TOML and XML with zero runtime dependencies.
* <b><code>&nbsp;&nbsp;&nbsp;247⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [dzr](https://github.com/yne/dzr)) - Cross-platform Deezer.com audio player.
* <b><code>&nbsp;20302⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;471🍴</code></b> [fx](https://github.com/antonmedv/fx)) - Command-line JSON processing tool by anononymus JavaScript functions
* <b><code>&nbsp;&nbsp;&nbsp;562⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [gifgen](https://github.com/lukechilds/gifgen)) - Simple high quality GIF encoding
* <b><code>&nbsp;&nbsp;&nbsp;780⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;103🍴</code></b> [image-scraper](https://github.com/sananth12/ImageScraper)) - A cool command line image scraper with a lot of features.
* <b><code>&nbsp;&nbsp;1090⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [imgp](https://github.com/jarun/imgp)) - Blazing fast batch image resizer and rotator
* <b><code>&nbsp;&nbsp;8545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;224🍴</code></b> [jc](https://github.com/kellyjonbrazil/jc)) - Convert command output, file-types, and common strings to JSON or YAML for easier use in scripts.
* <b><code>&nbsp;&nbsp;4864⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;160🍴</code></b> [jo](https://github.com/jpmens/jo)) - A small utility to create JSON objects from command-line arguments.
* <b><code>&nbsp;33745⭐</code></b> <b><code>&nbsp;&nbsp;1703🍴</code></b> [jq](https://github.com/stedolan/jq)) - Sed for json data. You can use it to slice and filter and map and transform structured data
* <b><code>&nbsp;&nbsp;&nbsp;383⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [korkut](https://github.com/oguzhaninan/korkut)) - Quick and simple image processing at the command line.
* <b><code>&nbsp;&nbsp;&nbsp;467⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [library](https://github.com/chapmanjacobd/library)) - Create SQLITE databases for folders of music, video, images, or online media. Play and track media like Plex but a CLI-only interface with many sorting options.
* 🌎 [mpv](mpv.io/) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [nehm](https://github.com/bogem/nehm)) - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way
* <b><code>&nbsp;&nbsp;1795⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;263🍴</code></b> [PiCAST](https://github.com/lanceseidman/PiCAST)) - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [sejda](https://github.com/torakiki/sejda/)) - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc)
* <b><code>&nbsp;&nbsp;8853⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;324🍴</code></b> [visidata](https://github.com/saulpw/visidata)) - A terminal spreadsheet multitool for exploring and arranging data (csv/json/xml/xls/yaml/etc)
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [xidel](https://github.com/benibela/xidel/)) - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery.
* [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.
* <b><code>&nbsp;14953⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;748🍴</code></b> [yq](https://github.com/mikefarah/yq)) - yq is a portable command-line YAML processor

## Applications

*Command line-based applications or command line access to existing services.*

* <b><code>&nbsp;&nbsp;1931⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;147🍴</code></b> [ansiweather](https://github.com/fcambus/ansiweather)) - Weather in your terminal, with ANSI colors and Unicode symbols
* <b><code>&nbsp;&nbsp;4983⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;259🍴</code></b> [awless](https://github.com/wallix/awless)) - A powerful, innovative and small surface CLI to manage AWS.
* <b><code>&nbsp;&nbsp;1764⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;240🍴</code></b> [bashblog](https://github.com/cfenollosa/bashblog)) - A Bash script that handles blog posting
* <b><code>&nbsp;&nbsp;5986⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [carbon-now-cli](https://github.com/mixn/carbon-now-cli)) - 🎨 Beautiful images of your code — from right inside your terminal.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [choosealicense-cli](https://github.com/lord63/choosealicense-cli)) - Choose an OSS license from the comfort of your terminal
* <b><code>&nbsp;&nbsp;4381⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;354🍴</code></b> [cointop](https://github.com/miguelmota/cointop)) - The fastest and most interactive terminal based UI application for tracking cryptocurrencies
* <b><code>&nbsp;&nbsp;1135⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [dstask](https://github.com/naggie/dstask)) - Single binary terminal-based TODO manager with git-based sync + markdown notes per task
* <b><code>&nbsp;&nbsp;5318⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;357🍴</code></b> [editly](https://github.com/mifi/editly)) - Command line video editor
* <b><code>&nbsp;&nbsp;&nbsp;400⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [facebook-cli](https://github.com/specious/facebook-cli)) - Facebook command line tool
* <b><code>&nbsp;&nbsp;1528⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [fanyi](https://github.com/afc163/fanyi)) - Translate English to Chinese in terminal
* <b><code>&nbsp;&nbsp;3651⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;325🍴</code></b> [gcalcli](https://github.com/insanum/gcalcli)) - Google Calendar command line interface
* <b><code>&nbsp;&nbsp;2097⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;328🍴</code></b> [geeknote](https://github.com/VitaliyRodnenko/geeknote)) - Command line evernote client
* <b><code>&nbsp;&nbsp;4120⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;170🍴</code></b> [haxor-news](https://github.com/donnemartin/haxor-news)) - Browse Hacker News like a haxor
* <b><code>&nbsp;&nbsp;&nbsp;469⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [hn-cli](https://github.com/rafaelrinaldi/hn-cli)) - Browse Hacker News from the comfort of your Terminal
* <b><code>&nbsp;&nbsp;&nbsp;330⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [iponmap](https://github.com/nogizhopaboroda/iponmap)) - Draw point on world map using ip address
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [isitup](https://github.com/lord63/isitup)) - Check whether a website is up or down
* <b><code>&nbsp;&nbsp;7162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;548🍴</code></b> [jrnl](https://github.com/jrnl-org/jrnl)) - A simple command line journal application that stores your journal in a plain text file
* <b><code>&nbsp;&nbsp;&nbsp;935⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [kanban.bash](https://github.com/coderofsalvation/kanban.bash)) - commandline asciii kanban board for minimalist productivity bash hackers (csv-based)
* <b><code>&nbsp;&nbsp;5865⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;536🍴</code></b> [ledger](https://github.com/ledger/ledger)) - Command line accounting
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [licen](https://github.com/lord63/licen)) - Generate your license. Yet another lice, but implement with Jinja2 and docopt
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [md2png](https://github.com/weaming/md2png)) - Convert markdown to PNG image
* <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [moviemon](https://github.com/iCHAIT/moviemon)) - Everything about your movies within the command line.
* <b><code>&nbsp;&nbsp;&nbsp;706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [nomino](https://github.com/yaa110/nomino)) - Batch rename utility using regex, sort and map file options.
* <b><code>&nbsp;&nbsp;&nbsp;587⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [pcalc](https://github.com/alt-romes/programmer-calculator)) - Calculator made for programmers working with multiple number representations, sizes, and overall close to the bits.
* <b><code>&nbsp;&nbsp;&nbsp;502⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [pockyt](https://github.com/achembarpu/pockyt)) - Read, Manage, and Automate your 🌎 [Pocket](getpocket.com) collection.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [pushblast](https://github.com/alebcay/pushblast)) - Get PushBullet notifications when a shell program exits
* <b><code>&nbsp;&nbsp;&nbsp;237⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [pushbullet-bash](https://github.com/Red5d/pushbullet-bash)) - Bash interface to the PushBullet API
* <b><code>&nbsp;16939⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;928🍴</code></b> [ranger](https://github.com/ranger/ranger)) - A console file manager with VI key bindings.
* <b><code>&nbsp;&nbsp;4642⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;283🍴</code></b> [Reddit Terminal Viewer](https://github.com/michael-lazar/rtv)) - Browse Reddit from your terminal
* <b><code>&nbsp;&nbsp;5308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [SAWS](https://github.com/donnemartin/saws)) - A Supercharged AWS CLI
* <b><code>&nbsp;&nbsp;9271⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;392🍴</code></b> [taskbook](https://github.com/klaussinani/taskbook)) - Tasks, boards & notes for the command-line habitat
* 🌎 [taskwarrior](taskwarrior.org/) - A command-line TODO list manager
* <b><code>&nbsp;&nbsp;&nbsp;901⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [terjira](https://github.com/keepcosmos/terjira)) - Command line power tool for Jira
* <b><code>&nbsp;&nbsp;5949⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;323🍴</code></b> [ticker](https://github.com/achannarasappa/ticker)) — Terminal stock ticker with live updates and position tracking
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [vl](https://github.com/ellisonleao/vl)) - URL link checker on text documents
* <b><code>&nbsp;&nbsp;8399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;502🍴</code></b> [wego](https://github.com/schachmat/wego)) - Weather app for the terminal
* <b><code>&nbsp;&nbsp;&nbsp;391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [whales](https://github.com/Gueils/whales)) - A tool to automatically dockerize your applications
* <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [whereami](https://github.com/rafaelrinaldi/whereami)) - Get your geolocation information from the CLI
* <b><code>&nbsp;28884⭐</code></b> <b><code>&nbsp;&nbsp;1210🍴</code></b> [wttr.in](https://github.com/chubin/wttr.in)) - :partly_sunny: The right way to check the weather (curl wttr.in)

## Games

*All work and no play is a cruddy way to spend your day.*

* <b><code>&nbsp;&nbsp;&nbsp;910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [bash2048](https://github.com/mydzor/bash2048)) - Bash implementation of 2048 game
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper)) - Bash implementation of minesweeper
* <b><code>&nbsp;&nbsp;&nbsp;363⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [nudoku](https://github.com/jubalh/nudoku)) - ncurses based sudoku game written in C
* <b><code>&nbsp;&nbsp;&nbsp;745⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [piu-piu](https://github.com/vaniacer/piu-piu-SH)) - Horizontal scroller game in bash with multiplayer mode!
* <b><code>&nbsp;&nbsp;&nbsp;566⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [sedtris](https://github.com/uuner/sedtris)) - Tetris in sed
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [sed-scripts](https://github.com/aureliojargas/sed-scripts)) - Arkanoid and Sokoban written using sed
* 🌎 [SHTAP](notimetoplay.org/engines/shtap/) - Reusable text adventure engine for Bash 4
* <b><code>&nbsp;&nbsp;&nbsp;333⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [tty-solitaire](https://github.com/mpereira/tty-solitaire)) - Play solitaire in your terminal!

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

* <b><code>&nbsp;14968⭐</code></b> <b><code>&nbsp;&nbsp;2316🍴</code></b> [bash-it](https://github.com/Bash-it/bash-it)) - A community Bash framework
* <b><code>&nbsp;&nbsp;1270⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [basher](https://github.com/basherpm/basher)) - A package manager for shell scripts
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [bashing](https://github.com/xsc/bashing)) - Smashing Bash into Pieces
* 🌎 [bpkg](www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
* <b><code>&nbsp;&nbsp;1904⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [dotdrop](https://github.com/deadc0de6/dotdrop)) - Save your dotfiles once, deploy them everywhere
* <b><code>&nbsp;&nbsp;&nbsp;250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [dotfiler](https://github.com/svetlyak40wt/dotfiler)) – Shell agnostic git based dotfiles package manager, written in Python.
* <b><code>&nbsp;&nbsp;1215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [fresh](https://github.com/freshshell/fresh)) - Keep your dotfiles fresh
* <b><code>&nbsp;&nbsp;2187⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [homeshick](https://github.com/andsens/homeshick)) - Git dotfile synchronizer written in Bash
* <b><code>&nbsp;&nbsp;1314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [shallow-backup](https://github.com/alichtman/shallow-backup)) - Easily create lightweight documentation of installed packages, dotfiles, and more
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [shundle](https://github.com/javier-lopez/shundle)) - Plugin manager for shell scripts
* <b><code>&nbsp;&nbsp;2250⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;127🍴</code></b> [vcsh](https://github.com/RichiH/vcsh)) - Config manager based on Git
* 🌎 [yadm](yadm.io/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* <b><code>&nbsp;&nbsp;&nbsp;792⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [ansi](https://github.com/fidian/ansi)) - ANSI escape codes in pure bash - change text color, position the cursor, much more
* <b><code>&nbsp;&nbsp;&nbsp;493⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [assert.sh](https://github.com/lehmannro/assert.sh)) - Bash unit testing framework
* <b><code>&nbsp;&nbsp;&nbsp;293⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [bashew](https://github.com/pforret/bashew)) - bash script creator - from small stand-alone script to complex projects with CI/CD and testing
* <b><code>&nbsp;&nbsp;&nbsp;619⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [bashful](https://github.com/jmcantrell/bashful)) - A collection of libraries to simplify writing Bash scripts
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Bashlets](https://github.com/reale/bashlets)) - A modular extensible toolbox for Bash
* 🌎 [bashly](bashly.dannyb.co/) - Bash command line framework and CLI generator
* <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [bashmanager](https://github.com/lingtalfi/bashmanager)) - mini bash framework for creating command line tools
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [bashwithnails](https://github.com/mindaugasbarysas/bashwithnails)) - a Bash framework written just for fun with testing, dependency management & packaging
* <b><code>&nbsp;&nbsp;2641⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [bash-language-server](https://github.com/bash-lsp/bash-language-server)) - 🌎 [LSP](microsoft.github.io/language-server-protocol/)-based Bash language server
* <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [bash-modules](https://github.com/vlisivka/bash-modules)) - functions for developing with [unofficial strict mode](http://redsymbol.net/articles/unofficial-bash-strict-mode/) enabled.
* <b><code>&nbsp;&nbsp;5849⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;464🍴</code></b> [bats](https://github.com/bats-core/bats-core)) - Bash Automated Testing System
* <b><code>&nbsp;&nbsp;&nbsp;343⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [composure](https://github.com/erichs/composure)) - Compose, document, version and organize your shell functions
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [crash](https://github.com/molovo/crash)) - Proper error handling, exceptions and try/catch for ZSH
* <b><code>&nbsp;&nbsp;&nbsp;456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [critic.sh](https://github.com/Checksum/critic.sh)) - Dead simple testing framework for Bash with coverage reporting
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md)) - A command line argument parser in 50 lines of portable shell script.
* <b><code>&nbsp;&nbsp;&nbsp;233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [esh](https://github.com/jirutka/esh)) - A simple templating engine based on shell, implemented in ~290 lines of POSIX shell and awk.
* <b><code>&nbsp;&nbsp;&nbsp;374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [Fishtape](https://github.com/jorgebucaran/fishtape)) - TAP producer and test harness for fish
* <b><code>&nbsp;&nbsp;&nbsp;511⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [getoptions](https://github.com/ko1nksm/getoptions)) - An elegant option parser for shell scripts (sh, bash and all POSIX shells)
* <b><code>&nbsp;&nbsp;&nbsp;235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [getopts.fish](https://github.com/jorgebucaran/getopts.fish)) - CLI parser for fish
* <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [is.sh](https://github.com/qzb/is.sh)) - An alternative for builtin test command, it will make your "if" statements pretty
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [lumberjack](https://github.com/molovo/lumberjack)) - A logging interface for shell scripts
* <b><code>&nbsp;&nbsp;&nbsp;598⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [mo](https://github.com/tests-always-included/mo)) - Mustache templates in pure bash
* <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [optparse](https://github.com/nk412/optparse)) - A BASH wrapper for getopts, for simple command line arguments.
* <b><code>&nbsp;&nbsp;&nbsp;461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [rerun](https://github.com/rerun/rerun)) - A modular shell automation framework to organize your keeper scripts
* <b><code>&nbsp;&nbsp;&nbsp;161⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [revolver](https://github.com/molovo/revolver)) - A reusable progress spinner for shell scripts
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [phases](https://github.com/sorokine/phases)) - Minimally invasive bash preprocessor, select sections of your script to run
* <b><code>&nbsp;&nbsp;&nbsp;168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [powscript](https://github.com/coderofsalvation/powscript)) - bash transpiler written in bash (coffeescript for bash)
* <b><code>&nbsp;&nbsp;&nbsp;268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [semver_bash](https://github.com/cloudflare/semver_bash)) - Semantic Versioning in Bash
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [sh-semver](https://github.com/qzb/sh-semver)) - Semver tool for bash - finds versions matching to specified rules
* <b><code>&nbsp;39039⭐</code></b> <b><code>&nbsp;&nbsp;1902🍴</code></b> [shellcheck](https://github.com/koalaman/shellcheck)) - Static analysis tool for shell scripts
* <b><code>&nbsp;&nbsp;1222⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [shellfire](https://github.com/shellfire-dev/shellfire)) -  A repository of namespaced, composable shell (bash, sh and dash) function libraries
* <b><code>&nbsp;&nbsp;1349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [shellspec](https://github.com/shellspec/shellspec)) - A full-featured BDD unit testing framework for dash, bash, ksh, zsh and all POSIX shells
* <b><code>&nbsp;&nbsp;8485⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;382🍴</code></b> [shfmt](https://github.com/mvdan/sh)) - A shell parser, formatter, and interpreter with bash support; includes shfmt
* <b><code>&nbsp;&nbsp;&nbsp;387⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [shpec](https://github.com/rylnd/shpec)) - A shell testing framework
* 🌎 [shutit](ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
* <b><code>&nbsp;&nbsp;1760⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;145🍴</code></b> [sub](https://github.com/basecamp/sub)) - A delicious way to organize programs
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [ts](https://github.com/thinkerbot/ts)) - A shell test script
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [urchin](https://github.com/tlevine/urchin)) - An idiomatic shell testing framework that uses only shell commands
* <b><code>&nbsp;&nbsp;1726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [shunit2](https://github.com/kward/shunit2)) - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;80⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [rebash](https://github.com/jandob/rebash)) - Scripting library/framework. Features: imports, exceptions, doc-tests ...
* <b><code>&nbsp;&nbsp;&nbsp;220⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [zunit](https://github.com/zunit-zsh/zunit)) - A powerful unit testing framework for ZSH

# Guides

* 🌎 [Bash Official Reference Manual](www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)
* 🌎 [Bash Hackers Wiki](web.archive.org/web/20230406205817/https://wiki.bash-hackers.org/)
* 🌎 [Greg Wooledge's (aka "greycat") wiki](mywiki.wooledge.org).
  Specifically 🌎 [Bash Guide](mywiki.wooledge.org/BashGuide), 🌎 [Bash FAQ](mywiki.wooledge.org/BashFAQ) and 🌎 [Bash Pitfalls](mywiki.wooledge.org/BashPitfalls)
* 🌎 [Google's Shell Style Guide](google.github.io/styleguide/shell.xml)
* 🌎 [The Linux Documentation Project: Bash Programming - Intro/How-to](tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
* 🌎 [The Linux Documentation Project: Advanced Bash Scripting Guide](tldp.org/LDP/abs/html/)
* 🌎 [WikiBooks: Bash Shell Scripting](en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* <b><code>159975⭐</code></b> <b><code>&nbsp;14765🍴</code></b> [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line))
* 🌎 [Learn Enough Command Line to Be Dangerous](www.learnenough.com/command-line-tutorial/basics)
* <b><code>&nbsp;12237⭐</code></b> <b><code>&nbsp;&nbsp;1047🍴</code></b> [A guide to learn bash](https://github.com/Idnan/bash-guide))
* 🌎 [Shell Field Guide](raimonster.com/scripting-field-guide/)

# Other Awesome Lists

Other amazingly awesome lists can be found in <b><code>&nbsp;&nbsp;3105⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;286🍴</code></b> [awesome-awesome](https://github.com/emijrp/awesome-awesome)) and <b><code>&nbsp;33254⭐</code></b> <b><code>&nbsp;&nbsp;3588🍴</code></b> [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)).

### See also

* <b><code>&nbsp;18807⭐</code></b> <b><code>&nbsp;&nbsp;1121🍴</code></b> [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps))
* [awesome-fish][awesome-fish]
* [awesome-zsh][awesome-zsh]
* [awesome-bash][awesome-bash]
* <b><code>&nbsp;12906⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;624🍴</code></b> [terminals-are-sexy](https://github.com/k4m4/terminals-are-sexy))

[awesome-badge]: https://raw.githubusercontent.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-fish]: https://github.com/jorgebucaran/awsm.fish
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins
[awesome-bash]: https://github.com/awesome-lists/awesome-bash

## Source
<b><code>&nbsp;36549⭐</code></b> <b><code>&nbsp;&nbsp;2471🍴</code></b> [alebcay/awesome-shell](https://github.com/alebcay/awesome-shell))
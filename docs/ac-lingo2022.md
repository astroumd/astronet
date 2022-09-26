# Astro Computing Lingo (26-sep-2022) 

astronet
--------
 
UMD:

      username@umd.edu                       use this for email and all other official UMD stuff

ASTRO:

      username@astro.umd.edu                 password is not shared with the umd.edu one!
      ssh username@terra.astro.umd           to change the password, nightly redistributed
      https://www.astro.umd.edu/~username    $HOME/public_html/index.html   dept_info.{txt,jpg}

Essentials tools:
-----------------
- unix [linux/macosx] shell (bash, tcsh, zsh, ...)
  - linux:   redhat, ubuntu
  - mac:     macosx (linux)
  - win:     WSL2 (=ubuntu)
  - chrome:  linux container
- X11 (Quartz on the mac w/ Xcode)
- ssh, rsync, unison, timeshift   (password-less w/ ssh-copy-id)
- editor (emacs, vim, sublime, ...)
- vpn
- tmux/screen
- vnc (x2go)
- latex, overleaf
- git (e.g. https://github.com/astroumd/thesisware)
            Facilities and Software
- google docs / box / ...
- C/C++/Fortran - python - R - julia - matlab - idl - mathematica
- casa, pyraf, heasarch, chanda
- https://ascl.net    (2000+ codes)
   anatomy of a code:
   - download
   - install
   - run
   - data & plot?
- papers:
  - your own "ADS" library, but then on disk (book manager / zotero)
  - jstor.org
  - arXiv:  RSS feed, e.g. feedly.com
  - zotero
- makefile
- how to get help:
    <CMD> --help
    <CMD> -h
    man CMD
    tldr CMD
    zeal (linux) / dash (mac)
- astroload (from /n/astromake)
- modules
- <ASK>  help@astro.umd.edu
  
- **astronet hardware**:   cpu - memory - hard drive (HDD/SDD) - network
  - laptop, desktop :  "single cpu" (small core)
    [laptop can get hot and slow down]
  - departmental emergency laptop (Dell linux, MacBook/pro)
  - small clusters (yorpXX, astraXX)            
  - small groups (labXX)                   
  - GPU (gpuX)
  - raid storage (horizon)
  - large core machines (lma, 32 cores/64 threads)
  - small core fast CPU (astraXX)
  - big clusters (zaratan)

Tips:

  - stick to an editor (emacs, vim, sublime, ...)
  - if something becomes repetitive, "script it" and "benchmark it"
    - bash/tcsh (WYSIWYG)
    - Makefile (WYSIWYG)
    - GNU parallel (WYSIWYG)
    - python
  - use single core parallel when possible (multi-core OpenMP is hard)



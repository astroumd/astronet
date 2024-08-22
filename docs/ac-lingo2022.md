# Astro Computing Lingo (22-aug-2024) 

astronet
--------
 UMD:

      username@umd.edu                       use this for email and all other official UMD stuff
ASTRO:

      username@astro.umd.edu                 password is not shared with the umd.edu one!
      ssh username@terra.astro.umd.edu       to change the password, redistributed hourly
      https://www.astro.umd.edu/~username    $HOME/public_html/index.html   dept_info.{txt,jpg}

Essentials tools:
-----------------
- unix [linux/macosx] shell (bash, tcsh, zsh, ...)
  - linux:   redhat, ubuntu
  - mac:     macosx 
  - win:     WSL2 (=ubuntu)
  - chrome:  linux container
- X11 (Quartz on the mac w/ Xcode) (future: Wayland)
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
- Makefile
- how to get help:
    - <CMD> --help
    - <CMD> -h
    - man CMD
    - tldr CMD
    - zeal (linux) / dash (mac)
- astroload (from /n/astromake) and "rc"
- modules ("module load gcc-12")
- <ASK>  help@astro.umd.edu
- **astronet hardware**:   cpu - memory - hard drive (SSD/HDD) - network
  - laptop, desktop :  "single cpu" (small core)
    [laptop can get hot and lower cpufreq]
  - departmental emergency laptop (Dell linux, MacBook/pro)
  - small clusters (yorpXX, astraXX)            
  - small groups (labXX)                   
  - GPU (gpuX)
  - raid storage (horizon)
  - large core machines (**lma**, 32 cores/64 threads)  
  - small core fast CPU (astraXX)
  - big clusters (zaratan) - including GPU
  - .
  - .


Tips:

  - stick to a colorizing editor (emacs, vim, sublime, VScode, ...)
  - if something becomes repetitive, "script it" and "benchmark it"
    - bash/tcsh (WYSIWYG)
    - Makefile (WYSIWYG)
    - GNU parallel (WYSIWYG)
    - python
  - use single core parallel when possible (multi-core OpenMP is hard)

Checklist:

  - set up your accounts:   "umd" and "astro"
  - set up your 2FA, so you can email and do wireless
  - download VPN so you can "ssh astro.umd.edu" from home (future)
  - printing at "astro"

This page also on:   https://github.com/astroumd/astronet/blob/main/docs/ac-lingo2022.md

Presentation on:     https://www.astro.umd.edu/~teuben/ACC/astr695-2024.pdf

---
title: Setup
---

## Install R if needed

The [R project for statistical computing][r-lang] provides the R programming enviornment, which you can download and install at the link. The R language is supported by an library of software, the [Comprehensive R archive network][cran], or CRAN, from which you can download both R and R language packages.

### Different installation for different operating systems

**Both R and RStudio run on all platforms (Windows, MacOSX, and Linux)**

R (the language) and RStudio (the integrated development environment) are available on all major operating systems, including Windows, MacOSX, and Linux. The exact installation procedures will differ depending on which version you use for installation.

MacOSX is more "Linux-like" than Windows, and some aspects of working with R may be easier on a Mac than on a Windows computer. That said, if you are using Windows, you can install the Windows Subsystem for Linux (WSL) and you will get a Linux system working natively on your Windows computer. If you are using Windows 11 and install the latest Ubuntu version of Linux (22.04) in your WSL installation, Linux graphics will run natively on your Windows computer.

**If you are using the laboratory computers, R and R Studio should already be installed**

> ## Ubuntu Linux using `apt`
> 
> You can install R from the Ubuntu Linux command line using the `apt` package manager. This should
> be equivalent to downloading from CRAN, except that the Ubuntu package manager may be slightly
> behind the most recent R version release. To install using apt, type
> 
>  ~~~
>  sudo apt-get install r-base-core
>  ~~~
> {: .language-bash}
>
> You need to use `sudo` for this command because installing software using apt requires administrator privileges. You will be prompted for an administrator (privileged) password.
{: .linux}

## Install RStudio

You can use R by itself, or you can use RStudio, an integrated environment for R programming. We highly recommend using RStudio! To install RStudio go to [The RStudio web site][rstudio]and follow the instructions.

{% include links.md %}
{% include site-links.md %}

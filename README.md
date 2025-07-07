### Complete Recon Automation Framework

*Disclaimer: I'm not the original author of the script, I only updated both `install.sh` and `script.sh` to actually work in modern versions of Kali*

So, I stumbled upon a video on YouTube showcasing the [Complete Recon Automation Framework](https://github.com/cyberflow-academy/Complete-Recon-Automation-Framework)

I downloaded it, try to run `install.sh` and it was a mess, most of the tools used the deprecated method of installing go tools (`go get -u`) and some used `pip install -r requirements.txt`

So I said, I'll take it, let's modify the entire installation script **and** the `script.sh` itself to work with the latest version of all tools and use the proper installation methods (`pipx install git+github.com/foobar`)

And it worked!

Props to the original author [Cyberflow Academy](https://github.com/cyberflow-academy) for all the major work in putting up this script together for everyone, the only thing I did was to ensure every tool was installed properly and some deprecated options in `script.sh` were removed and/or replaced with the current version equivalent

---

- This tool automates the reconnaisance part of Bug Bounty hunting, aggregating all the commands and saving the results organized in a directory structure

#### Happy hacking!

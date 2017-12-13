# Machine Setup

Machine setup, powered by Ansible.  Finally got this simplified and cleaned up.

## Usage:

```console
$ curl -sSk https://raw.githubusercontent.com/ciscomonkey/machine/master/web_install | bash
```

### Alternative:
```console
$ mkdir ~/dev
$ git clone https://github.com/ciscomonkey/machine.git ~/dev/machine
$ cd ~/dev/machine
```

If you need to edit anything, this is the time to do it.  Once done, run:

```console
$ ./setup
```

## Todo:

brew install autoenv
pip3 install virtualenv virtualenvwrapper
add bashrc stuff

* Applications
  * virtualenv and dev tools
* App Config files:
  * ST3
  * iTerm2
  * Git
  * Hazel
* Certificates?
* Licenses?
* Create ~/bin
  * Populate apps - They're in github right? ;D

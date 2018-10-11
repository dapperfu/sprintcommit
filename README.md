# sprintcommit

# Usage

### As Submodule

Add as a submodule:

```git submodule add --force --depeth=1 -- https://github.com/jed-frey/sprintcommit.git```

As a submodule in a dot directory:

```git submodule add --force --depeth=1 -- https://github.com/jed-frey/sprintcommit.git .sc```


### Standalone

Clone into a directory named sprintcommit.

```git clone --depth=1 --single-branch --recurse-submodules --shallow-submodules --jobs=4 -- https://github.com/jed-frey/sprintcommit.git```

Clone into a directory named sprintcommit.

```git clone --depth=1 --single-branch --recurse-submodules --shallow-submodules --jobs=4 -- https://github.com/jed-frey/sprintcommit.git /projects/sc```

# Development

```
git clone --recurse-submodules --no-shallow-submodules --jobs=4 -- https://github.com/jed-frey/sprintcommit.git
export DEBUG=1
cd sprintcommit
./sprintcommit
```


```
git clone --depth=1 --single-branch --recurse-submodules --shallow-submodules --jobs=4 -- https://github.com/jed-frey/sprintcommit.git /tmp/sprintcommit
cd /tmp/sprintcommit
GIT_BIN=echo /tmp/sprintcommit.sh
DEBUG=1 /tmp/sprintcommit.sh```
```

```
sprintcommit.sh [COMMIT_TIME]
 Arguments:
    COMMIT_TIME: Time (s) to sleep between commits.
       Default: 0
       If the value is zero (0) sprintcommit.sh runs once and exits.
 A tool for commiting code changes during 'in the zone' development sprints.
gi
 A brute force hammer written by a Mechanical/Industrial Engineer frustrated
 at the disproportonate amount of time 'managing' git when we were supposed
 to be working.
 ```

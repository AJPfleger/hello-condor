# Hello Condor

Just a repo to get familiar with (HTCondor)[https://htcondor.org/].

## Useful Commands

```shell
condor_submit hello.sub
condor_q
condor_q -held
condor_release -all
condor_wait -status log/hello.5539120.log
```

## Literature

https://batchdocs.web.cern.ch/local/quick.html
https://indico.cern.ch/event/980285/contributions/4129607/attachments/2152204/3640264/HTCondor_Tutorial(18).pdf

## Caveats

You need to manually create the folders locally, if you want to write output to some sub folders.


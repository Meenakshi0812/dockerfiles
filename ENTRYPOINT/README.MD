   ### ENTRYPOINT
   ENTRYPOINT is also used to run the container just like CMD.But there are few differences.
   1.we can't override ENTRYPOINT, but we can override CMD.
   2.we can't override ENTRYPOINT, if we try to override it will go and append to the ENTRYPOINT command.
   3.if we use CMD and ENTRYPOINT and dont give any command from terminal , CMD acts as argument provider to ENTRYPOINT.
   4.CMD will supply default arguments to ENTRYPOINT.
   5.you can always override CMD arguments from runtime 
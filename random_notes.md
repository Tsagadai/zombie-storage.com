# Most effective SSH tunneling

For some unknown reason I can never remember exactly how to set up an ssh tunnel and I always do it some other way. This is an effective way to map the local port to the same external port on `target` (handy for web apps like jupyter or zeppelin)

ssh -f -N -L localhost:<port>:0.0.0.0:<port> <target>

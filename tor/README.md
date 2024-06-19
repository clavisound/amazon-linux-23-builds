I made those scripts to use github which is IPv4 only with my IPv6 only amazon linux server.

Put here source files for tor and torsocks and run the scripts.

After starting tor, in another terminal run `source torsocks on`. Now with `torsocks sh` you can verify that LD_PRELOAD was a torsocks library. Now you start any program and the traffic will go through tor.

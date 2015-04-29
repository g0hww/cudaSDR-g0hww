# cudaSDR-g0hww

A fork of VK5ABN's cudaSDR for fiddling with. 

Fork created with "git svn clone http://svn.tapr.org/repos_sdr_hpsdr/trunk/VK5ABN/cudaSDR" on development 'puter so I can hopefully keep this up-to-date with the svn upstream.

 * Master branch is currently pristine upstream from VK5ABN's svn repo.
 * Branch n1gp-local-sound includes local audio changes from https://github.com/n1gp/cudaSDR

I have just obtained an ANAN-100D, and have been using it with this cudaSDR version on Ubuntu 14.04 x86_64.  The master branch works, and so does the n1gp-local-sound branch with local audio routing available in pavucontrol.

It seems to support up to 4 receivers with my Angelia/ANAN-100D.  Any more and something goes wonky requiring the turning-off-and-on-again of the rig and a restart of cudaSDR.

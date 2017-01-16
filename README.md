<H1> High Perofrmance Computing Competition </H1>
<H3> Repository for Annual High Performance Computing Competition at Universirty of Tulsa, Oklahoma </H3>
Weblink: http://www.greatplains.net/news/firstannualoklahomahighperformancecomputingcompetition

<b>Description:</b> The competition will have two tracks, one focused on programming for high-performance computing on a cluster, and a second focused on the setup and administration of a cluster.
Uniform hardware, costing approximately $500 - $550
Teams of 2-4 students


<b> Steps to install GMP Library </b>
1. Download the latest .tar file from https://gmplib.org/#DOWNLOAD.
2. Make sure you have m4 dependency installed, <b>"sudo apt-get install m4"</b> will do the job.
3. Extract the files <b>tar -xvf GMP.....</b>
4. <b>cd ~/GMP</b>
5. <b>./configure</b>, this will run all the necessary tests and the log will be saved in config.log
6. <b>make</b>
7. <b>make install</b> if no error everything is good so far.
8. Finally <b>make check</b> and it's ready to go.

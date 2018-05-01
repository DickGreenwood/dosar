# High Throughput Computing and Condor Introduction

## Preliminaries

You will receive login credentials at the beginning of this session. 

   * You might want to refer to the [online Condor 8.6.8 manual](http://research.cs.wisc.edu/htcondor/manual/v8.6/).<br>
   * You may enjoy browsing the [Condor web page](http://www.cs.wisc.edu/condor/).<br>

## Which Condor?
We will be using Condor 8.2.10, which is a recent production version of Condor.

Condor has two coexisting types of releases at any given time: stable and development. Condor 8.2.X and 7.8.x are considered stable releases, and you can know they are stable because the second digits (a 2 or a 8 in these cases) are  even numbers. In a given stable series, all versions have the same features (for example 7.8.0 and 7.8.1 have the same set of features) and differ only in bug fixes.

## Where you will work

Today you will log into user-training.osgconnect.net for all of your exercises:

Login on submission node using:

<pre><code>
$ <b>ssh -XY YOUR_USER_ID@user-training.osgconnect.net</b>
</code></pre>

You may get a message asking you to establish the authenticity of this connection. Answer "yes". 

When you login to the machine you will be in your "home directory".  We recommend that you work in this directory as nobody else can modify the files here.

You can always return to your home directory by running the command

<pre><code>
$ <b>cd ~</b>
</code></pre>


## The Exercises

Throughout the Condor exercises, you will be given a fair amount of guidance. In several spots, there are suggestions for extra exercises to do "on your own" or as "challenges". Since you aren't being graded, there is no extra credit for doing them, but we encourage you to try them out. If you prefer, you can come back to the extra credit after you've completed the basic exercises. If you simply cruise through the exercises, you'll probably have free time--we encourage you to delve in more deeply.

For all of the exercises, we'll assume that you are logged into user-training.osgconnect.net. You should have received your name and password for user-training.osgconnect.net at the beginning of the Computation Infrastructures lecture.

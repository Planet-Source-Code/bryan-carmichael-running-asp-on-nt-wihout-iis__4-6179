<div align="center">

## Running ASP on NT wihout IIS


</div>

### Description

Want to solve those IIS server restart issues - read this article - the web serving platform you dreamt of on NT ?
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Bryan Carmichael](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/bryan-carmichael.md)
**Level**          |Intermediate
**User Rating**    |3.0 (12 globes from 4 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML, VbScript \(browser/client side\)

**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__4-1.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/bryan-carmichael-running-asp-on-nt-wihout-iis__4-6179/archive/master.zip)





### Source Code


<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; Fed up with server restarts? -Trying to wring better performance out of your web server? Trying to get non-IIS boxes to integrate with your system? Fear not, there is an answer that doesn't involve hours of development or cost 100,000's of dollars -unfortunately this answer is not one that Microsoft likes too much.&nbsp;<br>
Put simply - uninstall IIS on your NT server and be ready for an adventure on the dark side of ASP!&nbsp;<br>
<br>
Step 1 - After uninstalling IIS, go to www.Apache.org and download version 1.3.9 of their web server - note this is not the most recent release but bear with me here. Install the server and set it to run as a NT Service - okay now we have a faster, more stable web server.&nbsp;<br>
<br>
Step 2 - Go to www.Chilisoft.com and download yourself a developer version of their ASP product (current version is 3.0.4) - this will give you a 5 client unlimited time licence. Install the product and reboot your machine - now we have a fast, stable ASP Platform.&nbsp;<br>
<br>
Step 3 - Try one of your existing applications and be surprised at the improved performance. Just to explain here, I don't work with or for either Apache or Chilisoft, nor am I in anyway supported or paid to endorse their products - I just like to use the best tools for the job - and when you run an 11 server multi OS Cluster web-site you have no room to take prisoners or use duff kit.&nbsp;<br>
Now, I hear you say, where is the catch? Well cost wise, Chilisoft's product starts at $1000 per 4 CPU NT licence, although you can always get a better price than this from them - but just think how many 2.00am server restarts avoided is $1000 worth - to never have to get up to reboot IIS is worth $1000 to me.&nbsp;<br>
Then there are all those alleged niceties, or features as Microsoft would call them that you don't get. To start with, there is no CDONTS - if that fills you with dread then maybe this route is not for you, although I built a 10,000 user web based email system in under a week on this platform and that included integration with 2 Linux mail servers - you just need a bit of imagination and a maverick streak.&nbsp;<br>
Other major issues include getting boxes to talk to one another - no nice IIS user features here but there are a myriad of workarounds and it certainly makes life interesting.&nbsp;<br>
I guess in the end it comes down to how you want to live your life - if cosy warm and closeted is your thing stick with IIS - if like me, you like to live on the frontiers of life and get the most out of everything (including optimal server performance) then ditch IIS and come on over to the dark side of ASP - where I will be waiting for you, hopefully with a big sack of articles including how to build a 4 page forum system that supports a near infinite number of messages, replies and users and runs on a lowly single processor box.&nbsp;<br>
Just for a bit of reference: we run over 1,000,000 page impressions a month on each of our 3 front end servers and the busiest they have ever been is 3% CPU usage - they are PIII 500 - single CPU 512Ram Compaq 1850's so they are not exactly monsters - just runnng real efficient code and web-serving technology.&nbsp;<br>
For those of you who cannot bring yourself to run NT and run Linux then fear not Chilisoft also do a linux version &#8211; check it out at http://www.chilisoft.com/platforms/linux.asp<br>
</font></p>


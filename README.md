# YT-Musik
YouTube music downloader
Vaibhav Pandya
**NOTE: The YouTube API/library that I am using cannot download all of the videos because of the restrictions put on by YouTube. If this is the case, your download status (in the DL Queue) will be something like 'cannot download due to YT restrctions'. And also this is only a class project learning application so we are not violating any terms. These links do work:

-https://www.youtube.com/watch?v=RiVKDn5kyfo&list=PLYiUhQLFA05uY8Fk8sR1mK_McHY17jXpI

-https://www.youtube.com/watch?v=cOsqdghHcIk

**NOTE: Also for the play tab, unfortunately, we cannot play the songs because the downloads will be in either WebM or MP4 format and the Java API doesnt support these formats and therfore cannot play them. I did try to use an opensource library VlcJ but could not get it to work. The library was throwing some kind of exception. But if you do want to play and check out the downloads, you can use it with something like VLC media player. 

Compilation: I have provided the executable jar file for convenience. Still if you want to compile from command line, do javac *.java and then run the program by java YTForm

How to use?
To just use the program, use the executable jar file that I have provided. If you want to use the code, copy the source files in a Java project. YTForm.java has the main class. NO other libraries required. 
When you run the program:
Type the YT URL, then hit Check and wait
Choose a quality option and hit Download
That's it. Downloads will go in the current project directory
Look at the status of the downloads in the DL Queue

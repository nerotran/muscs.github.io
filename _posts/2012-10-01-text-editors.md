---
layout: post
tags: Editor Emacs
date: 2012-10-01 13:06
title: Text Editors
published: true
---

When I think about my past days of doing silly programs I sometimes laugh on me, how stupid was I, using one after another editor for writing programs. Sometimes I was searching for IDEs exhaustively. I remember, in 2005 started programming C on Turbo C++ IDE (the famous blue screen idiot) and most of the time I used to play one audio CD (composed by Tabun containing some old RD Burman songs). Then I used Eclipse for Java which was a very smart IDE in deed. Then while teaching at IEI, I had to use a very lightweight compiler suitable for my netbook and I opt Genie this time. In the first year of my PHD I learned Haskel and Prolog for which I used their custom interface.

Confused by so many options and their pros and cons, I started doing some research on text editor which would be suitable for most of the programming languages and can support me throughout my PhD. I found few very good editors namely Notepad++, Emacs, vim etc. I liked Notepad++ in windows the most. It has very lucrative features and among them I think the most imortant one is you can connect notepad++ to a remote server and it can update filecontaints in that remote server automatically. Believe me, it saved a lot of time whrn I was modifying / rebuilding the lab website at City College. When I started working in Linux I had 2 options Emacs or Vim. My room-mate  Nikhil Sarda suggested Emacs whereas my friend cum my linux Guru Adonis Kai Hong suggested Vim. For few weeks I was using both. My colleague Erald asked me for compiling his model in C and I started building the whole code in Emacs. As I was going through it, I realized the power of Emacs and why it is called God of all editors. What cant you do with it? One can only point out about the low quality graphical user interface of it if s/he wants to find out the con side. Soon I feel that you can never completely understand Emacs because it is becoming reach every day. You can modify the editor in the way you want it to function through its own lisp language. You can have your own set of hot keys. You can link it with almost all compilers starting from C to latex and so on and the cool feature is, it change its mode accordingly (from the extension of the file name). I have never thought that in terminal mode, one editor can support me auto complete option, but it is way more than that. Not only it suggest about the system / compiler defined phrase, it also parse those variables used in the program previously and give those options.

Now come to the point of Latex. I installed auctex so that Emacs can work in preview mode. I just open a .tex file and presses C-c C-c and emacs call texlive to compile the file and generate a devi file. then pressed C-c C-v and it actually open the dvi file in xdvi viewer. cool feature of xdvi viewer is that it automatically updates its content and stay on a page when the original files content has been changed by compilation. So, while modifying complex equation, I just keep the page open and modify the source in emacs, compile it and go to dvi to view it, I don;t need to scrool through all the pages. For simplicity I open emacs and xdvi side by side and they are working absolute perfect. Now I am going to stick to emacs for sure.
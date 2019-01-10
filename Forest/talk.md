==================
> reading mark beg

One of the course I was taking at that time happened to have a final
project requirement where I am free to develop anything, so I took the
opportunity to rewrite my blog (as in <a
href="https://github.com/horizon-blue/tracing">horizon-blue/tracing</a>). I
reuse the same layout and the same frameworks (i.e. React, Flask,
etc.); other than those, everything was written from starch. I’ve even
include multilingual UI texts that can be toggle dynamically. It was a
step closer to my ideal blog and was hosted on <code
class="highlighter-rouge">thehorizon.blue</code> before my server
expired.</p> 

> reading mark end
==================


GraphQL: a open-source data query and manipulation language for API...
Sounds cool. But, why you website need such query system?

> However, because I learned most of
the frameworks on the fly and didn’t have a clear blueprint at
the beginning, the code was badly organized and didn’t follow a
good convention.

Do not worry, we are not serious guy, right? You mentioned you want to
change the license to
[GLWTPL](https://github.com/me-shaon/GLWTPL). That's how we
improve. What scripts you think is not necessary for your current
website? btw, what is "some other stuffs"? Text editor, or Operating
system? How big is your blog? I've checked my: 40k. Not sure how you
evalute the speed. If you want share, please let me Know.

I saw your blog using the google's analysing script.
```
  <script type="text/javascript">
  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-71234164-1']);
  
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();
</script>

```

I used to use that piece code to track how many people view my blog,
where are they from? But overtime, I feel that I was addictive to
it. I cannot control myself to constantly check the blog. However,
indeed, those number makes no sense to me. As a blog, the most
imporant thing is to log my experience. How many people check my
website doesn't make a huge difference to me, so I stop using the
script. Maybe you have some other concerns, want to know you idea.

That's so cool to get a alerts from GitHub. What were `vulnerable
dependencies`? Why you do not have courage? You are a programmer, a
master of computer science (I do not have any bad intention here)? If
you want, I want to help you to fix the bad code together (I am not a
programmer, it could take years to finish).


## frienf's reply

WOW. I never thought anybody would bother to read my babbling carefully and write a comment in such detail... thanks! Not sure whether I should post my reponses right now or wait till you are done updating your comments ... Well, let me say something in response first, then let's see what else you are going to ask lol

- Yeah, I understand that I shouldn't be afraid of making mistakes... in theory. However, it is still a challenge to persuade myself to do so in practice lol. (Thanks for the suggestion about grammar checker; though I don't have one on my text editor, I do have a basic spell checker turned on)

- For lull I mean "an interval of lessened activity," though I'm not sure whether this is the correct way to use the term. In fact I've just picked up this word a few days prior to writing this post when I was reading a friction and this term is used to describe a period of silence during conversation.

- I took a look at your blog (the archive that you linked to), and found that civil engineering is much harder than computer science... what you wrote in the other post makes me want to cry.

- For Jekyll, what I was looking for is the ability to set a password on some of my post so that they are not accessible to everybody, because I don't want to reveal the dark side of myself to the entire world (lol). That's a minor concern as for now because I can put that sort of stuffs on somewhere else instead of my blog here.

- React is a Javascript library - though it has its own syntax (JSX) and uses ECMAScript (which is a "dialect" of Javascript) that needs to be compile to vanilla Javascript in order to use on most of the browser. Contrary to building website with HTML (or generating HTML using server), website built by React has minimal HTML involved. All you need is a single <div />, and when a website is loaded, the browser loads the Javascript file and executes it to generate the rest of the contents.

- Flask definitely requires installation (I google the sentence you quote and found the readme file here, which seems to be the precursor of Flask. If that's something you want to build, at least you need to import what you need from the bottle.py, i.e. from bottle import send_file, redirect, abort.

# Approach
https://lukebentleyfox.net/posts/building-this-blog/
```
[21:20] James: trying to build a repo where i can write posts in /posts and deploy them from an infrastructure folder with a few calls
[21:21] James: so I could set up a dedicated machine that just hosts the blog and redeploy fresh each time. hopefully nixops is smart like terraform and avoids tearing down the whole thing if it isn't necessary
[21:21] James: post is 3 years old though and I haven't followed it yet, something for the weekend
```

# 2023-02-26
Apparently NixOps is dying. Above won't be the correct approach in this case.

Use of pollen language as demonstrated here is interesting:
https://github.com/roman-kashitsyn/mmapped.blog

We don't want to use netlify to deploy, but aside from that:
* The repo layout is nice, just what's needed.
* The end result (the site itself) is very beautiful and achievable. The css
file is 750 lines long but there isn't much in the way of design aside from that.
The margin notes are lovely.
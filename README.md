GraphComment is an alternative to Disqus, which in my opinion looks a bit cluttered. GraphComment has a more clean look to me.

You need to sign up on https://www.graphcomment.com and get a free ID.

Usage:

Copy `graphcomment.html` to `/layout/shortcodes/graphcomment.html`

On your `*.md` page add `{{< graphcomment >}}` where the comments should show.

In your `config.toml` add your graphcomment ID: 

`[params]`  
`graphcommentId = "YOUR-ID-HERE"`

You can also import comments from Wordpress (only with the Wordpress app though), moderate comments on the graphcomment.com website. Their SPAM protection also works nicely.

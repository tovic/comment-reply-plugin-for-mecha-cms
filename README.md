Comment Reply Plugin for Mecha CMS
==================================

> Add ability to reply to a comment.

This is the base plugin, primarily used to enable the `$comment->parent` field in the response data. With this plugin, you can reply to the user comments either from the _frontend_ or _backend_ page.

~~~ .no-highlight
2016-01-15-17-14-08_2016-02-16-11-46-02_2016-02-14-10-33-26.txt
└────────┬────────┘ └────────┬────────┘ └────────┬────────┘
        [1]                 [2]                 [3]
~~~

 1. `$comment->post`
 2. `$comment->id`
 3. `$comment->parent`
``excalibur``: a template for making great readmes
====================================================

> "Too many developers forget that software development, even open-source, is 20% code and 80% people." -[bphogan](https://news.ycombinator.com/item?id=11083033)

### In this first section, you must explain what you care about, and what your problem is. You can then move on to explaining what your solution is, before concluding with how it works differently from most solutions.

Camelot is a big place with a lot of problems. Camelot is in desperate need of a leader.

Fortunately, ``excalibur`` is here, and it solves the problem of leader-finding better than anything else. It does so magically, and instantly. ``excalibur`` tells you whether or not a person is the leader that Camelot needs.

``excalibur`` works differently than most other attempted solutions. Specifically, Excalibur is really hard to pull out of a stone, so only real leaders can do it.

Installation
------------

    $ pip install excalibur

When in doubt, make installation a single line, then follow up with more complicated or platform-specific instructions:

    $ sudo easy_install excalibur

Usage
-----

``excalibur`` consists of a single function, but your magical and awesome package may consist of more. Here's where you briefly describe what each function does. 

``can_become_king()`` accepts a Django user object, and returns a bool. This method makes ``excalibur`` make sense, thanks to its name, its documentation, and the way it fits in with how Python and Django devs write code.

    excalibur = Excalibur()
    arthur = User.objects.get(first_name="Arthur")
    excalibur.can_become_king(arthur)
    > True

Try not to:
-----------
* be too technical. Focus on the pain of the users.
* be too brief. You need to do more than tell people how to use it. You have to tell them why they should.
* be too broad. It would be great if everyone used your open source project. But it's better to focus on a clear, small case where this solution is the best. First, find people who care more than anyone else. Second, make them care even more.

Projects using Excalibur
------------------------
* [autorepr](https://github.com/wolever/autorepr), which makes civilized string representations in Python


Further Reading
---------------
* [How to maintain a successful open source project](https://medium.com/code-zen/how-to-maintain-a-successful-open-source-project-aaa2a5437d3a#.bx4dhpjom), by [shazow](https://github.com/shazow)

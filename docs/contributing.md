---
layout: docs
title: Contributing
prev_section: upgrading
next_section: history
permalink: /docs/contributing/
---

So you've got an awesome idea to throw into OECPy. Great! Please keep the
following in mind:

* If you're creating a small fix or patch to an existing feature, just a simple
  test will do. Please stay in the confines of the current test suite and use...

<div class="note warning">
  <h5>Contributions will not be accepted without tests</h5>
  <p>
    If you’re creating a small fix or patch to an existing feature, just a simple test will do.

    Detailied test information cna be found ...
  </p>
</div>

Test Dependencies
-----------------

To run the test suite and build the gem you'll need to install OECPy's
dependencies...

Workflow
--------

Here's the most direct way to get your work merged into the project:

* Fork the project.
* Clone down your fork:

{% highlight bash %}
git clone git://github.com/<username>/open-exoplanet-catalogue-python.git
{% endhighlight %}

* Create a topic branch to contain your change:

{% highlight bash %}
git checkout -b my_awesome_feature
{% endhighlight %}


* Hack away, add tests. Not necessarily in that order.
* Make sure everything still passes by running 'command here'
* If necessary, rebase your commits into logical chunks, without errors.
* Push the branch up:

{% highlight bash %}
git push origin my_awesome_feature
{% endhighlight %}

* Create a pull request against ryanvarley/open-exoplanet-catalogue-python and describe what your change does and the why you think it should be merged.

Updating Documentation
----------------------

We want the OECPy documentation to be the best it can be. We've open-sourced our docs and we welcome any pull requests if you find it lacking.

You can find the documentation for jekyllrb.com in the
[site](https://github.com/ryanvarley/open-exoplanet-catalogue-python/tree/gh-pages) directory of
OECPy's repo on GitHub.com. Edit links are also included on documentation pages.

All documentation pull requests should be directed at `master`.  Pull
requests directed at another branch will not be accepted.


<div class="note">
  <h5>Let us know what could be better!</h5>
  <p>
    Both using and hacking on OECPy should be fun, simple, and easy, so if for
    some reason you find it’s a pain, please <a
    href="{{ site.github_url }}">create an issue</a> on
    GitHub describing your experience so we can make it better.
  </p>
</div>

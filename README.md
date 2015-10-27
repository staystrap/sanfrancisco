## Contributing
The content for each city is contained in a repository of its own.
For example, the tips for Brisbane in Australia can be found in [this one](http://github.com/staystrap/brisbane).
If you want to pass on your knowledge for a new city, check out the second section.
In case you just want to improve the info for an existing city, go on reading directly below.

### Working on existing content
Fork the repository, make your changes and create a pull request.
To create a new page, e.g. for sport activities or sights, simply create a file
like `activities.md` in the root of the repository. Be sure to include the following
markup at the beginning of the file:

```
---
layout: article
image: page_cover_image.jpg # this path is relative to the img/ folder
title: Activities # not too long!
---
```

The name of the file determines the sort order, which is the reason why some
files are prefixed with a letter and an underscore. You do not have to anything else,
the file title will just appear in the sidebar.

### Give tips for a new city
1.  **Duplicate (not fork)** the template repository, i.e. take the current working code and publish it in a repository of your own.
2.  Use the *gh-pages* branch.
3.  Change the file `_config.yaml` to reflect the new city appropriately.
    Please also adapt the color scheme to a sensible and well-readable setting
    to haven some visible distinction to other cities.
4.  Contribute content as you think right
5.  Edit the README.md so that it points to THIS file ([like so](https://github.com/staystrap/brisbane/blob/gh-pages/README.md)). This avoid outdated READMEs
5.  Transfer ownership of the repository to the **staystrap** organization.
6.  We will take you onboard then :)

## This is too complicated!
This system is not the best solution for this - albeit the cheapest and fastest,
non-CS students will probably not know how to use this. But do not give up, we still need your help!
If you can't be bothered with this, just drop us your structured input
and we will be happy to do the lifting ourselves: [felix.wolff2@student.hpi.de](mailto:felix.wolff2@student.hpi.de)

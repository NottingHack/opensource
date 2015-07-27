# Open Source at Nottingham Hackspace

We have a number of projects that are released under one or more open source licenses.  To contribute to these projects, we ask that you sign the Contributors License Agreement (CLA).

We do this to protect the open source nature of the projects.  If we decide to move a project from one open source license to another in the future, it would be hard without these in place.  It also means that you are certifying that all the contributions you are making are yours to make - you're not copying and pasting large chunks of commercial code into our projects.

Signing the CLA is easy:

1. First and foremost, read the [the current version of the
   CLA](cla-1.0.md) It is written to be as close to plain English as possible.

2. Make an account on GitHub if you don't already have one.

3. File a pull request on this project, that adds a single file - details below.

4. Wait for a team member to merge your pull request.


## Filing the Pull Request

If you don't yet know how to file a pull request, read [GitHub's
document about it](https://help.github.com/articles/using-pull-requests).

Make your pull request be the addition of a single file to the
[contributors](contributors) directory of this project. Name the file
with the same name as your GitHub userid, with `.md` appended to the
end. For example, for the user `danfuzz`, the full path to the file
would be `contributors/danfuzz.md`.

Put the following in the file:

```
[date]

I hereby agree to the terms of the Contributors License
Agreement, version 1.0, with MD5 checksum 107679e9eff24e29c5a87bb154710a26edb0829d.

I furthermore declare that I am authorised and able to make this
agreement and sign this declaration.

Signed,

[your name]
https://github.com/[your github userid]
```

Replace the bracketed text as follows:

* `[date]` with today's date, in the unambiguous numeric form `YYYY-MM-DD`.
* `[your name]` with your name.
* `[your github userid]` with your GitHub userid.

You can confirm the SHA-1 checksum of the CLA by running the sha1sum program over `cla-1.0.md`:

```
sha1sum cla-1.0.md
107679e9eff24e29c5a87bb154710a26edb0829d  cla-1.0.md
```

If the output is different from above, do not sign the CLA and let us know.

That's it!

## Credits

Thank you to [Medium](https://github.com/Medium) and [Apache](http://www.apache.org) - we used a lot of their work in building this.

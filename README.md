# Meta-tracker for bugs.python.org

bugs.python.org is essentially a custom workflow engine for the CPython core
development team. This means it needs a meta-tracker to track feature requests,
as well as a general issue tracker to track maintainability and usability issues.

Historically that meta-tracker has been maintained at http://psf.upfronthosting.co.za/roundup/meta,
but it doesn't need any kind of heavy customisation or integration with other tools, so GitHub
Issues serve the purpose better than maintaining a second Roundup instance does.

## Development workflow for bugs.python.org

bugs.python.org is a Roundup deployment, maintained as described in https://wiki.python.org/moin/TrackerDevelopment.

It uses Mercurial in order to simplify updating to new version of Roundup (which is still using Mercurial upstream).

See https://github.com/python/bugs.python.org/issues/2 for the discussion on potentially moving to a GitHub based
workflow that better aligns with the workflows used by other CPython core-workflow projects (while still accounting
for the need to periodically rebase on new upstream releases).

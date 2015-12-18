`miniminirepro/*` repos are starter templates for creating minimal reproductions for a variety of projects, generally for the purpose of reporting issues.

The `miniminirepro` branch in a `miniminirepro/*` repo will tell you what project it relates to and what branches to use for what.

The starters are not necessarily the absolute minimal possible -- they may make some assumptions about common cases. Add the minimum you need to, and trim anything you can (dependencies, settings, code, files).

These are the general instructions. The `README` in a specific repo's `miniminirepro` branch and other branches it mentions may provide more specific instructions.

* Clone the relevant repo.

* Checkout the relevant branch

* `$ git checkout --orphan {{new_branch_name}}`

* Make and commit your changes (including updating the `README` with any special instructions and deleting any instructions there may be for how to use the starter).

* Push to GitHub.

* Clone the repo you just pushed to a new directory and make sure it repros with your instructions.

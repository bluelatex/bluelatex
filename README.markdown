[![Stories Proposed](https://badge.waffle.io/bluelatex/bluelatex.png?label=Proposed&title=Proposed)](https://waffle.io/bluelatex/bluelatex)
[![Stories Accepted](https://badge.waffle.io/bluelatex/bluelatex.png?label=Accepted&title=Accepted)](https://waffle.io/bluelatex/bluelatex)
\BlueLaTeX Governance Project
=============================

This project is where the future of [\BlueLaTeX][0] is discussed. It is intended to let all stakeholders know where the project is going and to allow them to influence the direction it takes.

Most of the time you will not have to file a ticket here, and only need to directly open bug reports on the [server][1] or on the [client][2] project bug trackers
This project is where the high-level use cases are discussed, where the future of \BlueLaTeX is decided.
All discussions are open and anybody can take part of it, including asking for new features.

New Tickets
-----------

Tickets you may open here must describe high-level scenarios. For example one ticket for user registration without email validation would look like this:

> ### User registration without validation must be allowed
>
> The server must be able to be configured so that email validation is not required upon user registration.
> In such a case, the user is asked for a password that will protect the newly created account.
> In such a scenario, it must also be allowed to send a confirmation email, that is only informative to notify the owner of the email address that a new account was created on his name.

Discussion and Decision
-----------------------

All discussions about asked features are done via ticket comments, either directly via Github or (at your convenience) on the dedicated [waffle.io][3] project.

The \BlueLaTeX reserves the right to reject any feature or use case request on any ground, even if we hope we will not have to do it.
Opening an issue does not commit the \BlueLaTeX team in any way for any action.

Once a ticket has be opened, the discussion can start.
We may require a vote to decide whether a new ticket is accepted or rejected, but the \BlueLaTeX team reserves the right to unilaterally accept or reject it.
Of course, this is not the intention to force things or to hide requests there but the feature request list will be moderated.

Once the feature request is accepted, all impacted components of the project will be tagged so that contributors of the component can start working on it.

[0]: http://bluelatex.org
[1]: https://github.com/bluelatex/bluelatex-server/issues
[2]: https://github.com/bluelatex/bluelatex-web/issues
[3]: https://waffle.io/bluelatex/bluelatex

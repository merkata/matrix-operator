<!--
Avoid using this README file for information that is maintained or published elsewhere, e.g.:

* metadata.yaml > published on Charmhub
* documentation > published on (or linked to from) Charmhub
* detailed contribution guide > documentation or CONTRIBUTING.md

Use links instead.
-->

# matrix-operator

Charmhub package name: operator-template
More information: https://charmhub.io/matrix-operator

Describe your charm in one or two sentences.

## TODO

* get the synapse server running with basic settings (defaults plus server name and report stats) - done

* get the server to use a postgresql backend - done

* get the server to be accessible via ingress - done

* be able to create a user (via config change at this point)

* deal with configuration changes consistently (merge existing with new)

* move config in a storage - done

* explore an SSO option for signup

* check on Redis option present in architecture

* see how charm behaves when scaling in/out

* see how to disable users locally

* see how/when an SSO user is invalidated

* think about test cases for basic functionality

* look into using the new postgresql interface (the current one used is being deprecated)

* demo (spin up the charm with relations, configure two users, get them to chat via a client)

## Other resources

<!-- If your charm is documented somewhere else other than Charmhub, provide a link separately. -->

- [Read more](https://example.com)

- [Contributing](CONTRIBUTING.md) <!-- or link to other contribution documentation -->

- See the [Juju SDK documentation](https://juju.is/docs/sdk) for more information about developing and improving charms.

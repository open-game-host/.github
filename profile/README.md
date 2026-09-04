# Open Game Host

Quick, easy, and free local game hosting, for everyone!

## About Us

Open Game Host strives to create free, open-source tools for anyone to run and manage their own game
services locally, with minimum setup and maximum fun!

## Contributing / License

The _Open Game Host_ project is licensed under the [Apache-2.0](http://www.apache.org/licenses/LICENSE-2.0)
license. We love contributors, and are happy to hear any suggestions, bug reports, feature requests,
and more in our different project's issue tabs!

## Roadmap

This is an roadmap of features we have planned for the service. There is a bit more that needs to be
fleshed out further before we want to commit to adding them here, and any recommendations for
features are welcome!

- [ ] **Node Agent Daemon**
  - [ ] Manage game services.
    - [ ] Start and stop services.
    - [ ] Load services and states from persistant storage.
    - [ ] Create and delete new services.
      - [ ] Templated service runners.
      - [ ] Custom service runners.
    - [ ] Handle service logging.
    - [ ] Custom service updating behavior?
  - [ ] Connect to client.
    - [ ] Recieve service commands.
    - [ ] Send/recieve service I/O.
  - [ ] Report node & service health.
- [ ] **Node Controller** _(Coming Soon)_
- [ ] **SSH Command-Line Interface**
  - [ ] Authentication (Login)
  - [ ] Dashboard
    - [ ] Select service to manage.
    - [ ] Node health.
  - [ ] Service Management
    - [ ] Service health.
    - [ ] Start, stop, restart triggers.
    - [ ] Service I/O.
  - [ ] Create New Service Wizard
    - [ ] Create based on a template.
    - [ ] Create custom services?
  - [ ] SSH Access?
    - [ ] Connect to SSH-based app.
    - [ ] SSH-based authentication.

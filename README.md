## Developer Handbook
An always evolving overview about how we work together as a team. Suggestions are always welcome, just make a Pull Request.

The main takeway from our process is that while we need *good* over *perfect* we have to optimize for *perfect* as much as possible while the team grows and we can split responsabiblities.


### Rules and Conventions
We currently use a best-effort approach to most of our rules described here, for now only a few of them are actually enforced.

We do this to avoid growing pains and bikesheding while we build our team and shape our internal culture.

- MAY (Optional)
- SHOULD (Recommended)
- MUST (Enforced)

### Communication
We **MUST** use english for documentation, code comments and everything related to our software, this way we can scale our team worldwide.

We **MUST** create github issues for project tasks

We **MUST NOT** use synchronous channels(Whatsapp, Telegram, Workplace) for important information or discussion, email or github isses are better for these use cases.

Before changing something non-trivial in any project you **SHOULD** discuss the change with the code owner

https://www.youtube.com/watch?v=rX0ItVEVjHc### Programming Languages
We **SHOULD** keep our project stacks as homogenous as possible but sometimes we have problems that **MAY** be solved using other languages and tools.

#### Services:
- Default: Go
- Quick and Simple: PHP and Javascript
- Performance: C++ and Rust

#### Apps:
- Web: Javascript
- Mobile: React Native, Kotlin (?)

### Development Flow
Currently we use master as an staging branch which we **MUST** to never break, prod branch as production branch. By default all new code **SHOULD** be branched from master.

We have a CI(Continuous Integration) pipeline attached to the master branch and a CD(Continuous Delivery) pipeline attached to prod branch.

We **MAY** look into a proper gitflow(tags and releases) after the team has enough size, maturity and predictability to account for the overhead.

We **MUST** commit frequently with helpful messages

### Issues and Pull Requests
TODO

### Testing
TODO

### Tooling
TODO

### Code style

We **MUST** enforce consistent code style considering the programming language.

We **SHOULD** automate code formatation with git *commit-msg* hook.

We **SHOULD** follow community best practices.

We **MUST** aways be discussing about code style.

### Infrastructure

We **MUST** consider AWS as stable and reliable enough to host our entire infrastructure as dealing with multi-cloud and cloud abstraction with a small team is not viable.

We **SHOULD** treat infrastrucutre as code as much as possible

We **SHOULD** be careful to not allocate many more resources that we need,

We **MUST** allocate at least 30% more resources than we need currently to have enough room for new clients.

We **SHOULD** implement a proxy system for all the packages we need from external sources so we have a more stable ecosystem

### Open Source and Community

We **SHOULD** embrace open source where possible, this means open sourcing projects we are proud of that are not essential for our core business

We **SHOULD** behave profissionally while representing the company in public events.

We **MAY** host our own events but they **MUST** be held to really high standards and the presentations **MUST** be backed by real world production data, we **MAY** charge entrance fees

### Resources
- (Mike Acton - Data Oriented Design)[https://www.youtube.com/watch?v=rX0ItVEVjHc]
- 

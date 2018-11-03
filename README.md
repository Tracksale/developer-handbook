## Developer Handbook
An always evolving overview about how we work together as a team. Suggestions are always welcome, just make a Pull Request.

### Rules and Conventions
We currently use a best-effort approach to most of our rules described here, for now only a few of them are actually enforced.

We do this to avoid growing pains and bikesheding while we build our team and shape our internal culture.

- MAY (Optional)
- SHOULD (Recommended)
- MUST (Enforced)

### Communication
We **MUST** use english for documentation, code comments and everything related to our software, this way we can scale our team worldwide.

We **MUST** create github issues for project tasks

We **MUST NOT** use synchronous chat(Whatsapp, Telegram, Workplace) for important information or discussion, email or github isses are better for these use cases.

Before changing something non-trivial in any project you **SHOULD** discuss the change with the project owner

### Programming Languages
We **SHOULD** keep our project stacks as homogenous as possible but sometimes we have problems that **MAY** be solved using other languages and tools.

#### Services:
- Default: Go
- Quick and Simple: PHP and Javascript
- Performance: C++ and Rust

#### Apps:
- Web: Javascript
- Mobile: Kotlin (?)

### Development Flow
Currently we use master as an staging branch which we **MUST** to never break, prod branch as production branch. By default all new code **SHOULD** be branched from master.

We have a CI(Continuous Integration) pipeline attached to the master branch and a CD(Continuous Delivery) pipeline attached to prod branch.

We **MAY** look into a proper gitflow(tags and releases) after the team has enough size, maturity and predictability to account for the overhead.

We **SHOULD** commit frequently with helpful messages






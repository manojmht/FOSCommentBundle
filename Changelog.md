Changelog
=========

### 2.3.0 (2019-xx-xx)

* Removed deprecated transchoice tag.
* Updated deprecated routing syntax.
* Updated deprecated `TreeBuilder` usage.
* Updated deprecated unit test warnings.
* Switched all Twig classes to use PHP namespaces.
* If available, `ThreadController` will extend `AbstractController`.

### 2.2.1 (2019-03-29)

* Commands should use the manager alias.
* Fixed Romanian translation.
* Allow installation of `JMSSerializerBundle 3.x`.

### 2.2.0 (2018-06-04)

* Allow template override in Symfony 4.
* Commands are now lazy loaded.
* Service class parameters have been removed.
* Added autowire support for model managers.

### 2.1.0 (2018-03-04)

* Dropped PHP < 5.6 support.
* Dropped Symfony < 2.7 support.
* Dropped jQuery < 3 support.
* Dropped HHVM support.
* Added Symfony 4 support.
* Signature of `ThreadPermalinkListener` has been changed.
* Route `ThreadController::getThreadsActions` throws 404 if called without id's.
* Added pipeline parser to integrate several parsers together.
* Added flat view for async thread.
* Removed HTTP class constants in `ThreadController`.
* Fixed form disappearing when creating a new reply.
* Fixed failing validator with encoded permalink.

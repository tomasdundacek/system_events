# Changelog

## [Unreleased]
* Mix-and-match kwargs
  * Your listeners now do not need to listen for all kwargs sent by the event
  * However you need to include `PhantomEvents::Listener` in order for your listeners to work correctly

## [0.0.3] - 2023-01-15
* Update Sidekiq Adapter to be Sidekiq 7 compatible

## [0.0.2] - 2022-05-05
* Use RABBITMQ_URL instead of AMQP_URL ENV variable
* Add license information

## [0.0.1] - 2022-05-04
* Initial release

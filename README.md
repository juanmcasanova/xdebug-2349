# Xdebug Issue 2349

Steps to reproduce:

- Start the consumer: php bin/console messenger:consume async -vv
- Add a new message: php bin/console app:new-message

The consumer process should give a segfault at this point.

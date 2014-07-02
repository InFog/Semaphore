# Semaphore

Semaphore is a simple Python/Tkinter app to help monitoring status from a given
command.

I mainly use it for unit tests.

## Usage

Using semaphore is pretty simple, here are some examples:

 `semaphore -c "py.test" -t 5`

The line above will call semaphore to run py.test every 5 seconds.

For PHPUnit:

 `semaphore -c "phpunit unit" -t 2`

## Screenshots

Failing tests:

![Failing Tests](screenshots/red.png "Failing Tests")

Successful tests:

![Successful Tests](screenshots/green.png "Successful Tests")

have fun!

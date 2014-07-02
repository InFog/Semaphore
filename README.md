# Semaphore

Semaphore is a simple Python/Tkinter app to help monitoring status from a given
command.

I mainly use it for unit tests. I keep this little window in somewhere my
peripheral vison sees what is going on, since I don't always want to know the
exact reason for a test failing, I just want to know that something is broken.

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

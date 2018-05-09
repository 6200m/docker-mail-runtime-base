# docker-mail-runtime-base
The [Mail-Go](https://github.com/RiiConnect24/Mail-Go) scripts take advantage of Docker cache before building new changes to the source. However, after the fact in a second image, there is no possible way to cache libraries.

This standalone image allows us to have already installed dependencies.

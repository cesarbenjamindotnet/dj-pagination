# dj-pagination

This repo was forked to fix compatibility issues with geonode and django 4.2.x. Geonode 4.3.1 now is fully compatible, so, i have to archive this repo and delete it on Jan 2025.

[![https://travis-ci.org/pydanny/dj-pagination](https://travis-ci.org/pydanny/dj-pagination.svg?branch=master)](https://travis-ci.org/pydanny/dj-pagination)

[![https://codecov.io/github/pydanny/django-pagination?branch=master](https://codecov.io/gh/pydanny/dj-pagination/branch/master/graphs/badge.svg?branch=master&service=github)](https://codecov.io/gh/pydanny/dj-pagination)

# How to use dj-pagination

See our official documentation for more details.
http://dj-pagination.readthedocs.io/

# Support this Project!

- [Buy Two Scoops of Django 3.x to develop the skills to build better projects](https://www.feldroy.com/products/two-scoops-of-django-3-x)
- [Learn the fundamentals with Django Crash Course](https://www.feldroy.com/products/django-crash-course)
- [Sponsor the maintainer directly](https://github.com/sponsors/pydanny)


# About the fork

This project is a fork of the "django-pagination" project
originally written by 'Eric Florenzano' then forked by the Linaro
Validation/Infrastructure team. Latest releases can be found on pypi.


# About top-level package name change
The top level package name was changed from `pagination` to
`linaro_django_pagination` to `dj_pagination`. Following the Linaro pattern
I did this to ensure that existing users of the original package could easily
transition, on their own terms. Since both packages are co-installable you
are free to check things out and see if the new pagination code works well for
you or not.

Since the implementation of the actual tags were rewritten since the
django-pagination days it's fairly certain the new package is a NOT a
drop-in replacement.



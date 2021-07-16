==============
Django Leaflet
==============

See the `documentation <https://django-leaflet.readthedocs.io/en/latest/>`_ for more information.

*django-leaflet* allows you to use `Leaflet <http://leafletjs.com>`_
in your `Django <https://www.djangoproject.com>`_ projects.

It embeds Leaflet version *1.7.1*.

.. image:: https://readthedocs.org/projects/django-leaflet/badge/?version=latest
    :target: http://django-leaflet.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://img.shields.io/pypi/v/django-leaflet.svg
        :target: https://pypi.python.org/pypi/django-leaflet

.. image:: https://img.shields.io/pypi/dm/django-leaflet.svg
        :target: https://pypi.python.org/pypi/django-leaflet

.. image:: https://coveralls.io/repos/makinacorpus/django-leaflet/badge.png
    :target: https://coveralls.io/r/makinacorpus/django-leaflet


Main purposes of having a python package for the Leaflet Javascript library :

* Install and enjoy ;
* Do not embed Leaflet assets in every Django project ;
* Enjoy geometry edition with Leaflet form widget ;
* Control apparence and settings of maps from Django settings (e.g. at deployment) ;
* Reuse Leaflet map initialization code (e.g. local projections) ;

:note:

    *django-leaflet* is compatible with `django-geojson <https://github.com/makinacorpus/django-geojson.git>`_ fields, which
    allow handling geographic data without spatial database.

=========
TUTORIALS
=========

* `GeoDjango maps with Leaflet <http://blog.mathieu-leplatre.info/geodjango-maps-with-leaflet.html>`_


=======
AUTHORS
=======

* `Mathieu Leplatre <http://mathieu-leplatre.info>`_
* `Ariel Núñez <http://ingenieroariel.com>`_
* `Boris Chervenkov <https://github.com/boris-chervenkov>`_
* `Marco Badan <https://github.com/itbabu>`_
* `Bruno Renié <https://github.com/brutasse>`_
* `Simon Thépot <https://github.com/djcoin>`_
* `Thibault Jouannic <https://github.com/thibault>`_
* `jnm <https://github.com/jnm>`_
* `Manel Clos <https://github.com/manelclos>`_
* `Gaël Utard <https://github.com/gutard>`_
* `Alex Marandon <https://github.com/amarandon>`_
* `ollb <https://github.com/ollb>`_
* `smcoll <https://github.com/smcoll>`_
* `jnm <https://github.com/jnm>`_
* `OKso <https://github.com/oksome>`_
* `Florent Lebreton <https://github.com/fle/>`_
* `rgreenemun <https://github.com/rgreenemun>`_
* `Marco Badan <https://github.com/itbabu>`_
* David Martinez Morata
* `NotSqrt <https://github.com/NotSqrt>`_
* `Dylan Verheul <https://github.com/dyve>`_
* `Mactory <https://github.com/Mactory>`_
* `Petr Dlouhy <https://github.com/PetrDlouhy>`_
* `Kostya Esmukov <https://github.com/KostyaEsmukov>`_
* Yann Fouillat (alias Gagaro)

|makinacom|_

.. |makinacom| image:: http://depot.makina-corpus.org/public/logo.gif
.. _makinacom:  http://www.makina-corpus.com

=======
LICENSE
=======

* Lesser GNU Public License
* Leaflet Copyright - 2010-2011 CloudMade, Vladimir Agafonkin

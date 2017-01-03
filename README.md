# symfony-microkernel-edition

See documentation - [MicroKernelTrait](http://symfony.com/doc/current/configuration/micro_kernel_trait.html)

What's inside?
---------------

The Symfony MicroKernel Edition is configured with the following defaults:

  * Twig is the only configured template engine;

  * Doctrine ORM/DBAL is configured;

  * Annotations for everything are enabled.

It comes pre-configured with the following bundles:

  * **FrameworkBundle** - The core Symfony framework bundle

  * [**SensioFrameworkExtraBundle**][1] - Adds several enhancements, including
    template and routing annotation capability

  * [**DoctrineBundle**][2] - Adds support for the Doctrine ORM

  * [**TwigBundle**][3] - Adds support for the Twig templating engine

  * [**SecurityBundle**][4] - Adds security by integrating Symfony's security
    component

  * **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
    the web debug toolbar

  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions

  * [**SensioGeneratorBundle**][5] (in dev/test env) - Adds code generation
    capabilities

Enjoy!

[1]: http://symfony.com/doc/3.0/bundles/SensioFrameworkExtraBundle/index.html
[2]: http://symfony.com/doc/3.2/book/doctrine.html
[3]: http://symfony.com/doc/3.2/book/templating.html
[4]: http://symfony.com/doc/3.2/book/security.html
[5]: http://symfony.com/doc/3.0/bundles/SensioGeneratorBundle/index.html

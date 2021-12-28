The NFP Index
=============

This is an up-to-date list of all platforms that are officially part of the
**Not-For-Production Initiative**. Any platform on this list...

* ...is not necessarily flexible and does not necessarily encourage, facilitate,
  or even allow feature customization;

* ...is not necessarily optimized and does not necessarily encourage,
  facilitate, or even allow code optimizing;

* ...is not necessarily secure and does not necessarily encourage, facilitate,
  or even allow security strenghtening;

* ...tries to follow good practices defined by internal guidelines, but does not
  necessarily encourage, facilitate or even allow good practices defined by
  other guidelines.

"Not necessarily" means that, while they do aim for flexibility, optimization,
security, and good practices whenever possible, they prioritize:

* flattening of learning curve;

* absence of idiosyncrasies;

* minimization of boilerplate;

* maximization of readability.

In other words, they are *not adequate for production environments*. Instead,
their goal is *improving intrinsic motivation in programming classes*, by
providing a balance between *competence*, *autonomy*, and *relatedness*, the
three innate psychological needs defined by the [Self-Determination
Theory](https://selfdeterminationtheory.org/SDT/documents/2000_RyanDeci_SDT.pdf)
of [R. M. Ryan](http://www.sas.rochester.edu/psy/people/faculty/ryan_richard/)
and [E. L.
Deci](http://www.sas.rochester.edu/psy/people/faculty/deci_edward/index.html)

**Competence**, the desire to master the requirements and control the outcome,
is facilitated by the four characteristics above. They ensure that the
difficulty is defined by the learning objectives of the class, not by the
platform.

**Autonomy**, the desire to act accordingly to your own self, is facilitated by
high-level APIs that, despite the four characteristics above, still allow a
reasonable degree of freedom to decide what to do and how to do it.

**Relatedness**, the desire to care and be cared for, is facilitated by the
possibility of setting interesting and engaging goals regardless of programming
experience.


Platforms
---------

*Coming soon!*


Frequently Asked Questions
--------------------------

1. *Why define the platforms by their limitations?*

   We want people to know, as soon as possible, what exactly they are getting.
   Or, more appropriately, what they are *not* getting. We had some experiences
   in the past where people wanted to use a platform in a production environment
   and were disappointed to learn that certain improvements were not possible.

   We don't want people wasting their time deploying code that will need to be
   replaced, or writing pull requests that are not going to be accepted. We are
   aware of the limitations and want others to be aware of them too. Think of it
   as a programming version of [lampshade
   hanging](https://tvtropes.org/pmwiki/pmwiki.php/Main/LampshadeHanging).

2. *So you don't accept pull requests?*

   Of course we do. Having limitations by design does not mean *all* limitations
   are by design. Sometimes they are there [because we are
   incompetent](https://tvtropes.org/pmwiki/pmwiki.php/Main/SelfDeprecation).
   Any improvement consistent with our priorities is more than welcome.

3. *A developer needs to understand flexibility, optimization, security, and
   good practices. Aren't you encouraging bad programming?*

   This is, in fact, a possibility, but only if a limitation is directly related
   to a learning objective. For example, we wouldn't recommend using a NFP
   server in an assignment of an Information Security course. But if there are
   no direct relations to a learning objective, having the limitation is an
   acceptable tradeoff, as long as it is disclosed.

4. *It seems that the goal is making programming classes as easy as possible.
   Shouldn't a class have challenges?*

   It is more accurate to say that the goal is making programming classes easy
   as possible where it doesn't matter, while still allowing them to be as
   difficult as necessary where it matters. This improves not only the intrinsic
   motivation, but also the reliability of assessments.

5. *Why not use an established platform and provide scaffolds for the more
   difficult parts?*

   Scaffolding can, in fact, flatten the learning curve, but still leaves
   idiosyncrasies and boilerplate that might get in the way of learning goals.
   Scaffolding also defeats the purpose of using an established platform in the
   first place, since it is not actually taught.

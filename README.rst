tic_tac_taco_pizza
==================

🐍🌮🍕 Play tic tac toe, with taco and pizza

.. contents::


Installation
============

``tic_tac_taco_pizza`` requires Python 3.6+ and ``click``.

It is recommended that you install tic_tac_taco_pizza using a virtualenvironment.

::

   $ python3 -m venv venv
   $ source venv/bin/activate
   $ pip install tic_tac_taco_pizza


Usage
=====

::

   $ tic_tac_taco_pizza [--token TOKEN]

Options
-------

::

   --token TOKEN        specify a token, one of: `taco`, `pizza`, 🌮 , or 🍕


If ``--token`` is not passed, you will be asked to choose a token.

Demo
====

https://asciinema.org/a/132421


Premise
=======

Lets you play Tic Tac Toe, with 🌮 and 🍕 instead of ⭕ and ❌.


How it works
============

- You'll be asked, 🌮 or 🍕
- A 👊 📃 ✂️  (rock, paper, scissor) will determine the next player
- Keep playing until it ends.
- Exit anytime by ``ctrl-C``


ambitious plan 😱
=================

- make into mobile app with `Toga <https://pybee.org/project/projects/libraries/toga/>`_


when
====

v 0.1.0 was made during PyConAU 2017 sprint.


conclusion
==========

🌮 is the new 🎉
  

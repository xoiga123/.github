.. ## 

.. <!--

.. **Here are some ideas to get you started:**

.. 🙋‍♀️ A short introduction - what is your organization all about?
.. 🌈 Contribution guidelines - how can the community get involved?
.. 👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
.. 🍿 Fun facts - what does your team eat for breakfast?
.. 🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
.. -->

Hello there! Welcome to unifyai👋
==============

.. image:: https://github.com/unifyai/unifyai.github.io/blob/master/img/externally_linked/logo.png?raw=true
   :width: 100%

.. raw:: html

    <br/>
    <div align="center">
    <a href="https://github.com/unifyai/ivy/issues">
        <img style="float: left; padding-right: 4px; padding-bottom: 4px;" src="https://img.shields.io/github/issues/unifyai/ivy">
    </a>
    <a href="https://github.com/unifyai/ivy/network/members">
        <img style="float: left; padding-right: 4px; padding-bottom: 4px;" src="https://img.shields.io/github/forks/unifyai/ivy">
    </a>
    <a href="https://github.com/unifyai/ivy/stargazers">
        <img style="float: left; padding-right: 4px; padding-bottom: 4px;" src="https://img.shields.io/github/stars/unifyai/ivy">
    </a>
    <a href="https://github.com/unifyai/ivy/pulls">
        <img style="float: left; padding-right: 4px; padding-bottom: 4px;" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg">
    </a>
    <a href="https://pypi.org/project/ivy-core">
        <img style="float: left; padding-right: 4px; padding-bottom: 4px;" src="https://badge.fury.io/py/ivy-core.svg">
    </a>
    <a href="https://github.com/unifyai/ivy/actions?query=workflow%3Adocs">
        <img style="float: left; padding-right: 4px; padding-bottom: 4px;" src="https://github.com/unifyai/ivy/actions/workflows/docs.yml/badge.svg">
    </a>
    <a href="https://github.com/unifyai/ivy/actions?query=workflow%3Atest-ivy">
        <img style="float: left; padding-right: 4px; padding-bottom: 4px;" src="https://github.com/unifyai/ivy/actions/workflows/test-ivy.yml/badge.svg">
    </a>
    <a href="https://discord.gg/G4aR9Q7DTN">
        <img style="float: left; padding-right: 4px; padding-bottom: 4px;" src="https://img.shields.io/discord/799879767196958751?color=blue&label=%20&logo=discord&logoColor=white">
    </a>
    </div>
    <br clear="all" />

**We’re on a mission to unify all ML frameworks 💥 + automate code conversions 🔄. Join our growing community 😊, and lets-unify.ai! 🦾**

Ivy is an ML framework that currently supports JAX, TensorFlow, PyTorch, MXNet, and Numpy. We’re very excited for you to try it out!

**What is Ivy?**

Ivy is a unified machine learning framework which maximizes the portability of machine learning codebases.
Ivy wraps the functional APIs of existing frameworks.
Framework-agnostic functions, libraries and layers can then be written using Ivy,
with simultaneous support for all frameworks.
Ivy currently supports Jax, TensorFlow, PyTorch, MXNet and Numpy. Check out the `docs <https://lets-unify.ai/ivy>`_ for more info!

**Ivy Libraries**

There are a host of derived libraries written in Ivy, in the areas of mechanics, 3D vision, robotics, gym environments,
neural memory, pre-trained models + implementations, and builder tools with trainers, data loaders and more. Click on the icons below to learn more!

.. raw:: html

   <style>
  .badge-table {
    display: table;
    width: 100%;
  }
  .badge-row {
    display: table-row;
  }
  .badge-cell {
    display: table-cell;
    width: 25%;
    text-align: center;
    vertical-align: top;
    padding: 10px;
  }
  .sub-badge {
    display: inline-block;
    margin-top: 7px;
    width: 80%;
  }
  </style>

  <div class="badge-table">
  <div class="badge-row">
    <div class="badge-cell">
      <a href="https://github.com/ivy-dl/mech"><img src="https://raw.githubusercontent.com/ivy-dl/ivy-dl.github.io/master/img/externally_linked/logos/ivy_mech.png"></a>
      <div class="sub-badge">
        <a href="https://pypi.org/project/ivy-mech"><img src="https://badge.fury.io/py/ivy-mech.svg"></a>
      </div>
      <div class="sub-badge">
        <a href="https://github.com/ivy-dl/mech/actions?query=workflow%3Anightly-tests"><img src="https://github.com/unifyai/mech/actions/workflows/nightly-tests.yml/badge.svg"></a>
      </div>
    </div>
    <div class="badge-cell">
      <a href="https://github.com/ivy-dl/vision"><img src="https://raw.githubusercontent.com/ivy-dl/ivy-dl.github.io/master/img/externally_linked/logos/ivy_vision.png"></a>
      <div class="sub-badge">
        <a href="https://pypi.org/project/ivy-vision"><img src="https://badge.fury.io/py/ivy-vision.svg"></a>
      </div>
      <div class="sub-badge">
        <a href="https://github.com/ivy-dl/vision/actions?query=workflow%3Anightly-tests"><img src="https://github.com/unifyai/vision/actions/workflows/nightly-tests.yml/badge.svg"></a>
      </div>
    </div>
    <div class="badge-cell">
      <a href="https://github.com/ivy-dl/robot"><img src="https://raw.githubusercontent.com/ivy-dl/ivy-dl.github.io/master/img/externally_linked/logos/ivy_robot.png"></a>
      <div class="sub-badge">
        <a href="https://pypi.org/project/ivy-robot"><img src="https://badge.fury.io/py/ivy-robot.svg"></a>
      </div>
      <div class="sub-badge">
        <a href="https://github.com/ivy-dl/gym/robot?query=workflow%3Anightly-tests"><img src="https://github.com/unifyai/robot/actions/workflows/nightly-tests.yml/badge.svg"></a>
      </div>
    </div>
    <div class="badge-cell">
      <a href="https://github.com/ivy-dl/gym"><img src="https://raw.githubusercontent.com/ivy-dl/ivy-dl.github.io/master/img/externally_linked/logos/ivy_gym.png"></a>
      <div class="sub-badge">
        <a href="https://pypi.org/project/ivy-gym"><img src="https://badge.fury.io/py/ivy-gym.svg"></a>
      </div>
      <div class="sub-badge">
        <a href="https://github.com/ivy-dl/gym/actions?query=workflow%3Anightly-tests"><img src="https://github.com/unifyai/gym/actions/workflows/nightly-tests.yml/badge.svg"></a>
      </div>
    </div>
  </div>
  <div class="badge-row">
    <div class="badge-cell">
      <a href="https://github.com/unifyai/memory"><img src="https://raw.githubusercontent.com/unifyai/unifyai.github.io/master/img/externally_linked/logos/ivy_memory.png"></a>
      <div class="sub-badge">
        <a href="https://pypi.org/project/ivy-memory"><img src="https://badge.fury.io/py/ivy-memory.svg"></a>
      </div>
      <div class="sub-badge">
        <a href="https://github.com/ivy-dl/memory/actions?query=workflow%3Anightly-tests"><img src="https://github.com/unifyai/memory/actions/workflows/nightly-tests.yml/badge.svg"></a>
      </div>
    </div>
    <div class="badge-cell">
      <a href="https://github.com/unifyai/builder"><img src="https://raw.githubusercontent.com/unifyai/unifyai.github.io/master/img/externally_linked/logos/ivy_builder.png"></a>
      <div class="sub-badge">
        <a href="https://pypi.org/project/ivy-builder"><img src="https://badge.fury.io/py/ivy-builder.svg"></a>
      </div>
      <div class="sub-badge">
        <a href="https://github.com/ivy-dl/builder/actions?query=workflow%3Anightly-tests"><img src="https://github.com/unifyai/builder/actions/workflows/nightly-tests.yml/badge.svg"></a>
      </div>
    </div>
    <div class="badge-cell">
      <a href="https://github.com/unifyai/models"><img src="https://raw.githubusercontent.com/unifyai/unifyai.github.io/master/img/externally_linked/logos/ivy_models.png"></a>
      <div class="sub-badge">
        <a href="https://pypi.org/project/ivy-models"><img src="https://badge.fury.io/py/ivy-models.svg"></a>
      </div>
      <div class="sub-badge">
        <a href="https://github.com/ivy-dl/models/actions?query=workflow%3Anightly-tests"><img src="https://github.com/unifyai/models/actions/workflows/nightly-tests.yml/badge.svg"></a>
      </div>
    </div>
    <div class="badge-cell">
      <a href="https://github.com/unifyai/ecosystem"><img src="https://raw.githubusercontent.com/unifyai/unifyai.github.io/master/img/externally_linked/logos/ivy_ecosystem.png"></a>
      <div style="margin-top: 16px" class="sub-badge">
        <a href="https://github.com/unifyai/ecosystem/actions?query=workflow%3Adocs"><img src="https://github.com/unifyai/ecosystem/actions/workflows/docs.yml/badge.svg"></a>
      </div>
    </div>
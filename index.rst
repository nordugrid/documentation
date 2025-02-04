======================================================================
Norwegian Research Infrastructure Services
======================================================================

The Norwegian academic high-performance computing and storage infrastructure is
maintained by `NRIS <https://sigma2.no/nris>`__ (formerly known as *the
Metacenter*), which is a joint collaboration between `UiO
<https://www.uio.no>`__, `UiB <https://www.uib.no>`__, `NTNU
<https://www.ntnu.no>`__, `UiT <https://uit.no>`__, and `Sigma2
<https://www.sigma2.no/>`__.

We provide valuable resources for the research communities. Not only do we provide
state-of-the art :ref:`compute <hardware-overview>` and :ref:`storage facilities <nird>`,
backed by :ref:`support <support-line>` and a guarantee that your data always
stays in Norway. But possibly more important is :ref:`easy access <extended-support>` to a wide selection
of competences that can assist, realize or take your project to the next level.

This website (https://documentation.sigma2.no/) primarily holds documentation
of resources we provide. For more general information and service overview,
please also see https://www.sigma2.no.

.. note::

   **Latest news and announcements** are posted at the `NRIS
   OpsLog <https://opslog.sigma2.no>`__ and the
   `@NRISstatus <https://twitter.com/NRISstatus.>`__ Twitter channel.


Compute, storage, pre/post-processing, visualization, machine learning
----------------------------------------------------------------------

We offer compute resources (:ref:`betzy`, :ref:`fram`, and :ref:`saga`,
storage resources (:ref:`nird`),
as well as the `NIRD
Toolkit <https://www.sigma2.no/nird-toolkit>`__ platform for pre- and
post-processing analysis, data intensive processing, visualization,
artificial intelligence, and machine learning.

Researchers also have access to :ref:`lumi` through the
LUMI consortium.


First time on a supercomputer?
------------------------------

Please read the **GETTING STARTED** section (left sidebar). In the
sidebar overview you will also find technical details about the
machines, instructions for using installed software, for submitting
jobs, storage, and code development.

Please do not hesitate to write to support@nris.no if you find
documentation sections which are not clear enough or have suggestions
for improvements. Such a feedback is very important to us and will
count.


How to get the most out of your allocation
------------------------------------------

We want to support researchers in getting the most out of the
high-performance computing services. When supporting users, we see that
these problems are very frequent:

- **Reusing outdated scripts** from colleagues without adapting them to
  optimal parameters for the cluster at hand and thus leaving few cores
  idle. Please check at least how many cores there are on a particular
  cluster node.
- **Requesting too much memory** which leads to longer queuing and less
  resource usage. Please check :ref:`choosing-memory-settings`.
- **Requesting more cores than the application can effectively use** without
  studying the scaling of the application. You will get charged more than
  needed and others cannot run jobs. If others do this, your own jobs queue.
- **Submitting jobs to the wrong queue** and then queuing longer than
  needed. Please take some time to study the different :ref:`job-types`.

If you are unsure about these, please contact us via
support@nris.no and we will help you to use your allocated
resources more efficiently so that you get your research results faster.

--------------

Acknowledging use of national HPC infrastructure
------------------------------------------------

Projects are required to acknowledge the use of the national e-infrastructure
resources in their scientific publications. Papers, presentations and other
publications that feature work that relied on resources provided by Sigma2
should include an `acknowledgement following this template
<https://www.sigma2.no/acknowledgements>`__.

Text is licensed CC-BY
----------------------

Unless explicitly noted, all text on this website is made available
under the `Creative Commons Attribution license
(CC-BY-4.0) <https://creativecommons.org/licenses/by/4.0/>`__ with
attribution to NRIS.

--------------

Index of keywords
-----------------

:ref:`genindex`

--------------

.. toctree::
   :maxdepth: 1
   :caption: Policies

   code-of-conduct.md

.. toctree::
   :maxdepth: 1
   :caption: News

   Latest changes and events <https://opslog.sigma2.no>
   Hardware live status <https://www.sigma2.no/hardware-status>
   known-issues.md


.. toctree::
   :maxdepth: 1
   :caption: Getting help

   getting_help/support_line.md
   getting_help/extended_support.rst
   getting_help/faq.md
   getting_help/how_to_write_good_support_requests.md
   getting_help/user_communities.md
   getting_help/qa-sessions.md
   getting_help/lost_forgotten_password.md
   getting_help/project_leader_support.md



.. toctree::
   :maxdepth: 1
   :caption: Training

   training/events.md
   training/material.md


.. toctree::
   :maxdepth: 1
   :caption: Getting started

   getting_started/getting_started.md
   getting_started/applying_account.md
   getting_started/applying_resources.md
   getting_started/editing_files.md
   getting_started/create_ssh_keys.md
   getting_started/tutorials.rst


.. toctree::
   :maxdepth: 1
   :caption: Services

   nird_archive/user-guide.md
   nird_toolkit/overview.rst
   services/easydmp-user-documentation.md
   getting_help/course_resources.md


.. toctree::
   :maxdepth: 1
   :caption: High-performance computing

   hpc_machines/hardware_overview.md
   hpc_machines/betzy.md
   hpc_machines/fram.md
   hpc_machines/saga.md
   hpc_machines/lumi.md
   hpc_machines/migration2metacenter.md
   computing/responsible-use.md
   jobs/overview.rst
   code_development/overview.rst
   computing/tuning-applications.md


.. toctree::
   :maxdepth: 1
   :caption: Software

   software/modulescheme.md
   software/installed_software.md
   software/userinstallsw.rst
   software/containers.md
   software/appguides.md
   software/licenses.md


.. toctree::
   :maxdepth: 1
   :caption: Files and Storage

   files_storage/nird.md
   files_storage/clusters.md
   files_storage/quota.md
   files_storage/backup.md
   files_storage/sharing_files.md
   files_storage/file_transfer.md
   files_storage/performance.md
   files_storage/dos_and_donts.md

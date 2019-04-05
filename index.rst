|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

Quick start of JupyterLab-QIIME2 VICE app in DE
================================================

Goal
----

`QIIME 2™ <https://qiime2.org/>`_ is a next-generation microbiome bioinformatics platform that is extensible, free, open source, and community developed. 

- Automatically track your analyses with decentralized data provenance — no more guesswork on what commands were run!

- Interactively explore your data with beautiful visualizations that provide new perspectives.

- Easily share results with your team, even those members without QIIME 2 installed.

- Plugin-based system — your favorite microbiome methods all in one place.

In this quick start, we will show you how to launch JupyterLab-QIIME2 VICE app in DE

Prerequisites
-------------

Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*

	.. list-table::
	    :header-rows: 1

	    * - Prerequisite
	      - Preparation/Notes
	      - Link/Download
	    * - CyVerse account
	      - You will need a CyVerse account to complete this exercise
	      - `Register <https://user.cyverse.org/>`_

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Documentation
      - Learning Center Docs
    * - Discovery Environment
      - Web/Point-and-click
      - `Discovery Environment <https://de.cyverse.org/de/>`_
      - `DE Manual <https://wiki.cyverse.org/wiki/display/DEmanual/Table+of+Contents>`_
      - `Guide <https://learning.cyverse.org/projects/discovery-environment-guide/en/latest/>`__

Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this quickstart you will need to have the following inputs prepared*

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Example Data
    * - Sequencing reads
      - `FastQ <https://en.wikipedia.org/wiki/FASTQ_format>`_
      - Any sequencing reads in FastQ format will work. They do not
        need to be pre-processed. They may also be compressed (e.g.
        fastq.gz)
      - gut microbiome

-----

*Get started: Launch JupyterLab-QIIME2*
---------------------------------------

1. Login to the |discovery_enviornment|.

2. Click on **Apps** window in the DE workspace and search for and run JupyterLab-Qiime2-2018.11.

3. Under “Analysis Name” leave the defaults or make any desired notes.

4. Under “Parameters” for ‘Input folder' or 'Input files', click Browse, then navigate to and
   select one or more FastQ files to analyze; Then click OK.

   .. Note::

	    To use our example data, navigate to *Community Data >*
	    *iplantcollaborative > example_data > qiime2  and select gut-microbiome folder.*

5. Click **Launch Analysis**. You will receive a notification that the job has been submitted and running with the "Access your running analysis here". 

6. Clicking on the "Access your running analysis" will open the JupyterLab-QIIME2 in another tab in the browser after a brief building phase.

.. Note::

  You will be asked to authenticate again to the JupyterLab with your CyVerse username and password

7. You will see the input data under "vice" folder of the JuptyerLab. Now you can upload your own Jupyter Notebook or create one using one of the available kernels

.. warning::

  Do not create or store any outputs inside the input folder (gut-microbiome) as those outputs are not brought back after the analysis

8. Finally, once you finish analysis, navigate to the DE tab, select the Analysis window and select the analysis, click "save and complete analysis". Upon clicking complete analysis, the analysis will be completed and all the outputs will be brought back to the analysis folder.

----

Additional information, help
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- See the original `JupyterLab quick start <https://learning.cyverse.org/projects/vice/en/latest/user_guide/quick-jupyter.html>`_ 

- See the original qiime2.org for how to run qiime2 analysis

- Search for an answer: `CyVerse Learning Center <http://learning.cyverse.org>`_ or `CyVerse Wiki <https://wiki.cyverse.org>`_

- Post your question to the user forum:
`Ask CyVerse <http://ask.iplantcollaborative.org/questions>`_

----

**Fix or improve this documentation**

- On Github: `Repo link <https://github.com/CyVerse-learning-materials/fastqc_quickstart>`_
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home`_

.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
.. _CyVerse logo: http://learning.cyverse.org/
.. |Home_Icon| image:: ./img/homeicon.png
    :width: 25
    :height: 25
.. _Home_Icon: http://learning.cyverse.org/
.. |discovery_enviornment| raw:: html

    <a href="https://de.cyverse.org/de/" target="_blank">Discovery Environment</a>
Class 3 - NGINX Dataplane Scripting
===================================

This class will introduce the student to customizing NGINX using NGINX JavaScript (njs)

**Lab Environment**

In each lab we will configure an NGINX server to either provide content itself or act as a reverse proxy that retrieves content from other servers.

This lab uses Docker containers to run everything in a single NGINX VM. While Docker containers are ideal for running NGINX, the same concepts apply when running NGINX in a VM or on a bare metal server.

**Verify the NGINX VM is Ready**

Click on ACCESS and then WEB SHELL. Then run the follwing commnands.

  .. image:: images/access.png

*(Note: The command is highlighted. The output is not.)*

.. code-block:: shell
  :emphasize-lines: 1,4

  git --version
  git version 2.25.0
  
  docker --version
  Docker version 19.03.8, build afacb8b

If both the git and docker commands work, you are ready to continue by clicking the next button below.

Expected time to complete: **1 hour**

*A listing of the modules for this class is listed below.  This same list is also available on the left column of every page for direct access.*

.. toctree::
   :maxdepth: 1
   :glob:

   module*/module*


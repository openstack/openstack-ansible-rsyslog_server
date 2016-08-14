========================
OpenStack rsyslog server
========================

Role to deploy rsyslog for use within OpenStack when deploying services using
containers.

Table of contents
~~~~~~~~~~~~~~~~~

.. toctree::
   :maxdepth: 2

   ops-logging.rst

Default variables
~~~~~~~~~~~~~~~~~

.. literalinclude:: ../../defaults/main.yml
   :language: yaml
   :start-after: under the License.

Required varibles
~~~~~~~~~~~~~~~~~

None

Example playbook
^^^^^^^^^^^^^^^^

.. literalinclude:: ../../examples/playbook.yml
   :language: yaml

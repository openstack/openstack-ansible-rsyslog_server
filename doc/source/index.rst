rsyslog_server Docs
===================

Installation of Rsyslog to receive shipped logs.

Basic Role Example
^^^^^^^^^^^^^^^^^^

.. code-block:: yaml

    - name: Install rsyslog
      hosts: localhost
      user: root
      roles:
        - { role: "rsyslog_server", tags: [ "rsyslog-server" ] }

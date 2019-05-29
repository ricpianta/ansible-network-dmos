===========================
Ansible Network datacom_dmos
===========================

.. _Ansible Network datacom_dmos_v2.7.1:

v2.7.1
======

.. _Ansible Network datacom_dmos_v2.7.1_New Tasks:

New Tasks
---------

- Add ``configure_vlan`` task.

- Add ``configure_system_properties`` task.

- Add ``configure_lldp`` task.


.. _Ansible Network datacom_dmos_v2.7.0:

v2.7.0
======

.. _Ansible Network datacom_dmos_v2.7.0_Major Changes:

Major Changes
-------------

- Initial release of 2.7.0 ``datacom_dmos`` Ansible role that is supported with Ansible 2.7.0


.. _Ansible Network datacom_dmos_v2.6.1:

v2.6.1
======

.. _Ansible Network datacom_dmos_v2.6.1_New Tasks:

New Tasks
---------

- Add ``configure_user`` task.


.. _Ansible Network datacom_dmos_v2.6.0:

v2.6.0
======

.. _Ansible Network datacom_dmos_v2.6.0_Major Changes:

Major Changes
-------------

- Initial release of the ``datacom_dmos`` Ansible role.

- This role provides functions to perform automation activities on Datacom DmOS devices.


.. _Ansible Network datacom_dmos_v2.6.0_New Functions:

New Functions
-------------

- NEW ``get_facts`` function can be used to collect facts from Datacom DmOS devices.

- NEW ``config_manager/get`` function returns the either the current active or current saved configuration from Datacom DmOS devices.

- NEW ``config_manager/load`` function provides a means to load a configuration file onto a target device running Datacom DmOS.

- NEW ``config_manager/save`` function saves the current active (running) configuration to the startup configuration.


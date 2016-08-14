Ansible Role for NFS Exports Management
======================================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-nfs-export.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-nfs-export)
[![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-nfs-export.svg)](https://github.com/pantarei/ansible-role-nfs-export)
[![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-nfs-export.svg)](https://github.com/pantarei/ansible-role-nfs-export/blob/master/LICENSE)

Ansible Role for NFS Exports Management.

Requirements
------------

This role require Ansible 2.0 or higher.

This role was designed for Ubuntu Server 14.04 LTS and Ubuntu Server 16.04 LTS.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>nfs_export</td>
<td>yes</td>
<td><a href="https://github.com/pantarei/ansible-role-nfs-export/blob/master/defaults/main.yml">defaults/main.yml</a></td>
<td></td>
<td>A list of export.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: hswong3i.nfs_export

License
-------

-   Code released under [MIT](https://github.com/pantarei/ansible-role-nfs-export/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <a href="https://twitter.com/hswong3i" class="uri" class="uri">https://twitter.com/hswong3i</a>
    -   <a href="https://github.com/hswong3i" class="uri" class="uri">https://github.com/hswong3i</a>


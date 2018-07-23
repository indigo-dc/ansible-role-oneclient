oneclient Role
=========

Install oneclient 
(following instructions provided here: https://beta.onedata.org/docs/doc/getting_started/downloading_onedata.html)

Role Variables
--------------

- `onedata_url`: base URL of the onedata packages repo (default: http://packages.onedata.org)
- `oneclient_package` (default: oneclient): allows to specify a different package version, e.g. oneclient-18.02.0.rc9 

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: indigo-dc.oneclient }

License
-------

Apache Licence v2 [1]

[1] http://www.apache.org/licenses/LICENSE-2.0


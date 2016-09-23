NordVPN  
=======  

Install and update the NordVPN list of servers and leave it setup to autologin.

Requirements
------------

This role provides all the requirements it needs

Role Variables
--------------

vpnuser: NordVPN user (email) - defaults NULL
vpnpassword: NordVPN password - defaults NULL
autostart: the VPN you want your destiny uses from boot up - defaults None
optargs: arguments you want to use in openvpn when it starts up

Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: vpnclients
      roles:
      - { role: nordvpn, vpnuser: user0@example.com, vpnpassword: superpassword, autostart: ru4.nordvpn.com.udp1194.ovpn }


License
-------

BSD

Author Information
------------------

Any fix request or suggestions or merge-request will be gladly attended via http://github.com/ieguiguren/ansible-nordvpn

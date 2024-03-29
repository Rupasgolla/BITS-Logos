- For BITS Logos goto directory - /etc/kolla
- Change Logo on Horizon Kolla-Ansible
- Goto all controller nodes and below steps

# cd /etc/kolla/
# git clone https://github.com/Rupasgolla/Logos
# cd /etc/kolla/Logos


# docker cp logo-splash.svg horizon:/var/lib/kolla/venv/lib/python3.9/site-packages/static/dashboard/img
# docker cp logo.svg horizon:/var/lib/kolla/venv/lib/python3.9/site-packages/static/dashboard/img
# docker cp favicon.ico horizon:/var/lib/kolla/venv/lib/python3.9/site-packages/static/dashboard/img

# docker restart horizon

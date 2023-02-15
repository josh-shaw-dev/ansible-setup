You will need ansible installed

 1. Install deps
	 1. `ansible-galaxy install geerlingguy.docker`
	 2. `ansible-galaxy install geerlingguy.pip`
	 3. `ansible-galaxy collection install ansible.posix`
	 4. `ansible-galaxy collection install community.docker`
	 5. `ansible-galaxy install rossmcdonald.influxdb` 
 2.  Edit `/etc/ansible/hosts`
	 1. Add the hosts/tags required
 3. Run the main playbook
	 1. `ansible-playbook -K -l all main.yml`


